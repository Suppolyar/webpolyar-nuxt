<template>
  <section class="py-8">
    <div class="text-5xl font-bold text-center mb-8">
      Интересные статьи и ссылки
    </div>
    <VBlogsItem class="mb-20" />
    <div class="text-5xl font-bold text-center mb-8">
      Минутка доброты
    </div>
    <VAdvertising />
  </section>
</template>

<script>
import VBlogsItem from '@/components/VBlogsItem'
export default {
  components: { VBlogsItem }
}
</script>

<style scoped>

</style>
