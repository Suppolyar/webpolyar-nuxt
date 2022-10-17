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
        <div class="flex flex-row justify-center items-center md:justify-start space-x-4 text-lg font-normal">
          <a
            href="#use"
            class="px-4 py-2 bg-white rounded text-blue-500 transition duration-300 hover:bg-blue-300 hover:text-white"
          >
            Посмотреть
          </a>
          <NuxtLink to="/contacts" class="px-4 py-2 bg-blue-500 rounded text-white transition duration-300 hover:bg-blue-300">
            Связаться
          </NuxtLink>

          <span class="text-white">или</span>
          <a href="tg://resolve?domain=Suppolyar" target="_blank" class="telegram-link">
            <svg width="36" height="31" viewBox="0 0 36 31" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M35.8974 2.82215L30.4648 29.1287C30.0549 30.9853 28.9861 31.4474 27.4672 30.5728L19.1897 24.3097L15.1956 28.254C14.7536 28.7079 14.3839 29.0874 13.532 29.0874L14.1267 20.4314L29.4683 6.19711C30.1353 5.58648 29.3236 5.24816 28.4316 5.85879L9.4656 18.1209L1.30059 15.4968C-0.475462 14.9275 -0.507608 13.6732 1.67027 12.7985L33.607 0.165084C35.0857 -0.404286 36.3796 0.503405 35.8974 2.82215V2.82215Z" fill="white"/>
            </svg>
          </a>
        </div>
      </div>
    </div>
    <div id="use" class="mb-20 container mx-auto">
      <div class="text-5xl font-bold text-center mb-8">
        Я использую
      </div>
      <div class="grid sm:grid-cols-2 xl:grid-cols-4 gap-8 px-4">
        <div
          class="flex flex-col items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold">
            HTML
          </div>
          <div>
            <img src="@/static/icons/html.svg" alt="html">
          </div>
          <div>
            Это язык гипертекстовой разметки страницы. Он используется для того, чтобы дать браузеру понять, как нужно отображать загруженный сайт
          </div>
        </div>
        <div
          class="flex flex-col items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
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
            Формальный язык описания внешнего вида документа (веб-страницы), написанного с использованием языка разметки. В своей работе я использую css-фреймворки
            <a class="text-blue-500" href="https://tailwindcss.com/" target="_blank">TailwindCSS</a> и <a class="text-purple-500" href="https://getbootstrap.com/" target="_blank">Bootstrap</a>
          </div>
        </div>
        <div
          class="flex flex-col items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold">
            Javascript <br>
            Typescript
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/js.svg" alt="js">
            <img src="@/static/icons/typescript.svg" alt="ss">
          </div>
          <div>
            Полноценный динамический язык программирования, который применяется к HTML документу, и может обеспечить динамическую интерактивность на веб-сайтах
          </div>
        </div>
        <div
          class="flex flex-col items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold">
            Vue
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/vue.svg" alt="vue">
            <img src="@/static/icons/nuxt.svg" alt="nuxt">
          </div>
          <div>
            <a class="text-green-500" href="https://ru.vuejs.org/" target="_blank">Vue</a> — это прогрессивный фреймворк для создания пользовательских интерфейсов. Vue создан пригодным для постепенного внедрения, что упрощает интеграцию с другими библиотеками и существующими проектами. А свой сайт портфолио я сделал с помощью
            <a class="text-green-500" href="https://nuxtjs.org/" target="_blank">Nuxt.js</a>, который позволяет создавать готовые к работе веб-приложения и призван упростить разработку универсальных и одностраничных сервисов
          </div>
        </div>
        <div
          class="flex flex-col items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold text-center">
            Сборщики проектов
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/webpack.svg" alt="webpack">
            <img src="@/static/icons/gulp.svg" alt="gulp">
          </div>
          <div>
            Сборка проекта позволяет ускорить и упростить разработку, но за это придётся заплатить некоторую цену. Если разрабатывается крупное веб-приложение с богатой функциональностью, то эта цена оказывается сравнительно небольшой. Если же она вас по каким-то причинам не устраивает, например, когда требуется написать что-то простое, то, возможно, будет лучше обойтись и без сборки
          </div>
        </div>
        <div
          class="flex flex-col items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
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
            Система управления версиями. У Git две основных задачи: первая —  хранить информацию о всех изменениях в вашем коде, начиная с самой первой строчки, а вторая — обеспечение удобства командной работы над кодом
          </div>
        </div>
        <div
          class="flex flex-col items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold text-center">
            Дизайн
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/figma.svg" alt="figma">
            <img src="@/static/icons/framer.svg" alt="framer">
          </div>
          <div>
            Графические онлайн-редакторы для совместной работы. В них можно создать прототип сайта, интерфейс приложения и обсудить правки с коллегами в реальном времени
          </div>
        </div>
        <div
          class="flex flex-col items-center px-4 py-8 bg-white border rounded transition duration-300 hover:shadow-2xl space-y-4"
        >
          <div class="text-2xl font-bold text-center">
            Планировщик задач
          </div>
          <div class="flex flex-row space-x-4">
            <img src="@/static/icons/notion.svg" alt="notion">
            <img src="@/static/icons/jira.svg" alt="jira">
          </div>
          <div>
            Планировщик задач помогает вам упорядочить ваши задачи и станет эффективным инструментом тайм-мененджмента
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
              <h3 class="font-semibold text-gray-900 dark:text-white">
                Начал изучать профессию Frontend разработчика
              </h3>
            </li>
            <li class="mb-10 ml-4 group">
              <div
                class="absolute w-3 h-3 bg-gray-500 rounded-full transition duration-300 group-hover:bg-blue-500 -left-1.5 border border-white "
              />
              <time class="mb-1 text-sm font-normal leading-none text-gray-500 transition duration-300 group-hover:text-blue-500">Апрель 2021</time>
              <h3 class="font-semibold text-gray-900 dark:text-white">
                Фриланс
              </h3>
              <p class="font-normal text-gray-500  ml-4">
                &#9702; Участие в различных проетах как верстальщик/frontend разработчик <br>
                &#9702; Внесение изменений в уже действующие
                веб-сайты, верстка HTML писем для рассылок по email
              </p>
            </li>
            <li class="mb-10 ml-4 group">
              <div
                class="absolute w-3 h-3 bg-gray-500 rounded-full transition duration-300 group-hover:bg-blue-500 -left-1.5 border border-white "
              />
              <time class="mb-1 text-sm font-normal leading-none text-gray-500 transition duration-300 group-hover:text-blue-500">Сентябрь 2021</time>
              <h3 class="font-semibold text-gray-900">
                Работа в digital-агентстве
              </h3>
              <p class="font-normal text-gray-500  ml-4">
                &#9702; Разработка проектов (Frontend части) с нуля <br>
                &#9702; Доработка существующих проектов <br>
                &#9702; Разработка бизнес-логики для поддержки продукта <br>
                &#9702; Проектирование пользовательских интерфейсов <br>
                &#9702; Кроссбраузерная и адаптивная верстка HTML5/CSS3 <br>
              </p>
            </li>
            <li class="ml-4 group">
              <div
                class="absolute w-3 h-3 bg-gray-500 rounded-full transition duration-300 group-hover:bg-blue-500 -left-1.5 border border-white "
              />
              <time class="mb-1 text-sm font-normal leading-none text-gray-500 transition duration-300 group-hover:text-blue-500">Февраль 2022</time>
              <h3 class="text-lg font-semibold text-gray-900">
                Работа в продуктовой компании
              </h3>
              <p class="font-normal text-gray-500  ml-4">
                &#9702; Разрабатывал и поддерживал Frontend часть нескольких web-приложений/сайтов <br>
                &#9702; Участвовал с нуля в разработке сервиса по онлайн платежам (есть опыт в работе с приложениями, связанные с криптовалютой) <br>
                &#9702; Проводил код-ревью <br>
                &#9702; Настраивал конфигурацию приложений на этапе разработки (Webpack, Vite, ESLint, Prettier, небольшой опыт CI/CD) <br>
                &#9702; Участвовал в обучении/наставлении по работе с Git у Junior-программистов <br>
              </p>
            </li>
          </ol>
        </div>
      </div>
      <div class="text-lg bg-white rounded-xl shadow-xl p-4">
        В октябре 2020 года я самостоятельно начал изучать Веб-разработку, читая научную литературу, утопая в технических документациях и разных профильных онлайн-курсах. Около года, с начала своего пути в IT-индустрии, я активно принимал участие в проектах на фрилансе, разрабатывал функционал на действующих Веб-сайтах с использованием jQuery и SPA, разработанных на Vue.js.
        <br><br>
        В сентябре 2021 года я присоединился к команде digital-агентства, как Junior Frontend Developer, и начал развивать свои навыки в коммерческой разработке: занимался улучшением и доработкой действующего, а также интеграцией нового функционала на веб-сайтах и разработкой новых проектов на Vue.js.
        <br><br>
        А с февраля 2022 года, я работаю в продуктовой компании, в команде по разработке системы онлайн-платежей, связанных с криптовалютами.
        <br><br>
        В команде, в которой я буду работать в будущем, я хочу видеть заинтересованных единомышленников, возможности для профессионального роста и приятную дружескую атмосферу :)
        <br>
        Самый удобный способ связи для меня Telegram: <a href="tg://resolve?domain=Suppolyar" target="_blank" class="text-blue-400">Suppolyar</a>
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
  background: linear-gradient(-45deg, #4b5563, #1e3a8a, rgba(110, 23, 116, 0.98), #334155);
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

.telegram-link svg:hover path {
  transition: all 0.3s linear;
  fill: #3B82F6;
}
</style>
