<script>
	// import {  } from '$lib/shared';
	import { Footer, Faq, PreFaq, Hero, Header, Stats, Banner, AboutMe, Contact, Testimonials, BannerDivider, Avia, Categories, ProductsStorefront } from '$lib/widgets';
  // import {  } from '$lib/entities'
</script>


<svelte:head>
  <title>EcoWoo shop</title>
</svelte:head>


<div class="page-wrapper">

  <!-- <Header /> -->

      <div class="section-divider padding"></div>
      <Banner />

      <Hero />

      <Stats />

      <div class="section-divider"></div>
      <ProductsStorefront />


      <div class="section-divider"></div>

      <AboutMe />

      <div class="section-divider"></div>
      <Categories />

      <div class="section-divider"></div>
      <Avia />

      <div class="section-divider"></div>
      <BannerDivider />

      <!-- <div class="section-divider"></div>
      <Testimonials /> -->

      <div class="section-divider"></div>
      <Contact />

      <div class="section-divider"></div>
      <PreFaq />

      <Faq />
</div>

<Footer />



<style>

</style>
