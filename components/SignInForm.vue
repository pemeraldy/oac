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
            <button type="submit" class="btn btn-block btn-primary">
                Login
                <!-- <i class="fa fa-arrow-right"></i> -->
            </button>
        </div>

        <p class="text-center my-4">
            <nuxt-link class="text-muted" to="/auth/reset-password">Forgot Password?</nuxt-link>
        </p>

        <div class="mt-4">
            <button type="submit" class="btn btn-block btn-outline-dark">Sign Up</button>
        </div>
    </form>
  </div>
</template>

<script>
export default {
    name: 'reset-pw-form',
}
</script>

<style>

</style>