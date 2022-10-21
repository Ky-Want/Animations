<template>
  <div class="mb-5 pb-5">
    <WalkingCatLoader />
  </div>

  <div class="mb-5 pb-5">
    <WhiteOrbLoader />
  </div>

  <div class="mb-5 pb-5">
    <PlanetLoader />
  </div>

  <div class="mb-5 pb-5">
    <WordTornadoLoader />
  </div>

  <div class="mb-5 pb-5">
    <WatchingCatLoader />
  </div>



  <!-- <LightSabers /> -->

  <!-- <InfinityLoopCord /> -->

  <!-- <GooeyLoader /> -->
</template>






<script>
import WatchingCatLoader from "../components/WatchingCatLoader.vue";
import WalkingCatLoader from "../components/WalkingCatLoader.vue";
import LightSabers from "../components/LightSabers.vue";
import InfinityLoopCord from "../components/InfinityLoopCord.vue";
import WhiteOrbLoader from "../components/WhiteOrbLoader.vue";
import PlanetLoader from "../components/PlanetLoader.vue";
import GooeyLoader from "../components/GooeyLoader.vue";
import WordTornadoLoader from "../components/My Animations/WordTornadoLoader.vue";

export default {
  setup() {
    return {};
  },
  components: {
    WatchingCatLoader,
    WalkingCatLoader,
    LightSabers,
    InfinityLoopCord,
    WhiteOrbLoader,
    PlanetLoader,
    GooeyLoader,
    WordTornadoLoader,
  }
}
</script>






<style scoped lang="scss">

</style>