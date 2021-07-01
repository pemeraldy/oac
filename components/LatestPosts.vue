<template>
  <section class="lastest-wrapper">
      <div class="row">
          <div class="col-12">
              <div>
                <h1>Latest Events</h1>
                <p>Catch up with all the lastest event published by different people across the country.</p>
              </div>
              <div class="d-flex slides-wrap">
                  <SlideCard class="mr-2 mr-md-4"/>
                  <SlideCard class="mr-2 mr-md-4" />
                  <SlideCard class="mr-2 mr-md-4" />
              </div>
              <div class="slide-control">
                  <img src="~/assets/images/icons/next-btn.png" alt="next button">
              </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
.lastest-wrapper{
    padding-left: 168px;
    padding-right: 168px;
    padding-top: 110px;
    padding-bottom: 140px;
}
.slide-control{
    position: absolute;
    right: -90px;
    top: 50%;
    cursor: pointer;
}
@media screen and (max-width: 500px) {
    .lastest-wrapper{
        padding-left: 18px;
        padding-right: 18px;
        padding-top: 0;
        margin-top: 30px;
        overflow-x:hidden ;
    }
    .slides-wrap{
        overflow-x:scroll
    }
}
</style>