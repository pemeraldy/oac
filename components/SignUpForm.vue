<template>
  <div class="w-100">
    <form>
        <div class="form-group required">
            <label for="useremeail">Email addresss*</label>
            <input type="text" class="form-control p-4" placeholder="example@gmail.com" id="useremeail">
        </div>
        <div class="form-group required">
            <label for="userpassword">Password*</label>
            <input type="password" class="form-control p-4" placeholder="example@gmail.com" id="userpassword">
        </div>
        <div class="form-group required">
            <label for="userpassword">Confirm password*</label>
            <input type="password" class="form-control p-4" placeholder="example@gmail.com" id="userpassword">
        </div>
         <div class="input-group d-flex align-items-center">
            <input type="checkbox" id="newletter" aria-label="Checkbox for following text input">
            <label for="newletter" class="ml-2">Send me DIA newsletter</label>
        </div>
        <div class="mt-4">
            <button type="submit" class="btn btn-block btn-primary">Sign up</button>
        </div>

        <div class="my-3">
            <p>
                By clicking sign up, I accept the 
                <nuxt-link class="text-primary" to="/">Terms and Conditions</nuxt-link> and 
                <nuxt-link class="text-primary" to="/">Privacy Policy</nuxt-link>
            </p>
        </div>
        <div class="mt-4">
            <button type="submit" class="btn btn-block btn-outline-dark">Already have an account? Log in</button>
        </div>
    </form>
  </div>
</template>

<script>
export default {
    name: 'Signin-form',
}
</script>

<style scoped>
form{
    margin-bottom:40px;
}
.btn.btn-block.btn-primary, .btn-outline-dark{
    height: 48px;
}
.form-group input[type=text].form-control{
    border: 1px solid #D9D9D9;
}
</style>