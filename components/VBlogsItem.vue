<template>
  <div class="container mx-auto px-4 py-8">
    <div class="grid md:grid-cols-2 xl:grid-cols-4 gap-8 px-4">
      <div
        v-for="(blog, idx) in blogs"
        :key="idx"
        class="flex flex-col justify-between px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
      >
        <div>
          <div class="w-full mb-4">
            <img class="object-cover w-full h-40" :src="blog.picture" alt="pict">
          </div>
          <div class="text-lg font-bold mb-4">
            {{ blog.name }}
          </div>
          <div class="text-sm mb-4">
            {{ blog.description }}
          </div>
        </div>
        <div>
          <a class="transition duration-300 text-blue-500 hover:text-blue-700" :href="blog.link" target="_blank">Прочитать</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import BLOGS from '@/components/constants/blogs'
export default {
  name: 'VBlogsItem',
  data () {
    return {
      blogs: BLOGS
    }
  }
}
</script>

<style scoped>

</style>
