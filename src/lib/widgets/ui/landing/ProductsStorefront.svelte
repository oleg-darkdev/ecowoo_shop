<script>
  const products = [
    {
      title: 'Bike polo girl.',
      desc: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.',
      price: '12 zł.',
      category: '🚲',
      img: '/images/magnets/cycle/woman.jpg',
      tags: ['kolarstwo', 'citybike', 'bikepolo', 'MTB', 'touring', 'grawel', 'triathlon', 'fatbike', 'BMX']
    },
    {
      title: 'Bike polo man.',
      desc: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.',
      price: '12 zł.',
      img: '/images/magnets/cycle/man.jpg',
      category: '🚲',
      tags: ['kolarstwo', 'citybike', 'bikepolo', 'MTB', 'touring', 'grawel', 'triathlon', 'fatbike', 'BMX']
    },
    {
      title: 'Bike polo man.',
      desc: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.',
      price: '12 zł.',
      img: '/images/magnets/cycle/man.jpg',
      category: '🚲',
      tags: ['kolarstwo', 'citybike', 'bikepolo', 'MTB', 'touring', 'grawel', 'triathlon', 'fatbike', 'BMX']
    },
    {
      title: 'Bike polo man.',
      desc: 'Lorem Ipsum is simply dummy text of the printing and typesetting industry.',
      price: '12 zł.',
      img: '/images/magnets/cycle/man.jpg',
      category: '🚲',
      tags: ['kolarstwo', 'citybike', 'bikepolo', 'MTB', 'touring', 'grawel', 'triathlon', 'fatbike', 'BMX']
    },



  ]
</script>

<section class="section no-padding-tb-4">
  <div class="container">
    <div class="flex-vertical">
      <div class="title-wrapper-section centered">
        <div class="all-caps">Lorem Ipsum is simply dummy.</div>
        <div>
          <h2 class="alternative-title">
            Lorem Ipsum is simply dummy text of the printing and typesetting industry.
          </h2>
          <p class="paragraph-2">
            Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
          </p>
        </div>
      </div>

      <div class="categories-content-wrapper">
        <div class="product-collection w-dyn-list">
          <div role="list" class="product-grid w-dyn-items">
            {#each products as {title, desc, category, price, img, tags}}
            <div role="listitem" class="product-item w-dyn-item">
              <a href="/" class="product-link-block w-inline-block">
                <div class="grid-product-image-wrapper">
                  <!-- <img alt="" loading="lazy"  src="{img}" class="grid-image-product w-condition-invisible"> -->
                  <img src="{img}" loading="lazy" alt="" class="w-full h-full grid-image-product">
                  <img src="images/placeholder.60f9b1840c.svg" loading="eager" alt="" class="grid-hover-image-product">
                  <div class="eigenschaft-container w-condition-invisible">
                    <div class="eigenschaft-bubble w-condition-invisible">
                      <div class="eigenschaft-label">NO <br>SU </div>
                    </div>
                    <div class="eigenschaft-bubble w-condition-invisible">
                      <div class="eigenschaft-label">BIO <br>
                      </div>
                    </div>
                    <div class="eigenschaft-bubble w-condition-invisible">
                      <div class="eigenschaft-label">BD</div>
                    </div>
                    <div class="eigenschaft-bubble w-condition-invisible">
                      <div class="eigenschaft-label">NAT</div>
                    </div>
                  </div>
                </div>

                <div class="grid-product-content-wrapper">

                  <div class="grid-product-content">
                    <!-- background-color:hsla(63, 100.00%, 84.60%, 1.00) -->
                    <!-- weinfarbe-bubble -->
                    <div style="" class="weinfarbe-bubble text-2xl">{category}</div>
                    <div class="all-caps vinyl">
                      {#each tags as tag}
                        #{tag}
                      {/each}</div>
                    <!-- <div class="all-caps vinyl"> Clairo</div> -->
                    <!-- <div class="all-caps vinyl w-condition-invisible">
                      {#each tags as tag}
                        #{tag}
                      {/each}
                    </div> -->
                    <h4 class="product-name">{title}</h4>
                    <div class="price-div">
                      <!-- <p class="product-price ab">ab</p> -->
                      <p   class="product-price">{price}</p>
                    </div>
                    <!-- <div  class="sale-price-wrapper w-condition-invisible">
                      <p   class="new-price">83.00�&nbsp;CHF</p>
                      <p class="old-price w-dyn-bind-empty"></p>
                    </div> -->
                  </div>
                  <div class="product-details-button">
                    <div>Product Details</div>
                  </div>
                </div>
              </a>
            </div>
          {/each}
            </div>
          </div>
        </div>
      </div>

      <a href="#categories" class="button-2 yellow-background large-padding w-button">
        Pełna lista pamiątek 👇
      </a>
    </div>
</section>


<style>

</style>
