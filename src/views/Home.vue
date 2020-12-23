<template lang="pug">
  .home

    TOPSTUFF
    BOTTONS

</template>

<script>
// @ is an alias to /src
import TOPSTUFF from '@/components/TOPSTUFF.vue'
import BOTTONS from '@/components/BOTTONS.vue'

export default {
  // name: 'Home',
  components: {
    TOPSTUFF,
    BOTTONS,
  }
}
</script>
<style lang="sass">
.home
  min-height: 2200px
</style>
