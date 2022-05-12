<template>
  <div>
    <TitleCom/>
    <HeroComp/>
  </div>
</template>

<script>
import TitleCom from './components/TitleCom.vue'
import HeroComp from './components/HeroComp.vue'

export default {
  name: 'App',
  components: {
    TitleCom,
    HeroComp
  }
}
</script>

<style lang="scss">

</style>
