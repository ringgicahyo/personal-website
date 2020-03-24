<template>
    <div id="app">
      <particlesJS/>
      <router-view name="header"></router-view>
      <main>
          <fade-transition origin="center" mode="out-in" :duration="250">
              <router-view/>
          </fade-transition>
      </main>
      <!-- <router-view name="footer"></router-view> -->
    </div>
</template>
<script>
import { FadeTransition } from "vue2-transitions";
import particlesJS from './views/components/ParticleJS';

export default {
  components: {
    FadeTransition,
    particlesJS
  },

};
</script>