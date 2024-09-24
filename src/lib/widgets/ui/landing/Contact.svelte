<script>
    import {contacts} from '$shared';
</script>

<section class="section padding-tb4">
  <a name="contact"></a>

  <div class="container">
    <div class="split-section">
      <div  class="split-ig-section-content bg-beige">
        <div class="split-ig-title">
          <h2 class="alternative-title">Kontakt ze mną? ☎️</h2>
        </div>
        <div class="big-paragraph">
          Zawsze jestem otwarty na nowe znajomości i propozycje, jeśli masz pomysły na współtworzenie, możesz wysłać do mnie e-mail lub za pośrednictwem mediów.
        </div>

        <div class="social-icons mb-8">
          {#each contacts as {title, icon, data}}
          <a href="{data}" target="_blank" class="social-links w-inline-block">
            <img src="{icon}" loading="lazy" alt="{title} icon" class="social-icon">
          </a>

          {/each}
        </div>

        <div class="big-paragraph">
          W razie jakichkolwiek pytań proszę o <a href="#faq">zwrócenie uwagi na blok F.A.Q.</a> - jeśli nie ma tam odpowiedzi, możesz śmiało pytać mnie w prywatnych wiadomościach.
        </div>
      </div>

      <div class="split-ig-image-wrapper">
        <div class="w-layout-grid split-ig-grid">
          <div class="split-ig-image social-4">
            <img src="images/process_2.jpg" loading="lazy" sizes="(max-width: 991px) 100vw, 45vw"  alt="" class="image-cover">
          </div>
          <div class="split-ig-image social-4">
            <img src="images/heart.svg" loading="lazy" sizes="(max-width: 479px) 100vw, (max-width: 767px) 90vw, (max-width: 991px) 46vw, 45vw"  alt="" class="image-cover">
          </div>
          <div   class="split-ig-image social-4">
            <img src="images/hello.svg" loading="lazy" sizes="(max-width: 479px) 100vw, (max-width: 767px) 90vw, (max-width: 991px) 46vw, 45vw" alt="" class="image-cover">
          </div>
          <div  class="split-ig-image social-3 ">
            <img src="images/oleg.JPG" loading="lazy" sizes="(max-width: 991px) 100vw, 45vw"  alt="" class="image-cover">
          </div>
        </div>
      </div>
    </div>
  </div>
</section>



<style>

</style>
