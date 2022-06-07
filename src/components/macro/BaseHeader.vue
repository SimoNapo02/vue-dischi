<template>
  <header>
    <div class="container">
      <LogoSec />
    </div>
  </header>
</template>

<script>
import LogoSec from "../sections/LogoSec.vue";
export default {
  name: "BaseHeader",
  components: {
    LogoSec,
  },
};
</script>

<style lang="scss" scoped>
header {
  background-color: var(--secondary-color);
  height: var(--header-md);
}
</style>
