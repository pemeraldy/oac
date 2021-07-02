<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-primary">
    <div class="container">
        <nuxt-link to="/" tag="div" class="navbar-brand">
          <img src="~/assets/images/logo.png" alt="cop logo">
        </nuxt-link>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto d-flex align-items-center">
      <li class="nav-item mx-3 active">
        <a class="nav-link text-white" href="#">Events <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item mx-3">
        <a class="nav-link text-white" href="#">Knowledge Repository</a>
      </li>
      <li class="nav-item mx-3">      
        <a class="nav-link text-white" href="#">About Us</a>
      </li>
      <li v-if="$route.path === '/' || $route.path === '/auth/sign-up'  " class="nav-item mx-3">
        <nuxt-link to="/auth/sign-in" tag="button" class="btn nav-btn btn-outline-success my-2 my-sm-0" type="submit">Sign in</nuxt-link>
      </li>
      <li v-if="$route.path === '/auth/sign-in' " class="nav-item mx-3">
        <nuxt-link to="/auth/sign-up" tag="button" class="btn nav-btn btn-outline-success my-2 my-sm-0" type="submit">Sign up</nuxt-link>
      </li>
    </ul>
    <form v-if="$route.path !== '/community'" class="form-inline my-2 my-lg-0 position-relative">
      <input class="form-control nav-input mr-sm-2" type="search" placeholder="Search" aria-label="Search for health questions">
      <i class="text-gray text-muted search-icon position-absolute mr-3 fa fa-search"></i>
    </form>
    <div class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          <span class="text-white">Yopee</span>
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
          <a class="dropdown-item" href="#">Profile</a>
          <a class="dropdown-item" href="#">Sign out</a>
        </div>
      </div>
  </div>
    </div>
</nav>
</template>
<style scoped>
.nav-btn, .nav-input {
  height: 30px ;
}
.nav-btn{
  width: 80px;
  line-height: 2px !important;
}
.search-icon{
  right:0;
}

/* Responsive */
@media screen and (max-width: 500px) {
  
}
</style>