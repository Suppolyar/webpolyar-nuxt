<template>
  <div>
    <VHeader />
    <VHeroSection class="container mx-auto" />
  </div>
</template>

<script>
import VHeader from '../components/VHeader'
import VHeroSection from '~/components/VHeroSection'
export default {
  name: 'IndexPage',
  components: { VHeader, VHeroSection }

}
</script>

<style>
* {
  @apply text-gray-800;
}
</style>
