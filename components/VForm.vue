<template>
  <div class="w-full">
    <div class="max-w-5xl mx-auto ">
      <div class="bg-white w-full shadow-lg rounded p-8 sm:p-12">
        <p class="text-3xl font-bold leading-7 text-center">
          Связаться со мной
        </p>
        <form>
          <div class="md:flex items-center mt-12">
            <div class="w-full md:w-1/2 flex flex-col">
              <label class="font-semibold leading-none">Имя</label>
              <input v-model="name" type="text" name="name" class="leading-none text-gray-900 p-3 focus:outline-none focus:border-blue-500 mt-4 bg-gray-100 border rounded border-gray-200">
            </div>
            <div class="w-full md:w-1/2 flex flex-col md:ml-6 md:mt-0 mt-4">
              <label class="font-semibold leading-none">Телефон</label>
              <input v-model="phone" type="tel" name="tel" class="leading-none text-gray-900 p-3 focus:outline-none focus:border-blue-500 mt-4 bg-gray-100 border rounded border-gray-200">
            </div>
          </div>
          <div class="md:flex items-center mt-12">
            <div class="w-full md:w-1/2 flex flex-col">
              <label class="font-semibold leading-none">Email</label>
              <input v-model="mail" type="email" name="email" class="leading-none text-gray-900 p-3 focus:outline-none focus:border-blue-500 mt-4 bg-gray-100 border rounded border-gray-200">
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
          <div class="flex justify-center mt-6">
            <label class="flex items-center">
              <input type="checkbox" class="form-checkbox" required>
              <span class="ml-2">Я согласен с <a href="/"><span class="underline hover:text-blue-500 transition duration-300">политикой конфиденциальности</span></a></span>
            </label>
          </div>
          <div class="flex items-center justify-center w-full">
            <button
              class="mt-9 font-semibold leading-none text-white py-4 px-10 bg-blue-500 rounded hover:bg-blue-300 transition duration-300">
              Отправить
            </button>
          </div>
        </form>
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
      mail: '',
      message: '',
      company: ''
    }
  }
}
</script>

<style scoped>

</style>
