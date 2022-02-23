<template>
  <section class="container mx-auto">
    <div class="py-8 text-xl text-center px-4">
      <div class="text-2xl font-bold">
        Разработчик трудится над этой страничкой
      </div>
      <div class="mb-10">
        Может хотите вернуться на <NuxtLink to="/">
          <span class="text-blue-500">главную</span>
        </NuxtLink>?
      </div>
      <div class="mb-10">
        <img class="lg:w-1/2 mx-auto" src="@/static/plug.gif" alt="">
      </div>
      <div class="text-left sm:text-center">
        <div class="text-2xl font-bold mb-8">
          А может несколько интересных фактов про it? например:
        </div>
        <div class="max-w-3xl mx-auto text-left">
          <p class="mb-4">
            &#9702;
            Среднестатистический пользователь компьютера моргает 7 раз в минуту. Нормальный показатель – 12 раз в минуту.
          </p>
          <p class="mb-4">
            &#9702;
            Текст с экрана читается на 10% медленнее, чем с бумаги.
          </p>
          <p class="mb-4">
            &#9702;
            Каждую секунду на интернет-площадке eBay.com происходят транзакции на сумму в 680 долларов (около 53 110 руб.).
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'VPlug'
}
</script>

<style scoped>

</style>
