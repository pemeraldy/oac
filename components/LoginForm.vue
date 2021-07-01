<template>
  <div class="w-100">
    <form>
        <div class="form-group">
            <label for="username">Username</label>
            <input type="email" class="form-control" id="username" aria-describedby="emailHelp">
            <!-- <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small> -->
        </div>
        <div class="form-group required">
            <label for="userpassword">Password</label>
            <input type="password" class="form-control" id="userpassword">
        </div>
        <div class="mt-4">
            <button type="submit" class="btn btn-block btn-primary">Login</button>
        </div>

        <p class="text-center my-4">
            <nuxt-link class="text-muted" to="/">Forgot Password?</nuxt-link>
        </p>

        <div class="mt-4">
            <button type="submit" class="btn btn-block btn-primary">Reset password</button>
        </div>
    </form>
  </div>
</template>

<script>
export default {
    name: 'login-form',
}
</script>

<style>

</style>