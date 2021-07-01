<template>
  <div class="slide-card flex-shrink-0 p-4">
      <h1 class="slide-heading">
          Antibiotic Awareness
      </h1>
      <p class="slide-text">As Emsa Marmara we held a field activity in order to raise awareness about antibiotic resistance...</p>
      <div class="date-time d-flex ">
          <div class="d-flex align-items-center">
              <img class="" src="~/assets/images/icons/calender.png" alt="">
              <span class="ml-1" >26 August, 2021</span>
          </div>
          <div class=" ml-3 d-flex align-items-center">
              <img class="" src="~/assets/images/icons/clock.png" alt="">
              <span class="ml-1" >10:30 AM</span>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.slide-card{
    border: 0.4px solid rgba(32, 32, 32, 0.2);
    max-width: 450px;
    max-height: 220px;
}
.slide-heading{
    font-family: 'SFProDisplay';
    font-style: normal;
    font-weight: 500;
    font-size: 26px;
    line-height: 32px;
    /* identical to box height */
    letter-spacing: -0.02em;
    /* Black */
    color: #202020;
    opacity: 0.8;
}
@media screen and (max-width: 500px) {
    .slide-card{
        max-width: 290px;
        flex-shrink: 0;
    }
    .slide-card span{
        font-size: 10px;
    }
}
</style>