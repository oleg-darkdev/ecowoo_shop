<script>
	// import {  } from '$lib/shared';
	import { Footer, Faq, PreFaq, Hero, Header, Stats, Banner, AboutMe, Contact, Testimonials, BannerDivider, Avia, Categories, ProductsStorefront } from '$lib/widgets';
  // import {  } from '$lib/entities'
</script>


<svelte:head>
  <title>EcoWoo shop</title>
</svelte:head>


<div class="page-wrapper">

  <Header />

      <div class="section-divider padding"></div>
      <Banner />

      <Hero />

      <Stats />

      <!-- <div class="section padding-tb4">
        <div class="new-vin-home">
          <div class="column-25">
            <div class="title-wrapper-left-column">
              <div class="all-caps">Jetzt im Shop</div>
              <h2 class="product-header">Neue Weine</h2>
              <div class="alle-category-home left w-dyn-list">
                <div role="list" class="alle-category-home w-dyn-items">
                  <div role="listitem" class="home-button-alle right w-dyn-item">
                    <a href="/category/alle-weine" class="button dark home w-button">Alle Weine</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="collection-list-wrapper home w-dyn-list">
            <div role="list" class="product-grid home w-dyn-items">
              <div role="listitem" class="product-item w-dyn-item">
                <a href="/product/riesling-vendange-laurencienne" class="product-link-block w-inline-block">
                  <div data-w-id="5932040f-6133-5527-2b49-703785a88820" class="grid-product-image-wrapper">
                    <div class="play-button small-play">
                      <div class="play-button-text smaller">Drink Me</div>
                    </div>
                    <img alt="Frisch, fruchtig, unbekümmert und auch elegant, so kommt unser Rheinriesling aus dem Wallis daher. Hier eine sehr seltene Traubensorte, sorgt er für Abwechslung, wenn die Lust nach Schweizer Weine steht." loading="eager" data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_main_image_4dr%22%2C%22to%22%3A%22src%22%7D%5D" src="images/6363eff30ac220b67e070ae5_c659233a-2862-4749-a471-f3a8edbe3bd6.jpeg" sizes="(max-width: 479px) 85vw, (max-width: 767px) 44vw, (max-width: 991px) 28vw, 21vw" srcset="images/6363eff30ac220b67e070ae5_c659233a-2862-4749-a471-f3a8edbe3bd6-p-500.jpeg 500w, images/6363eff30ac220b67e070ae5_c659233a-2862-4749-a471-f3a8edbe3bd6.jpeg 600w" class="grid-image-product">
                    <img src="images/placeholder.60f9b1840c.svg" loading="eager" alt="" class="grid-hover-image-product">
                  </div>
                  <div class="grid-product-content-wrapper">
                    <div class="grid-product-content">
                      <div style="background-color:hsla(58, 100.00%, 88.24%, 1.00)" class="weinfarbe-bubble"></div>
                      <div class="all-caps vinyl">Defayes &amp; Crettenand</div>
                      <h4 class="product-name">Riesling Vendange Laurencienne</h4>
                      <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22no%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="product-price">25.00�&nbsp;CHF</p>
                      <div data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22yes%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="sale-price-wrapper w-condition-invisible">
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="new-price">25.00�&nbsp;CHF</p>
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_compare_at_price_7dr10dr%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="old-price w-dyn-bind-empty"></p>
                      </div>
                    </div>
                    <div class="product-details-button">
                      <div>Product Details</div>
                    </div>
                  </div>
                </a>
              </div>
              <div role="listitem" class="product-item w-dyn-item">
                <a href="/product/onra-blanco" class="product-link-block w-inline-block">
                  <div data-w-id="5932040f-6133-5527-2b49-703785a88820" class="grid-product-image-wrapper">
                    <div class="play-button small-play">
                      <div class="play-button-text smaller">Drink Me</div>
                    </div>
                    <img alt="Eine Mischung aus weisser Garnacha und etwas Sauvignon Blanc, besitzt der Ónra Blanco viel blumige Kraft und agrumischen Saft. Wir mögen seine Frische und seine mineralische Note, den bemerkenswerten aromatischen Reichtum und seinen langen Abgang." loading="eager" data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_main_image_4dr%22%2C%22to%22%3A%22src%22%7D%5D" src="images/6672eadbb8abf654cfd27fd1_lagravera_onra_blanco_vin_vinyl_setpember.jpeg.jpeg" sizes="(max-width: 479px) 85vw, (max-width: 767px) 44vw, (max-width: 991px) 28vw, 21vw" srcset="images/6672eadbb8abf654cfd27fd1_lagravera_onra_blanco_vin_vinyl_setpember.jpeg-p-500.jpeg 500w, images/6672eadbb8abf654cfd27fd1_lagravera_onra_blanco_vin_vinyl_setpember.jpeg-p-800.jpeg 800w, images/6672eadbb8abf654cfd27fd1_lagravera_onra_blanco_vin_vinyl_setpember.jpeg.jpeg 1000w" class="grid-image-product">
                    <img src="images/placeholder.60f9b1840c.svg" loading="eager" alt="" class="grid-hover-image-product">
                  </div>
                  <div class="grid-product-content-wrapper">
                    <div class="grid-product-content">
                      <div style="background-color:hsla(52, 100.00%, 73.53%, 1.00)" class="weinfarbe-bubble"></div>
                      <div class="all-caps vinyl">Lagravera</div>
                      <h4 class="product-name">Ónra Blanco</h4>
                      <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22no%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="product-price">18.00�&nbsp;CHF</p>
                      <div data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22yes%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="sale-price-wrapper w-condition-invisible">
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="new-price">18.00�&nbsp;CHF</p>
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_compare_at_price_7dr10dr%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="old-price w-dyn-bind-empty"></p>
                      </div>
                    </div>
                    <div class="product-details-button">
                      <div>Product Details</div>
                    </div>
                  </div>
                </a>
              </div>
              <div role="listitem" class="product-item w-dyn-item">
                <a href="/product/onra-claret" class="product-link-block w-inline-block">
                  <div data-w-id="5932040f-6133-5527-2b49-703785a88820" class="grid-product-image-wrapper">
                    <div class="play-button small-play">
                      <div class="play-button-text smaller">Drink Me</div>
                    </div>
                    <img alt="Süffig und kein Ende in Sicht, mit recht wenig Alkohol und frech-fruchtigen Aromen: Das ist der Ónra Claret. Lagravera machen ihn aus 85 % früh geernteten, gepressten Monastrell-Trauben und 15 % ganzen Trauben von alten Rebsorten. An der Grenze zwischen Rot und Rosé macht er grossen Spass. Gleichzeitig besitzt er Klasse, eine Textur zum verlieben und eine sommerliche Frische. Popstar, baby." loading="eager" data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_main_image_4dr%22%2C%22to%22%3A%22src%22%7D%5D" src="images/6673c136368df341f92a1515_lagravera_onra_clarete_vin_vinyl_setpember.jpeg" sizes="(max-width: 479px) 85vw, (max-width: 767px) 44vw, (max-width: 991px) 28vw, 21vw" srcset="images/6673c136368df341f92a1515_lagravera_onra_clarete_vin_vinyl_setpember-p-500.jpeg 500w, images/6673c136368df341f92a1515_lagravera_onra_clarete_vin_vinyl_setpember-p-800.jpeg 800w, images/6673c136368df341f92a1515_lagravera_onra_clarete_vin_vinyl_setpember.jpeg 1000w" class="grid-image-product">
                    <img src="images/placeholder.60f9b1840c.svg" loading="eager" alt="" class="grid-hover-image-product">
                  </div>
                  <div class="grid-product-content-wrapper">
                    <div class="grid-product-content">
                      <div style="background-color:hsla(359, 88.50%, 64.22%, 0.74)" class="weinfarbe-bubble"></div>
                      <div class="all-caps vinyl">Lagravera</div>
                      <h4 class="product-name">Ónra Claret</h4>
                      <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22no%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="product-price">22.00�&nbsp;CHF</p>
                      <div data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22yes%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="sale-price-wrapper w-condition-invisible">
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="new-price">22.00�&nbsp;CHF</p>
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_compare_at_price_7dr10dr%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="old-price w-dyn-bind-empty"></p>
                      </div>
                    </div>
                    <div class="product-details-button">
                      <div>Product Details</div>
                    </div>
                  </div>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div> -->

      <!-- <div class="section padding-tb4">
        <div class="new-vinyl-home">
          <div class="collection-list-wrapper home w-dyn-list">
            <div role="list" class="product-grid home w-dyn-items">
              <div role="listitem" class="product-item w-dyn-item">
                <a href="/product/blood-bitch" class="product-link-block w-inline-block">
                  <div data-w-id="e184373e-3cb5-9fc5-c0cb-284a5b068b0f" class="grid-product-image-wrapper">
                    <div class="play-button small-play">
                      <div class="play-button-text smaller">Play Me</div>
                    </div>
                    <img alt="" loading="lazy" data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_main_image_4dr%22%2C%22to%22%3A%22src%22%7D%5D" src="images/65fdc1c2ce00e2e5167a09c5_jenny_hval_blood_bitch_setpember_vin_vinyl.jpg" sizes="(max-width: 479px) 85vw, (max-width: 767px) 44vw, (max-width: 991px) 28vw, 21vw" srcset="images/65fdc1c2ce00e2e5167a09c5_jenny_hval_blood_bitch_setpember_vin_vinyl-p-500.jpg 500w, images/65fdc1c2ce00e2e5167a09c5_jenny_hval_blood_bitch_setpember_vin_vinyl-p-800.jpg 800w, images/65fdc1c2ce00e2e5167a09c5_jenny_hval_blood_bitch_setpember_vin_vinyl.jpg 1000w" class="grid-image-product">
                    <img src="images/placeholder.60f9b1840c.svg" loading="eager" alt="" class="grid-hover-image-product">
                  </div>
                  <div class="grid-product-content-wrapper">
                    <div class="grid-product-content">
                      <div class="all-caps vinyl">Jenni Hval </div>
                      <h4 class="product-name">Blood Bitch</h4>
                      <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22no%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="product-price">37.00�&nbsp;CHF</p>
                      <div data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22yes%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="sale-price-wrapper w-condition-invisible">
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_compare_at_price_7dr10dr%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="old-price w-dyn-bind-empty"></p>
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="new-price">37.00�&nbsp;CHF</p>
                      </div>
                    </div>
                    <div class="product-details-button">
                      <div>Product Details</div>
                    </div>
                  </div>
                </a>
              </div>
              <div role="listitem" class="product-item w-dyn-item">
                <a href="/product/i-am-not-there-anymore" class="product-link-block w-inline-block">
                  <div data-w-id="e184373e-3cb5-9fc5-c0cb-284a5b068b0f" class="grid-product-image-wrapper">
                    <div class="play-button small-play">
                      <div class="play-button-text smaller">Play Me</div>
                    </div>
                    <img alt="" loading="lazy" data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_main_image_4dr%22%2C%22to%22%3A%22src%22%7D%5D" src="images/65f2d0c01a6e04712a0a365e_clientele_am_not_there_anymore_vin_vinyl_setpember.jpeg" sizes="(max-width: 479px) 85vw, (max-width: 767px) 44vw, (max-width: 991px) 28vw, 21vw" srcset="images/65f2d0c01a6e04712a0a365e_clientele_am_not_there_anymore_vin_vinyl_setpember-p-500.jpeg 500w, images/65f2d0c01a6e04712a0a365e_clientele_am_not_there_anymore_vin_vinyl_setpember-p-800.jpeg 800w, images/65f2d0c01a6e04712a0a365e_clientele_am_not_there_anymore_vin_vinyl_setpember.jpeg 1000w" class="grid-image-product">
                    <img src="images/placeholder.60f9b1840c.svg" loading="eager" alt="" class="grid-hover-image-product">
                  </div>
                  <div class="grid-product-content-wrapper">
                    <div class="grid-product-content">
                      <div class="all-caps vinyl">The Clientele</div>
                      <h4 class="product-name">I am not There Anymore</h4>
                      <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22no%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="product-price">49.00�&nbsp;CHF</p>
                      <div data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22yes%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="sale-price-wrapper w-condition-invisible">
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_compare_at_price_7dr10dr%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="old-price w-dyn-bind-empty"></p>
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="new-price">49.00�&nbsp;CHF</p>
                      </div>
                    </div>
                    <div class="product-details-button">
                      <div>Product Details</div>
                    </div>
                  </div>
                </a>
              </div>
              <div role="listitem" class="product-item w-dyn-item">
                <a href="/product/selwi" class="product-link-block w-inline-block">
                  <div data-w-id="e184373e-3cb5-9fc5-c0cb-284a5b068b0f" class="grid-product-image-wrapper">
                    <div class="play-button small-play">
                      <div class="play-button-text smaller">Play Me</div>
                    </div>
                    <img alt="" loading="lazy" data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_main_image_4dr%22%2C%22to%22%3A%22src%22%7D%5D" src="images/65f2ce08995712bcf8d12311_junke_eko_selwi_vin_vinyl_setpember.jpeg" sizes="(max-width: 479px) 85vw, (max-width: 767px) 44vw, (max-width: 991px) 28vw, 21vw" srcset="images/65f2ce08995712bcf8d12311_junke_eko_selwi_vin_vinyl_setpember-p-500.jpeg 500w, images/65f2ce08995712bcf8d12311_junke_eko_selwi_vin_vinyl_setpember-p-800.jpeg 800w, images/65f2ce08995712bcf8d12311_junke_eko_selwi_vin_vinyl_setpember.jpeg 1000w" class="grid-image-product">
                    <img src="images/placeholder.60f9b1840c.svg" loading="eager" alt="" class="grid-hover-image-product">
                  </div>
                  <div class="grid-product-content-wrapper">
                    <div class="grid-product-content">
                      <div class="all-caps vinyl">Junge Eko</div>
                      <h4 class="product-name">Selwi</h4>
                      <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22no%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="product-price">29.00�&nbsp;CHF</p>
                      <div data-wf-sku-conditions="%7B%22condition%22%3A%7B%22fields%22%3A%7B%22default-sku%3Acompare-at-price%22%3A%7B%22exists%22%3A%22yes%22%2C%22type%22%3A%22CommercePrice%22%7D%7D%7D%2C%22timezone%22%3A%22Europe%2FZurich%22%7D" class="sale-price-wrapper w-condition-invisible">
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_compare_at_price_7dr10dr%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="old-price w-dyn-bind-empty"></p>
                        <p data-wf-sku-bindings="%5B%7B%22from%22%3A%22f_price_%22%2C%22to%22%3A%22innerHTML%22%7D%5D" class="new-price">29.00�&nbsp;CHF</p>
                      </div>
                    </div>
                    <div class="product-details-button">
                      <div>Product Details</div>
                    </div>
                  </div>
                </a>
              </div>
            </div>
          </div>
          <div class="column-25">
            <div class="title-wrapper-left-column">
              <div class="all-caps rechts">Jetzt im Shop</div>
              <h2 class="product-header rechts">Neues Vinyl</h2>
              <div class="alle-category-home left w-dyn-list">
                <div role="list" class="alle-category-home w-dyn-items">
                  <div role="listitem" class="home-button-alle left w-dyn-item">
                    <a href="/category/alle-vinyl-platten" class="button dark home w-button">Alle Platten</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div> -->



      <div class="section-divider"></div>
      <ProductsStorefront />


      <div class="section-divider"></div>

      <AboutMe />

      <div class="section-divider"></div>
      <Categories />

      <div class="section-divider"></div>
      <Avia />


      <div class="section-divider"></div>
      <!-- <section class="section no-padding-tb-6">
        <div class="container">
          <div class="flex-vertical">
            <div class="title-wrapper-section centered">
              <div class="all-caps">Setpember Wein Tipps</div>
              <div>
                <h2 class="alternative-title">Wild, female power, gesellig oder luxuriös? Welcher Wein darf es sein?</h2>
                <p class="paragraph-2">Hier geben wir dir ein paar Ideen mit auf den Weg. Was zu dir passt, entscheidest aber immer noch du. </p>
              </div>
            </div>
            <div class="categories-content-wrapper">
              <div class="w-dyn-list">
                <div role="list" class="categories-grid w-dyn-items">
                  <div role="listitem" class="categories-item no-border-bottom w-dyn-item">
                    <div class="category-content-wrapper">
                      <div class="image-wrapper">
                        <img src="images/63582054c83bda34148c0866_setpember-wein-wildones.jpeg" loading="lazy" alt="" sizes="(max-width: 479px) 87vw, (max-width: 767px) 43vw, (max-width: 991px) 44vw, 21vw" srcset="images/63582054c83bda34148c0866_setpember-wein-wildones-p-500.jpeg 500w, images/63582054c83bda34148c0866_setpember-wein-wildones-p-800.jpeg 800w, images/63582054c83bda34148c0866_setpember-wein-wildones-p-1080.jpeg 1080w, images/63582054c83bda34148c0866_setpember-wein-wildones.jpeg 1125w">
                      </div>
                      <div class="category-button-wrapper"></div>
                      <a href="/category/wild-ones-weine" class="button-2 unicorn-bg w-button">Wild Ones</a>
                    </div>
                  </div>
                  <div role="listitem" class="categories-item no-border-bottom w-dyn-item">
                    <div class="category-content-wrapper">
                      <div class="image-wrapper">
                        <img src="images/6358200ca8f93f9668314288_setpember-wein-femalepower.jpeg" loading="lazy" alt="" sizes="(max-width: 479px) 87vw, (max-width: 767px) 43vw, (max-width: 991px) 44vw, 21vw" srcset="images/6358200ca8f93f9668314288_setpember-wein-femalepower-p-500.jpeg 500w, images/6358200ca8f93f9668314288_setpember-wein-femalepower-p-800.jpeg 800w, images/6358200ca8f93f9668314288_setpember-wein-femalepower-p-1080.jpeg 1080w, images/6358200ca8f93f9668314288_setpember-wein-femalepower.jpeg 1125w">
                      </div>
                      <div class="category-button-wrapper"></div>
                      <a href="/category/female-power-wein" class="button-2 unicorn-bg w-button">Female Power</a>
                    </div>
                  </div>
                  <div role="listitem" class="categories-item no-border-bottom w-dyn-item">
                    <div class="category-content-wrapper">
                      <div class="image-wrapper">
                        <img src="images/6358202812cb5b8f4ba599d9_setpember-wein-darlings.jpeg" loading="lazy" alt="" sizes="(max-width: 479px) 87vw, (max-width: 767px) 43vw, (max-width: 991px) 44vw, 21vw" srcset="images/6358202812cb5b8f4ba599d9_setpember-wein-darlings-p-500.jpeg 500w, images/6358202812cb5b8f4ba599d9_setpember-wein-darlings-p-800.jpeg 800w, images/6358202812cb5b8f4ba599d9_setpember-wein-darlings-p-1080.jpeg 1080w, images/6358202812cb5b8f4ba599d9_setpember-wein-darlings.jpeg 1125w">
                      </div>
                      <div class="category-button-wrapper"></div>
                      <a href="/category/everybodys-darlings" class="button-2 unicorn-bg w-button">Everybody’s Darlings</a>
                    </div>
                  </div>
                  <div role="listitem" class="categories-item no-border-bottom w-dyn-item">
                    <div class="category-content-wrapper">
                      <div class="image-wrapper">
                        <img src="images/6358203cc83bdad6538c0609_setpember-wein-yolo.jpeg" loading="lazy" alt="" sizes="(max-width: 479px) 87vw, (max-width: 767px) 43vw, (max-width: 991px) 44vw, 21vw" srcset="images/6358203cc83bdad6538c0609_setpember-wein-yolo-p-500.jpeg 500w, images/6358203cc83bdad6538c0609_setpember-wein-yolo-p-800.jpeg 800w, images/6358203cc83bdad6538c0609_setpember-wein-yolo-p-1080.jpeg 1080w, images/6358203cc83bdad6538c0609_setpember-wein-yolo.jpeg 1125w">
                      </div>
                      <div class="category-button-wrapper"></div>
                      <a href="/category/yolo-weine" class="button-2 unicorn-bg w-button">YOLO</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section> -->



      <div class="section-divider"></div>
      <BannerDivider />

      <div class="section-divider"></div>
      <Testimonials />

      <div class="section-divider"></div>
      <Contact />



      <!-- <div class="section padding-tb4">
        <div class="container newsletter">
          <div class="title-wrapper centered">
            <div class="all-caps">Abonnier unseren Newsletter</div>
            <h2 class="heading-23">Beginne noch heute deine Setpember Reise. Abonnier jetzt unseren Newsletter.</h2>
          </div>
          <div class="form-block newsletter-section w-form">
            <form id="wf-form-Footer-Newsletter-Form" name="wf-form-Footer-Newsletter-Form" data-name="Footer Newsletter Form" action="https://setpember.us10.list-manage.com/subscribe/post?u=857231acd9b2572aad17d8078&amp;id=f405cfdbe5&amp;f_id=008429e2f0" method="post" class="underlined-form newsletter-section" data-wf-page-id="637103ed71bc7382a7b4baac" data-wf-element-id="5fbd88fd-c56d-6513-2724-ee34110d01c2">
              <div class="div-block-9">
                <input class="newsletter-input w-input" maxlength="256" name="First-Name" data-name="First Name" placeholder="Vorname" type="text" id="First-Name">
                <input class="newsletter-input w-input" maxlength="256" name="Last-Name" data-name="Last Name" placeholder="Nachname" type="text" id="Last-Name">
                <input class="newsletter-input w-input" maxlength="256" name="Email" data-name="Email" placeholder="E-Mail Adresse" type="email" id="Email" required="">
              </div>
              <input type="submit" data-wait="paar Sekunden..." class="button-2 unicorn-bg newsletter w-button" value="Newsletter abonnieren">
            </form>
            <div class="form-success w-form-done">
              <div>Danke! Deine Anmeldung ist eingegangen!</div>
            </div>
            <div class="form-error w-form-fail">
              <div>Oops! Da scheint etwas nicht geklappt zu haben.</div>
            </div>
          </div>
        </div>
      </div> -->

  <PreFaq />

  <Faq />


  <!-- <div class="section-divider"></div> -->
  <!-- <div class="section padding-tb4">
    <div class="container newsletter">
      <div class="title-wrapper centered">
        <div class="all-caps">Abonnier unseren Newsletter</div>
        <h2 class="heading-23">Beginne noch heute deine Setpember Reise. Abonnier jetzt unseren Newsletter.</h2>
      </div>
      <div class="form-block newsletter-section w-form">
        <form id="wf-form-Footer-Newsletter-Form" name="wf-form-Footer-Newsletter-Form" data-name="Footer Newsletter Form" action="https://setpember.us10.list-manage.com/subscribe/post?u=857231acd9b2572aad17d8078&amp;id=f405cfdbe5&amp;f_id=008429e2f0" method="post" class="underlined-form newsletter-section" data-wf-page-id="637103ed71bc7300c0b4bb41" data-wf-element-id="5fbd88fd-c56d-6513-2724-ee34110d01c2">
          <div class="div-block-9">
            <input class="newsletter-input w-input" maxlength="256" name="First-Name" data-name="First Name" placeholder="Vorname" type="text" id="First-Name">
            <input class="newsletter-input w-input" maxlength="256" name="Last-Name" data-name="Last Name" placeholder="Nachname" type="text" id="Last-Name">
            <input class="newsletter-input w-input" maxlength="256" name="Email" data-name="Email" placeholder="E-Mail Adresse" type="email" id="Email" required="">
          </div>
          <input type="submit" data-wait="paar Sekunden..." class="button-2 unicorn-bg newsletter w-button" value="Newsletter abonnieren">
        </form>
        <div class="form-success w-form-done">
          <div>Danke! Deine Anmeldung ist eingegangen!</div>
        </div>
        <div class="form-error w-form-fail">
          <div>Oops! Da scheint etwas nicht geklappt zu haben.</div>
        </div>
      </div>
    </div>
  </div> -->
</div>

<Footer />



<style>

</style>
