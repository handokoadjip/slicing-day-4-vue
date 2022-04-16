<template>
  <HeaderComponent />
  <main>
    <router-view />
  </main>
  <SectionFooterComponent />
  <FooterComponent />
</template>

<script>
import HeaderComponent from "@/components/HeaderComponent.vue"
import SectionFooterComponent from "@/components/SectionFooterComponent.vue";
import FooterComponent from "@/components/FooterComponent.vue"

export default {
  name: 'App',
  components: {
    HeaderComponent,
    SectionFooterComponent,
    FooterComponent,
  }
}
</script>

<style>
/* Style Here */
</style>
