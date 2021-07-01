<template>
  <div class="w-100">
    <form>        
        <div class="form-group required">
            <label for="userpassword">Email address*</label>
            <input type="email" class="form-control" id="userpassword">
        </div>
        <div class="my-5">
            <button type="submit" class="btn btn-block btn-primary">Reset Password</button>
        </div>
    </form>
  </div>
</template>

<script>
export default {
    name: 'Reset-password-form',
}
</script>

<style>

</style>