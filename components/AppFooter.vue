<template>
  <div class="app-footer bg-primary">
      <div class="container">
          <h1 class="text-center footer-header text-white">Join our community & stay updated.</h1>
            <p class="text-center footer-para text-white">No Spam. Only sweet content and updates of our products.</p>
            <div class="d-flex justify-content-center py-5">
                <NewsLetterForm />
            </div>            
            <hr class="h-rule">      
      </div>
      <div class="d-flex justify-content-center">
        <FooterNav />
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.app-footer{
    padding-top: 90px;
    /* padding-bottom: 90px; */
}
hr.h-rule{
    border-top: 0.4px solid #fff;
    opacity: 0.2;
}
@media screen and (max-width: 500px) {
 .footer-header{
     font-size: 26px;
 }   
}
</style>