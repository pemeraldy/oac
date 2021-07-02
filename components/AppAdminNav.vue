<template>
  <nav class="navbar py-md-0 navbar-expand-lg navbar-light bg-primary-dark">
    <div class="container">
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto d-flex align-items-center">
          <li class="nav-item mx-3 active">
            <nuxt-link to="/events" class="nav-link text-white" href="#"
              >Dashboard <span class="sr-only">(current)</span></nuxt-link
            >
          </li>
          <li class="nav-item mx-3">
            <a class="nav-link text-white" href="#">Topics</a>
          </li>
          <li class="nav-item mx-3">
            <a class="nav-link text-white" href="#">Users</a>
          </li>
          <li class="nav-item mx-3">
            <a class="nav-link text-white" href="#">Events</a>
          </li>
          <li class="nav-item mx-3">
            <a class="nav-link text-white" href="#">Knowledge Repository</a>
          </li>
          <li
            v-if="$route.path === '/' || $route.path === '/auth/sign-up'"
            class="nav-item mx-3"
          >
            <nuxt-link
              to="/auth/sign-in"
              tag="button"
              class="btn nav-btn btn-outline-success my-2 my-sm-0"
              type="submit"
              >Sign in</nuxt-link
            >
          </li>
          <li v-if="$route.path === '/auth/sign-in'" class="nav-item mx-3">
            <nuxt-link
              to="/auth/sign-up"
              tag="button"
              class="btn nav-btn btn-outline-success my-2 my-sm-0"
              type="submit"
              >Sign up</nuxt-link
            >
          </li>
        </ul>

        <div class="nav-item dropdown">
          <a
            class="nav-link dropdown-toggle d-flex justify-content-center"
            href="#"
            id="navbarDropdownMenuLink"
            role="button"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false"
          >
            <span class="avatar mx-2"></span>
            <span style="line-height:40px;" class="mr-1 text-white">Yopee</span>
            <i style="line-height:40px;" class="text-white fa fa-chevron-down"></i>
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
.nav-btn,
.nav-input {
  height: 30px;
}
.nav-btn {
  width: 80px;
  line-height: 2px !important;
}
.search-icon {
  right: 0;
}
.dropdown-toggle::after {
  display: none !important;
}
.avatar {
  width: 40px;
  height: 40px;
  background: #ddd;
  display: inline-block;
  border-radius: 100%;
}
.bg-primary-dark{
  background: #0d6d40;
}
/* Responsive */
@media screen and (max-width: 500px) {
}
</style>
