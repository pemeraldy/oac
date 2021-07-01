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

<style lang="scss" scoped>
.lastest-wrapper{
    padding-left: 168px;
    padding-right: 168px;
    padding-top: 110px;
    padding-bottom: 140px;
    overflow-x: hidden;
    
    h1{
        font-weight: 600;
        font-size: 48px;
    }
    p{
        font-weight: 400;
        font-size: 18px;
    }
}
.slides-wrap{
    margin-top:69px;
}
.slide-control{
    position: absolute;
    right: -90px;
    top: 62%;
    cursor: pointer;
}
@media screen and (max-width: 500px) {
    .lastest-wrapper{
        padding-left: 18px;
        padding-right: 18px;
        padding-top: 0;
        margin-top: 30px;
        overflow-x:hidden ;

        h1{
            font-size: 37px;
        }
        p{
            font-size: 16px;
        }
    }
    .slides-wrap{
        overflow-x:scroll
    }
}
</style>