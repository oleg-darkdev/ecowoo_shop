<script>
  import {categories} from '$shared';
</script>

<section class="section no-padding-tb-sides">
  <div class="container no-padding-tb">
    <div id='categories' class="flex-horizontal padding-left">
      <div class="reviews-title-wrapper">
        <div class="all-caps">
          Każdy magnes wykonany jest z naturalnego drewna
        </div>
        <div>
          <h2 class="alternative-title">
           Wybierz kategorię i znajdź idealną pamiątkę <span>🤩</span>
          </h2>
          <p class="paragraph-3">
            która stanie się stylowym elementem Twojego wnętrza lub wartościowym prezentem dla najbliższych!
          </p>
        </div>
      </div>
      <div class="collection-list-wrapper-3 w-dyn-list">
        <div role="list" class="blog-list w-dyn-items">
          {#each categories as category}
          <div role="listitem" class="blog-list-item w-dyn-item">
            <div class="date-wrap">
              <p style="" class="all-caps dayclass  ">
                <!-- {category.tags} -->
                {#each category.tags as tag}
                 <span class='mr-1'>#{tag} </span>
                {/each}
              </p>
              <!-- <div class="all-caps">,</div>
              <div class="all-caps date">6</div>
              <div class="all-caps">.</div>
              <div class="all-caps dateclass">October</div>
              <div class="all-caps">2024</div> -->
            </div>
            <div class="blog-list-image-wrapper">
              <img src="{category.img}" loading="lazy" alt="" sizes="(max-width: 479px) 100vw, (max-width: 767px) 97vw, (max-width: 991px) 48vw, 33vw" class="image-cover">
            </div>
            <div class="blog-list-content-wrapper">
              <h4 class="heading-9">{category.title} {category.emoji}</h4>
              {#each category.desc as desc }
                <p class="paragraph-3">
                  {desc}
                </p>
              {/each}
              <div class="button-wrapper">
                <!-- yellow-background -->
                <!-- wszystkie -->
                <a href="{category.link}" target="_blank" class="button-2 {category.brandColor} w-button lowercase">
                   magnesy {category.title} {category.emoji}
                </a>
              </div>
            </div>
          </div>
          {/each}
        </div>
      </div>
    </div>
  </div>
</section>

<style>
.lovers-bg {
  background-color: #f08db9;
}
.films-bg {
  background-color: #fbf5bc;
}
.animals-bg {
  background-color: #c59e7c;
}
.flowers-bg {
  background-color: #f8c6d4;
}
.nature-bg {
  background-color: #a1ce93;
}
.graffiti-bg {
  background-color: #f39456;
}
.cosmos-bg {
  background-color: #7d6fb0;
}
.tourism-bg {
  background-color: #a6bd85;
}
.cycle-bg {
  background-color: #7bcbe2;
}
.van-bg {
  background-color: #ffd048;
}
.belarus-bg {
  background-color: #ea544c;
}
.history-bg {
  background-color: #9a6349;
}
.acab-bg {
  background-color: #b2b2b2;
}

</style>
