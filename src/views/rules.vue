<template lang="pug">
  .rule

    TOPSTUFF
    //- BOTTON2
    //- entryanima
    stars1
    stars2
    stars3
    stars4
    RULEE
    //- slideshow
    //- router-view
    //- Backgron
    //- EYES

</template>

<script>
// @ is an alias to /src
import TOPSTUFF from '@/components/TOPSTUFF.vue'
// import BOTTON2 from '@/components/BOTTON2.vue'
import entryanima2 from '@/components/entryanima2.vue'
import stars1 from '@/components/stars1.vue'
import stars2 from '@/components/stars2.vue'
import stars3 from '@/components/stars3.vue'
import stars4 from '@/components/stars4.vue'
import RULEE from '@/components/RULEE.vue'
// import slideshow from '@/components/slideshow.vue'

// import Backgron from '@/components/Backgron.vue'
// import EYES from '@/components/EYES.vue'

export default {
  // name: 'Home',
  components: {
    TOPSTUFF,
    // BOTTON2,
    entryanima2,
    stars1,
    stars2,
    stars3,
    stars4,
    RULEE,
    // slideshow,

    // Backgron,
    // EYES,
  }
}
</script>
<style lang="sass">
.rule
  min-height: 2200px
  margin: 0px
  padding: 0px
</style>
