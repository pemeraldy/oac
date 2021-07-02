<template>
  <div>
    <div class=" bg-primary py-2">
      <div class="container">
        <nuxt-link to="/" tag="div" class="navbar-brand">
          <img class="ml-3" src="~/assets/images/logo.png" alt="cop logo" />
        </nuxt-link>
      </div>
    </div>
    <AppAdminNav />
    <Nuxt />
  </div>
</template>

<script>
export default {};
</script>

<style></style>
