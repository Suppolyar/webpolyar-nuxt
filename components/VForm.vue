<template>
  <div class="w-full">
    <div class="max-w-5xl mx-auto ">
      <div v-if="showForm" class="bg-white w-full shadow-lg rounded p-8 sm:p-12">
        <p class="text-3xl font-bold leading-7 text-center">
          Связаться со мной
        </p>
        <form>
          <div class="md:flex items-center mt-12">
            <div class="w-full md:w-1/2 flex flex-col">
              <label class="font-semibold leading-none">Имя *</label>
              <input v-model="name" type="text" name="name" class="leading-none text-gray-900 p-3 focus:outline-none focus:border-blue-500 mt-4 bg-gray-100 border rounded border-gray-200">
            </div>
            <div class="w-full md:w-1/2 flex flex-col md:ml-6 md:mt-0 mt-4">
              <label class="font-semibold leading-none">Телефон</label>
              <input v-model="phone" type="tel" name="tel" class="leading-none text-gray-900 p-3 focus:outline-none focus:border-blue-500 mt-4 bg-gray-100 border rounded border-gray-200">
            </div>
          </div>
          <div class="md:flex items-center mt-8">
            <div class="w-full md:w-1/2 flex flex-col">
              <label class="font-semibold leading-none">Email *</label>
              <input v-model="email" type="email" name="email" class="leading-none text-gray-900 p-3 focus:outline-none focus:border-blue-500 mt-4 bg-gray-100 border rounded border-gray-200">
            </div>
            <div class="w-full md:w-1/2 flex flex-col md:ml-6 md:mt-0 mt-4">
              <label class="font-semibold leading-none">Компания</label>
              <input v-model="company" type="text" class="leading-none text-gray-900 p-3 focus:outline-none focus:border-blue-500 mt-4 bg-gray-100 border rounded border-gray-200">
            </div>
          </div>
          <div>
            <div class="w-full flex flex-col mt-8">
              <label class="font-semibold leading-none">Сообщение</label>
              <textarea v-model="message" type="text" class="h-40 text-base leading-none text-gray-900 p-3 focus:oultine-none focus:border-blue-500 mt-4 bg-gray-100 border rounded border-gray-200" />
            </div>
          </div>
          <div class="flex justify-center mt-6 cursor-pointer">
            <label
              class="flex items-center"
            >
              <input type="checkbox" class="form-checkbox" @click="acceptRules">
              <span class="ml-2">Я согласен с <NuxtLink to="/policy"><span class="underline hover:text-blue-500 transition duration-300">политикой конфиденциальности</span></NuxtLink></span>
            </label>
          </div>
          <div v-if="showErrorMessage" class="text-red-700 text-center mt-2">
            Чтобы отправить сообщение, вам нужно согласиться с политикой конфедециальности, а так же заполнить все обязательные поля
          </div>
          <div class="flex items-center justify-center w-full">
            <button
              class="mt-9 font-semibold leading-none text-white py-4 px-10 bg-blue-500 rounded hover:bg-blue-300 transition duration-300"
              @click.prevent="sendForm"
            >
              Отправить
            </button>
          </div>
        </form>
      </div>
      <div v-else class="bg-white w-full shadow-lg rounded p-8 sm:p-12 flex flex-col items-center justify-center">
        <p class="text-3xl font-bold leading-7 text-center mb-8">
          Спасибо!
        </p>
        <div class="mb-8">
          <img src="@/static/friends.gif" alt="gif">
        </div>
        <p class="text-2xl leading-7 text-center">
          В скором времени я свяжусь с вами :)
        </p>
        <NuxtLink
          to="/"
          class="mt-9 font-semibold leading-none text-white py-4 px-10 bg-blue-500 rounded hover:bg-blue-300 transition duration-300"
        >
          На главную
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'VForm',
  data () {
    return {
      name: '',
      phone: '',
      email: '',
      message: '',
      company: '',
      showErrorMessage: false,
      rules: false,
      showForm: true
    }
  },
  computed: {
    validForm () {
      return this.rules === true && this.name.length > 0 && this.email.length > 0
    }
  },
  methods: {
    acceptRules () {
      this.rules = !this.rules
    },
    sendForm () {
      if (this.validForm) {
        this.$mail.send({
          from: this.email,
          subject: 'Отправлено с моего сайта',
          html: `
        Имя: ${this.name}, <br>
        Телефон: ${this.phone}, <br>
        Почта: ${this.email}, <br>
        Компания: ${this.company}, <br>
        Сообщение: ${this.message}`
        })
        this.showForm = false
      } else {
        this.showErrorMessage = true
      }
    }
  }
}
</script>

<style scoped>

</style>
