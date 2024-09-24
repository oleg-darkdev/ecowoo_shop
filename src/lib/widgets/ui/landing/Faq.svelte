<script>
  import {faqData} from '$shared'
</script>

<div class="section-divider"></div>

<a name="faq"></a>

<section class="section no-padding-tb">
  {#each faqData  as faq}
  <div class="container no-padding-tb">
    <div class="faq-category">
      <div class="faq-category-title">
        <h2>{faq.titleGroup}</h2>
      </div>
      <div class="faq-content-wrapper">

        {#each faq.data as data}
        <div class="faq-content" on:click={()=> data.show = !data.show}>
          <div class="faq-title flex-row flex " >
            <h3 class="faq-header mr-2" >{data.q}</h3>
            <h2 class="faq-header">{data.show ? '👆' : '👇'}</h2>
          </div>
          <!--  yellow-background -->
          {#if data.show}
            {#each data.a as answer}
              <p>
                {answer}
              </p>
            {/each}
          {/if}
        </div>
        {/each}


      </div>
    </div>
  </div>
  <div class="container full-width"></div>
  <div class="section-divider no-display-mobile"></div>
{/each}



</section>


<style>
.faq-content:last-child {
  border-bottom-style: none;
}

@media screen and (max-width: 479px) {
  .faq-content:last-child {
    border-bottom-style: solid;
    border-bottom-color: #23231a;
  }
}
</style>
