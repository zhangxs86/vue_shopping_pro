<template>
  <div>
    <h2>
      <m-header></m-header>
    </h2>
    <router-view></router-view>
  </div>
</template>

<script>
import MHeader from "@/common/MHeader";
export default {
  components: {
    MHeader,
  },
};
</script>


<style lang="sass" scoped>
</style>