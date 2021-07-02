<template>
  <div class="mt-5">
    <div class="container mb-5">
      <div class="row">
        <div class="d-none d-md-block col-md-6 col-12">
          <div>
            <img
              class="card-img rounded-0"
              src="~/assets/images/contact-hero.png"
              alt="contact us"
            />
          </div>
        </div>
        <div class="col-md-6 col-12 form-wrap">
          <h1 class="heading">Get in Touch</h1>
          <p class="intro">
            Have an inquiry or some feedback for us? Fill out the form below to
            contact our team.
          </p>
          <div class="mb-5 mb-md-0">
            <ContactForm />
          </div>
        </div>
      </div>
    </div>
    <AppFooter />
  </div>
</template>

<script>
export default {
  layout: "user"
};
</script>

<style scoped>
.form-wrap {
  padding-left: 73px;
  padding-right: 73px;
}
.heading {
  font-size: 48px;
  font-style: normal;
  font-weight: 600;
  line-height: 57px;
  letter-spacing: -0.02em;
  text-align: left;
}
.intro {
  width: 400px;
  font-weight: 400px;
  font-size: 20px;
}
@media screen and (max-width: 500px) {
  .form-wrap {
    padding-left: 10px;
    padding-right: 10px;
  }
  .intro{
    width: 100%;
  }
}
</style>
