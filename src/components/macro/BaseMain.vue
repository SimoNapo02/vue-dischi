<template>
  <main>
    <AlbumSection />
  </main>
</template>

<script>
import AlbumSection from "../sections/AlbumSec.vue";
export default {
  name: "BaseMain",
  components: {
    AlbumSection,
  },
};
</script>

<style lang="scss" scoped>
main {
  background-color: var(--primary-color);
  min-height: calc(100vh - 3.75rem);
}
</style>
