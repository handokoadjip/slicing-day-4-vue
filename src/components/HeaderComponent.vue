<template>
  <header class="mb-5 pb-5">
    <nav class="navbar navbar-expand-lg navbar-light px-4">
      <div class="container py-3 border-bottom">
        <router-link class="navbar-brand text-center text-uppercase mp-0 d-flex align-items-center" to="#">
          <i class="fab fa-audible text-primary fa-2x me-3 fw-medium"></i>
          my dream travel blog
        </router-link>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
          <ul class="navbar-nav text-uppercase ms-auto">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center fw-medium" aria-current="page" to="#">work</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center fw-medium" to="#">about</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center fw-medium text-primary" to="#">blog</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center fw-medium" to="#">contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

