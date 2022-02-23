<template>
  <div>
    <VHeroSection />
  </div>
</template>

<script>
import VHeroSection from '~/components/VHeroSection'
export default {
  name: 'IndexPage',
  components: { VHeroSection }

}
</script>

<style>
* {
  @apply text-gray-800;
}
</style>
