<script setup></script>

<template>
  <section class="overflow-hidden bg-gray-50 sm:grid sm:grid-cols-2">
    <img alt="vue" src="/Vue.jpg" class="sm:hidden block h-56 w-full object-cover sm:h-full" />
    <div class="p-8 md:p-12 lg:px-16 lg:py-24">
      <div class="mx-auto max-w-xl text-center ltr:sm:text-left rtl:sm:text-right">
        <h2 class="text-2xl font-bold text-gray-900 md:text-3xl">Проекты на Vue</h2>

        <p class="text-gray-500 md:mt-4 md:block">
          Тут вы можете собственноручно опробовать 2 моих сайта, написанных на Vue. Первый это
          интернет-магазин косметики. Второй - сайт для организации спортивных мероприятий, будь то
          соревнования или просто товарищеские игры.<br />
          P.s. сайты со временем дорабатываются и являются лишь pet-проектами, т.е. не для
          коммерческого использования.
        </p>

        <div class="xl:flex xl:justify-between">
          <div class="mt-4 md:mt-8">
            <a
              href="https://markezz-pet-vue-cosmetics-store.netlify.app/"
              class="w-60 inline-block rounded bg-emerald-600 px-12 py-3 text-sm font-medium text-white transition hover:bg-emerald-700 focus:outline-none focus:ring focus:ring-yellow-400"
            >
              Интернет-магазин
            </a>
          </div>
          <div class="mt-4 md:mt-8">
            <a
              href="https://markezz-pet-vue-sports-meetings.netlify.app/"
              class="w-60 inline-block rounded bg-emerald-600 px-4 py-3 text-sm font-medium text-white transition hover:bg-emerald-700 focus:outline-none focus:ring focus:ring-yellow-400"
            >
              Спортивные мероприятия
            </a>
          </div>
        </div>
      </div>
    </div>

    <img alt="vue" src="/Vue.jpg" class="sm:block hidden h-56 w-full object-cover sm:h-full" />
  </section>
</template>
