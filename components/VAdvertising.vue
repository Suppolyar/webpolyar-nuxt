<template>
  <div class="container mx-auto px-4">
    <div class="flex flex-col-reverse md:grid grid-cols-3 gap-x-4 mb-8">
      <div class="col-span-2 text-xl p-4">
        <div class="bg-white rounded-xl shadow-xl p-4">
          <p>
            Маленькая мечта каждого взрослого человека - понемногу делать этот мир добрее и лучше. <br><br>
            Большой мечтой маленькой собаки на фотографии было найти свой дом и свою семью. А нам очень хотелось завести
            питомца, который будет бегать по пятам, счастливо лаять каждый раз, когда мы приходим домой, дарить нам
            радость и давать возможность заботиться и делиться теплотой.
            <br><br>
            Мы случайно увидели Касси на сайте <a href="https://www.friendforpet.ru/" target="_blank"><span
              class="transition duration-300 text-red-500 hover:text-red-700"
            >Purina</span></a> (компания Nestle) и тут же в нее влюбились. Проект "Друг для друга" помогает людям и животным
            из приютов найти друг друга и стать друзьями на всю жизнь.
            Касси нашли в лесу совсем маленькой, но ей очень повезло, - она попала в добрые руки кураторов проекта и
            смогла найти свою семью. И я счастлив, что смог стать для нее настоящим другом.
            <br><br>
            Давайте делать добрые дела, как можно чаще! <br><br>
            И помните, что домашние питомцы для нас - страница жизни, а мы для них - вся жизнь.
          </p>
          <div class="h-40 w-40 flex flex-row items-center">
            <img class="w-full" src="@/static/purina.svg" alt="purina">
            <span class="text-2xl text-red-700">PURINA</span>
          </div>
        </div>
      </div>
      <div class="w-full mb-4 col-span-1 p-4">
        <img class="rounded-2xl shadow w-full sm:mx-0 mx-auto sm:mx-none" src="@/static/dog_photo.jpg">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'VAdvertising'
}
</script>

<style scoped>

</style>
