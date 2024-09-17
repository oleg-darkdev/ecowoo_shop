<script>
  const features = [
    {
      icon: 'images/for-all.svg',
      title: 'dla wszystkich grup wiekowych',
    },
    {
      icon: 'images/design.svg',
      title: 'Zapadający w pamięć motyw',
    },
    {
      icon: 'images/handmade.svg',
      title: 'Wykonane własnymi rękami',
    },
    {
      icon: 'images/eko.svg',
      title: 'Ekologiczne i drewniane',
    },
  ]
</script>

<section class="section no-padding">
  <div class="container">
    <div class="title-wrapper centered padding-bottom-2"></div>
    <div class="w-layout-grid lg:grid-cols-4 md:grid-cols-2 grid-cols-1">
      {#each features as {title, icon}}
      <div class="icon-link w-inline-block">

        <div class="feature-wrapper first no-margin-bottom">
          <img src="{icon}" loading="lazy" alt="{title} img" width="150" class="feature-icon">
          <h4 class="all-caps">{title}</h4>
        </div>

      </div>
      {/each}


    </div>
  </div>
</section>

<style>

</style>
