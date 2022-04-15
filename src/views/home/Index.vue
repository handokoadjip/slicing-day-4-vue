<template>
  <TitleComponent />
  <ContentComponent />
  <SectionFooterComponent />
</template>

<script>
import TitleComponent from "@/components/TitleComponent.vue";
import ContentComponent from "@/components/ContentComponent.vue";
import SectionFooterComponent from "@/components/SectionFooterComponent.vue";

export default {
  name: "HomePage",
  components: {
    TitleComponent,
    ContentComponent,
    SectionFooterComponent,
  },
  mounted() {
    document.title = "Milan Vučković | MY DREAM TRAVEL BLOG"
  }
}
</script>
