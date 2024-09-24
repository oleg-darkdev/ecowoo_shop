<<<<<<< HEAD
<script>
  import {categories} from '$shared';
</script>

<footer class="footer-section ">
  <div class="footer ">
    <div class="footer-container ">
      <div class="footer-logo-wrapper ">
        <!-- <div class="form-block newsletter w-form">
          <form id="wf-form-Footer-Newsletter" name="wf-form-Footer-Newsletter" data-name="Footer Newsletter" action="https://setpember.us10.list-manage.com/subscribe/post?u=857231acd9b2572aad17d8078&amp;id=f405cfdbe5&amp;f_id=008429e2f0" method="post" class="underlined-form" data-wf-page-id="637103ed71bc7300c0b4bb41" data-wf-element-id="b9972bd1-2082-b01c-3289-1b91d5bb9398">
            <input class="underlined-input w-input" maxlength="256" name="Email" data-name="Email" placeholder="E-Mail Adresse" type="email" id="Email-2">
            <input type="submit" data-wait="paar Sekunden..." class="button-2 unicorn-bg newsletter w-button" value="Newsletter abonnieren">
          </form>
          <div class="form-success w-form-done">
            <div>Danke! Deine Anmeldung ist eingegangen!</div>
          </div>
          <div class="form-error w-form-fail">
            <div>Oops! Da scheint etwas nicht funktioniert zu haben.</div>
          </div>
        </div> -->
        <div>
          <div class="footer-logo-wrap">
            <img src="images/logo_light.svg" loading="lazy" alt="" class="footer-logo">
            <div class="all-caps footer">Sklep z handmade upominkami.</div>
          </div>
          <div class="social-icons footer">
            <a href="/" class="social-links footer w-inline-block">
              <img src="images/621e78476ef4b5e780a65c7a_social_icon_instagram.svg" loading="lazy" alt="" class="social-icon footer">
            </a>
            <a href="/" class="social-links footer w-inline-block">
              <img src="images/621e7847d9afce6372d844a8_social_icon_facebook.svg" loading="lazy" alt="" class="social-icon footer">
            </a>
            <!-- <a href="" class="social-links footer w-inline-block">
              <img src="images/621e7847a5a71e8778ca0c0a_social_icon_spotify.svg" loading="lazy" alt="" class="social-icon footer">
            </a> -->
            <a href="/" class="social-links footer w-inline-block">
              <img src="images/621e7847590fabc077e6aa1d_social_icon_whatsapp.svg" loading="lazy" alt="" class="social-icon footer">
            </a>
          </div>
        </div>
      </div>
      <div class="footer-menu">
        <div class="footer-menu-title">
          <div class="all-caps footer">Lista pamiątek.</div>
        </div>
        <!-- <a href="/shop" class="footer-link"></a> -->
        <div class="w-dyn-list">
          <div role="list" class="w-dyn-items">
            {#each categories.slice(0, 6) as category}
            <div role="listitem" class="w-dyn-item">
              <a href="{category.link}" class="footer-link">{category.emoji} {category.title} </a>
            </div>
            {/each}

          </div>
        </div>
      </div>
      <div class="footer-menu pt-24">
        <!-- <div class="footer-menu-title">
          <div class="all-caps footer"></div>
        </div> -->
            {#each categories.slice(6, 12) as category}
            <div role="listitem" class="w-dyn-item">
              <a href="{category.link}" class="footer-link">{category.emoji} {category.title} </a>
            </div>
            {/each}
      </div>
      <div class="footer-menu">
        <div class="footer-menu-title">
          <div class="all-caps footer">Kontakt</div>
        </div>
        <a href="https://goo.gl/maps/iUH8mDgns7siVcb37" target="_blank" class="footer-link infos">
          Lorem Ipsum is simply dummy
          <br>Lorem Ipsum is simply dummy
           <br>Lorem Ipsum 14:00 – 19:00
           <br>Lorem Ipsum 10:00 – 16:00
          </a>
      </div>
    </div>
    <div class="footer-copyright desktop">
      <div class="footer-link links">2024© EcoWoo;</div>
      <div class="div-block-5">
        <a href="/" class="footer-link legal">Lorem Ipsum</a>
        <a href="/" class="footer-link legal">Lorem Ipsum</a>
        <a href="/" aria-current="page" class="footer-link legal w--current">Lorem Ipsum</a>
      </div>
      <div class="footer-link rechts">Development by <a href="https://oleg-darkdev.vercel.app/" target="_blank" class="copyright-link">oleg_DarkDev</a> <em class="italic-text">♥︎</em>
      </div>
    </div>
    <div class="footer-copyright mobile">
      <div class="div-block-5">
        <a href="#" class="footer-link legal">Lorem Ipsum</a>
        <a href="#" class="footer-link legal">Lorem Ipsum</a>
        <a href="#" class="footer-link legal">Lorem Ipsum</a>
      </div>
      <div class="copyright-wrapper">
        <div class="footer-link links">2024© EcoWoo;</div>
        <div class="footer-link rechts">Development by <a href="https://oleg-darkdev.vercel.app/" target="_blank" class="copyright-link">oleg_DarkDev</a> <em class="italic-text">♥︎</em>
        </div>
      </div>
    </div>
  </div>
=======
<footer class="section">
	<div class="footer-section container">
		<div
			class="footer-wrap box-footer-wrap cut-right"
		>
			<a href="/" aria-current="page" class="w-inline-block w--current">
				<img
					src="images/logo.svg"
					loading="lazy"
					alt="Logo"
					class="logo h-20 w-full"
				/>
			</a>
		</div>
		<div class="box-footer-wrap small cut-bottom">
			<div class="footer-detail">
				<a href="#">+48 111 111 111</a>
				<a href="#">fundacja@lekkosc.eu</a>
			</div>
			<div class="footer-detail">
				<!-- https://goo.gl/maps/2nu2g5N7orCKpbCFA -->
				<a href="" target="_blank" class="fixed-link-width"
					>SĄCZKI (Rieselfeld), Gdansk, Poland</a
				>
			</div>
		</div>
		<div class="box-footer-wrap smaller">
			<div class="footer-detail social-link grow">
				<a
					href="/"
					class="type-details bold">Instagram</a
				>
			</div>
			<div class="footer-detail social-link">
				<a
					href="/"
					class="type-details bold">Facebook</a
				>
			</div>
			<div class="footer-detail social-link grow">
				<a
					href="/"
					class="type-details bold">LinkedIn</a
				>
			</div>
			<div class="text-block">Follow us</div>
			<div class="mobile-footer-social">
				<a href="/" class="w-inline-block">
					<img src="images/Instagram.svg" loading="lazy" alt="insta" />
				</a>
				<a href="/" class="w-inline-block">
					<img src="images/Facebook.svg" loading="lazy" alt="" />
				</a>
				<a href="/" class="w-inline-block">
					<img src="images/LinkedIn.svg" loading="lazy" alt="linkedin" />
				</a>
			</div>
		</div>
	</div>
>>>>>>> origin/main
</footer>


<style>
<<<<<<< HEAD

</style>
=======
.footer-wrap {
  grid-area: span 2 / span 1 / span 2 / span 1;
}

</style>
>>>>>>> origin/main
