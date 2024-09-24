<script>
  import {categories, contacts, footerLinks} from '$shared';
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
            {#each contacts as {title, link, icon}}
            <a href="{link}" class="social-links footer w-inline-block">
              <img src="{icon}" loading="lazy" alt="{title} icon" class="social-icon footer">
            </a>
            {/each}
          </div>
        </div>
      </div>
      <div class="footer-menu">
        <div class="footer-menu-title">
          <div class="all-caps footer">Kategorie pamiątek.</div>
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
      <div class="footer-menu">
        <div class="footer-menu-title">
          <div class="all-caps footer">Kategorie pamiątek.</div>
        </div>
            {#each categories.slice(6, 12) as category}
            <div role="listitem" class="w-dyn-item">
              <a href="{category.link}" class="footer-link">{category.emoji} {category.title} </a>
            </div>
            {/each}
      </div>
      <div class="footer-menu">
        <div class="footer-menu-title">
          <div class="all-caps footer">Kontakt ze mną.</div>
        </div>
        {#each contacts as {title, link}}
          <a href="{link}" target="_blank" class="footer-link">
            {title}
          </a>
        {/each}
      </div>
    </div>
    <div class="footer-copyright desktop">
      <div class="footer-link links">2024© EcoWoo;</div>
      <div class="div-block-5">
        {#each footerLinks as {title, link}}
        <a href="{link}" class="footer-link legal">{title}</a>
        {/each}
      </div>
      <div class="footer-link rechts">Development by <a href="https://oleg-darkdev.vercel.app/" target="_blank" class="copyright-link">oleg_DarkDev</a> <em class="italic-text">♥︎</em>
      </div>
    </div>
    <div class="footer-copyright mobile">
      <div class="div-block-5">
        {#each footerLinks as {title, link}}
        <a href="{link}" class="footer-link legal">{title}</a>
        {/each}
      </div>
      <div class="copyright-wrapper">
        <div class="footer-link links">2024© EcoWoo;</div>
        <div class="footer-link rechts">Development by <a href="https://oleg-darkdev.vercel.app/" target="_blank" class="copyright-link">oleg_DarkDev</a> <em class="italic-text">♥︎</em>
        </div>
      </div>
    </div>
  </div>
</footer>


<style>

</style>
