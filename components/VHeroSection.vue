<template>
  <section>
    <div class="flex flex-row items-center py-8 h-screen bg-animate">
      <div class="text-xl font-bold text-center md:text-left px-4">
        <div class="text-5xl text-white">
          Привет, меня зовут <span class="text-blue-200">Илья Захаров</span>
        </div>
        <div class="text-4xl mb-4 text-white">
          и я <span class="text-blue-200">Frontend</span> разработчик
        </div>
        <p class="font-normal text-white mb-4">
          Большинство хороших программистов делают свою работу не потому, что ожидают оплаты или признания, а потому что получают удовольствие от программирования. <span class="text-blue-200">&copy; Linus Torvalds</span>
        </p>
        <div class="flex flex-row justify-center md:justify-start space-x-4 text-base font-normal">
          <a href="#use" class="px-4 py-2 bg-white rounded text-blue-500 transition duration-300 hover:bg-blue-300 hover:text-white">
            Посмотреть
          </a>
          <button class="px-4 py-2 bg-blue-500 rounded text-white transition duration-300 hover:bg-blue-300">
            Связаться
          </button>
        </div>
      </div>
    </div>
    <div id="use" class="mb-40">
      <div class="text-5xl font-bold text-center mb-8">
        Я использую
      </div>
      <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-8 px-4 sm:px-0">
        <div class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4">
          <div class="text-2xl font-bold">
            HTML
          </div>
          <div>
            <img src="@/static/icons/html.svg" alt="html">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque, nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4">
          <div class="text-2xl font-bold">
            CSS
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/css.svg" alt="css">
            <img src="@/static/icons/tailwind.svg" alt="tw">
            <img src="@/static/icons/bootstrap.svg" alt="bootstrap">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque, nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4">
          <div class="text-2xl font-bold">
            JavaScript
          </div>
          <div>
            <img src="@/static/icons/js.svg" alt="js">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque, nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4">
          <div class="text-2xl font-bold">
            Vue
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/vue.svg" alt="vue">
            <img src="@/static/icons/nuxt.svg" alt="nuxt">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque, nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4">
          <div class="text-2xl font-bold text-center">
            Сборщики проектов
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/webpack.svg" alt="webpack">
            <img src="@/static/icons/gulp.svg" alt="gulp">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque, nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4">
          <div class="text-2xl font-bold text-center">
            Git
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/git.svg" alt="git">
            <img src="@/static/icons/github.svg" alt="github">
            <img src="@/static/icons/bitbucket.svg" alt="bb">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque, nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4">
          <div class="text-2xl font-bold text-center">
            Дизайн
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/figma.svg" alt="figma">
            <img src="@/static/icons/framer.svg" alt="framer">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque, nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4">
          <div class="text-2xl font-bold text-center">
            Планировщик задач
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/notion.svg" alt="notion">
            <img src="@/static/icons/jira.svg" alt="jira">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque, nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
      </div>
    </div>
    <div>
      <div class="text-5xl font-bold text-center mb-8">
        Обо мне
      </div>
      <div class="md:grid grid-cols-3 sm:px-0 px-4 gap-x-4">
        <div class="w-full mb-4 col-span-1">
          <img class="rounded-2xl shadow w-full h-full sm:mx-0 mx-auto sm:mx-none" src="@/static/main_photo.jpg">
        </div>
        <div class="text-xl col-span-2">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab adipisci asperiores blanditiis commodi corporis, cum dolorem enim eos et eveniet ex id ipsam maxime nesciunt porro reprehenderit suscipit. Consequuntur, corporis.
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ab adipisci asperiores blanditiis commodi corporis, cum dolorem enim eos et eveniet ex id ipsam maxime nesciunt porro reprehenderit suscipit. Consequuntur, corporis.
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'VHeroSection'
}
</script>

<style>
.bg-animate {
  background: linear-gradient(-45deg, #4b5563, #1e3a8a, #2563eb, #334155);
  background-size: 400% 400%;
  animation: gradient 15s ease infinite;
}

@keyframes gradient {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}
</style>
