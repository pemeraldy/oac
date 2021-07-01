<template>
  <div class="w-100">
    <form>        
        <div class="form-group required">
            <label for="userpassword">Email*</label>
            <input type="email" class="form-control" id="userpassword">
        </div>
        
        <div class="my-5">
            <button type="submit" class="btn btn-block btn-primary">Request password reset</button>
        </div>
    </form>
  </div>
</template>

<script>
export default {
    name: 'Request-pw-form',
}
</script>

<style>

</style>