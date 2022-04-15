<template>
  <section class="p-5 bg-light">
    <div class="container d-flex justify-content-center align-items-center">
      <div class="row justify-content-center pt-5">
        <div class="col-lg-1 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start h-100 d-flex align-items-center">
            <router-link to="#">
              <i class="fas fa-arrow-left"></i>
            </router-link>
          </div>
        </div>
        <div class="col-lg-4 mb-5 mb-lg-0 border-end px-5">
          <div class="wrapper text-center text-lg-start">
            <p class="text-fade-black-1 text-uppercase">previous post</p>
            <h3>The ultimate guide to traveling when you have no money</h3>
          </div>
        </div>
        <div class="col-lg-4 mb-5 mb-lg-0 border-start px-5">
          <div class="wrapper text-center text-lg-start">
            <p class="text-fade-black-1 text-uppercase">next post</p>
            <h3>How to find and buy good travel insurance</h3>
          </div>
        </div>
        <div class="col-lg-1 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start h-100 d-flex align-items-center">
            <router-link to="#">
              <i class="fas fa-arrow-right"></i>
            </router-link>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionFooterComponent",
}
</script>