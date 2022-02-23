<template>
  <section>
    <div class="flex flex-row items-center py-8 h-screen bg-animate mb-20">
      <div class="text-xl font-bold text-center md:text-left container mx-auto px-4">
        <div class="text-5xl text-white">
          Привет, меня зовут <span class="text-blue-300">Илья Захаров</span>
        </div>
        <div class="text-4xl mb-4 text-white">
          и я <span class="text-blue-300">Frontend</span> разработчик
        </div>
        <p class="font-normal text-white mb-4">
          Большинство хороших программистов делают свою работу не потому, что ожидают оплаты или признания, а потому что
          получают удовольствие от программирования. <span class="text-blue-300">&copy; Linus Torvalds</span>
        </p>
        <div class="flex flex-row justify-center md:justify-start space-x-4 text-base font-normal">
          <a
            href="#use"
            class="px-4 py-2 bg-white rounded text-blue-500 transition duration-300 hover:bg-blue-300 hover:text-white"
          >
            Посмотреть
          </a>
          <button class="px-4 py-2 bg-blue-500 rounded text-white transition duration-300 hover:bg-blue-300">
            Связаться
          </button>
        </div>
      </div>
    </div>
    <div id="use" class="mb-20 container mx-auto">
      <div class="text-5xl font-bold text-center mb-8">
        Я использую
      </div>
      <div class="grid sm:grid-cols-2 lg:grid-cols-4 gap-8 px-4">
        <div
          class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold">
            HTML
          </div>
          <div>
            <img src="@/static/icons/html.svg" alt="html">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque,
            nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div
          class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold">
            CSS
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/css.svg" alt="css">
            <img src="@/static/icons/tailwind.svg" alt="tw">
            <img src="@/static/icons/bootstrap.svg" alt="bootstrap">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque,
            nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div
          class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold">
            JavaScript
          </div>
          <div>
            <img src="@/static/icons/js.svg" alt="js">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque,
            nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div
          class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold">
            Vue
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/vue.svg" alt="vue">
            <img src="@/static/icons/nuxt.svg" alt="nuxt">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque,
            nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div
          class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold text-center">
            Сборщики проектов
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/webpack.svg" alt="webpack">
            <img src="@/static/icons/gulp.svg" alt="gulp">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque,
            nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div
          class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold text-center">
            Git
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/git.svg" alt="git">
            <img src="@/static/icons/github.svg" alt="github">
            <img src="@/static/icons/bitbucket.svg" alt="bb">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque,
            nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div
          class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold text-center">
            Дизайн
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/figma.svg" alt="figma">
            <img src="@/static/icons/framer.svg" alt="framer">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque,
            nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
        <div
          class="flex flex-col justify-between items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold text-center">
            Планировщик задач
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/notion.svg" alt="notion">
            <img src="@/static/icons/jira.svg" alt="jira">
          </div>
          <div>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad aliquid cum eaque eos et excepturi illo itaque,
            nam odio repellat sed totam voluptatum? Autem hic illum laudantium libero rem totam?
          </div>
        </div>
      </div>
    </div>
    <div class="container mx-auto px-4">
      <div class="text-5xl font-bold text-center mb-8">
        Обо мне
      </div>
      <div class="md:grid grid-cols-3 gap-x-4 mb-8">
        <div class="w-full mb-4 col-span-1">
          <img class="rounded-2xl shadow w-full sm:mx-0 mx-auto sm:mx-none" src="@/static/main_photo.jpg">
        </div>
        <div class="col-span-2">
          <ol class="relative border-l border-gray-500">
            <li class="mb-10 ml-4 group">
              <div
                class="absolute w-3 h-3 bg-gray-500 rounded-full transition duration-300 group-hover:bg-blue-500 -left-1.5 border border-white "
              />
              <time class="mb-1 text-sm font-normal leading-none text-gray-500 transition duration-300 group-hover:text-blue-500">Октябрь 2020</time>
              <h3 class="text-lg font-semibold text-gray-900 dark:text-white">
                Начал изучать профессию Frontend разработчика
              </h3>
            </li>
            <li class="mb-10 ml-4 group">
              <div
                class="absolute w-3 h-3 bg-gray-500 rounded-full transition duration-300 group-hover:bg-blue-500 -left-1.5 border border-white "
              />
              <time class="mb-1 text-sm font-normal leading-none text-gray-500 transition duration-300 group-hover:text-blue-500">Апрель 2021</time>
              <h3 class="text-lg font-semibold text-gray-900 dark:text-white">
                Фриланс
              </h3>
              <p class="text-base font-normal text-gray-500  ml-4">
                &#9702; Участие в различных проетах как верстальщик/frontend разработчик. <br>
                &#9702; Внесение изменений в уже действующие
                веб-сайты, верстка HTML писем для рассылок по email.
              </p>
            </li>
            <li class="ml-4 group">
              <div
                class="absolute w-3 h-3 bg-gray-500 rounded-full transition duration-300 group-hover:bg-blue-500 -left-1.5 border border-white "
              />
              <time class="mb-1 text-sm font-normal leading-none text-gray-500 transition duration-300 group-hover:text-blue-500">Сентябрь 2022</time>
              <h3 class="text-lg font-semibold text-gray-900">
                Работа в digital-агентстве
              </h3>
              <p class="text-base font-normal text-gray-500  ml-4">
                &#9702; Разработка проектов (Frontend части) с нуля <br>
                &#9702; Доработка существующих проектов <br>
                &#9702; Разработка бизнес-логики для поддержки продукта <br>
                &#9702; Проектирование пользовательских интерфейсов <br>
                &#9702; Кроссбраузерная и адаптивная верстка HTML5/CSS3 <br>
              </p>
            </li>
          </ol>
        </div>
      </div>
      <div class="text-xl bg-white rounded-xl shadow-xl p-4">
        С октября 2020 года я занимаюсь Веб-разработкой, до сентября 2021 года я активно принимал участие в проектах
        на фрилансе, разрабатывал функционал на действующих Веб-сайтах с использованием jQuery и SPA, разработанных на
        Vue.js. <br><br>
        В сентябре этого года я начал работать в коммерческой разработке, как Junior Frontend Developer. Занимаюсь
        улучшением и доработкой действующего, а также интеграцией нового функционала на веб-сайтах и разработкой новых
        проектов на Vue.js.
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
  background: linear-gradient(-45deg, #4b5563, #1e3a8a, #1e40af, #334155);
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
