<template>
  <TitleComponent />
  <ContentComponent />
</template>

<script>
import TitleComponent from "@/components/TitleComponent.vue";
import ContentComponent from "@/components/ContentComponent.vue";

export default {
  name: "HomePage",
  components: {
    TitleComponent,
    ContentComponent,
  },
  mounted() {
    document.title = "Milan Vučković | MY DREAM TRAVEL BLOG"
  }
}
</script>
