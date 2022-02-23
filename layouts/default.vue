<template>
  <div>
    <VHeader />
    <Nuxt />
    <VFooter />
  </div>
</template>

<script>
import VHeader from '@/components/VHeader'
import VFooter from '@/components/VFooter'
export default {
  components: {
    VHeader,
    VFooter
  }
}
</script>
