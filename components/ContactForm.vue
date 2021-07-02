<template>
  <form class="form-row">
    <div class="form-group col-md-6">
      <label for="firstname">First name</label>
      <input type="text" class="form-control p-3" placeholder="Enter first name" id="firstname">
    </div>
    <div class="form-group col-md-6">
      <label for="lastname">Last name</label>
      <input type="text" class="form-control p-3" placeholder="Enter last name " id="Lastname">
    </div>
    <div class="form-group col-12">
      <label for="Email">Email address</label>
      <input type="email" class="form-control p-3" placeholder="Enter email address " id="email">
    </div>
    <div class="form-group col-12">
      <label for="message">Message</label>
      <textarea class="form-control" name="" id="" placeholder="Type in your message or feedback here" rows="5"></textarea>
    </div>
    <div class="mt-4 w-100">
        <button type="submit" class="btn submit-btn btn-block btn-primary">Get in touch</button>
    </div>
  </form>
</template>

<script>
export default {

}
</script>

<style scoped>
  .form-control{
    border-radius: 6px !important;
    border: 1.5px solid #2020201e;
  }
  .submit-btn{
    height: 48px;
  }
</style>