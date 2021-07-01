<template>
  <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="d-flex justify-content-center">
              <div class="w-100 detail-section d-flex flex-column align-items-center">
            <h1 class="text-center details-heading">Meet new people, share ideas & learn something new! </h1>
            <p class="text-center details-para mt-md-3">AMR/AMU Community of Practice (CoP) is available to the general public and health workers already in the programme.</p>
          </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
    .detail-section {
        padding-top: 80px;
        max-width: 619px;
    }
    .details-heading{
      font-weight: 600;
      font-size: 48px;
      letter-spacing: -2px;
    }
    .details-para{
      max-width: 543px;
      font-size: 18px;
      font-style: normal;
      font-weight: 400;
      line-height: 28px;
      letter-spacing: 0em;
      text-align: center;
    }

    /* Responsive */
    @media screen and (max-width: 500px) {
      .details-heading{
      font-size: 30px;
    }
    .details-para{
      font-size: 16px;
    }
    }
</style>