<template>
  <div class="w-100">
    <form>        
        <div class="form-group required">
            <label for="userpassword">Enter Password*</label>
            <input type="password" class="form-control" id="userpassword">
        </div>
        <div class="form-group required">
            <label for="userpassword">Confirm new password</label>
            <input type="password" class="form-control" id="userpassword">
        </div>
        <div class="my-5">
            <button type="submit" class="btn btn-block btn-primary">Reset Password</button>
        </div>
    </form>
  </div>
</template>

<script>
export default {
    name: 'password-reset-form',
}
</script>

<style>

</style>