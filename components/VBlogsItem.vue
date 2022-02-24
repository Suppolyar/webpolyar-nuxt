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
        <div class="flex flex-row link max-w-max cursor-pointer group">
          <a class="transition duration-300 text-blue-400 group-hover:text-blue-700" :href="blog.link" target="_blank">
            Прочитать
          </a>
          <svg
            width="24"
            height="24"
            viewBox="0 0 24 24"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="link__icon group"
          >
            <path d="M8 4L16 12L8 20" stroke="#60a5fa" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
          </svg>
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
.link:hover svg {
  transition: all 0.3s linear;
  transform: translateX(5px);
}
.link:hover svg path{
  transition: all 0.3s linear;
  stroke: #1e40af;
}
</style>
