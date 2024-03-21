<script setup></script>

<template>
  <section class="overflow-hidden bg-gray-50 sm:grid sm:grid-cols-2">
    <img alt="react" src="/react.jpg" class="h-56 w-full object-cover sm:h-full" />
    <div class="p-8 md:p-12 lg:px-16 lg:py-24">
      <div class="mx-auto max-w-xl text-center ltr:sm:text-left rtl:sm:text-right">
        <h2 class="text-2xl font-bold text-gray-900 md:text-3xl">Проекты на React</h2>
        <p class="text-gray-500 md:mt-4 md:block">
          Проекты представлены в видео , приятного просмотра 🙂
        </p>
        <!-- <video class="mt-2" controls>
          <source src="/video.mp4" type="video/mp4" />
        </video> -->
        <br />
        <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/oeviI6FvDzg?si=F-aimv8hNaMMAgU0"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          referrerpolicy="strict-origin-when-cross-origin"
          allowfullscreen
        ></iframe>
        <p class="text-gray-500 mt-2 md:mt-4 md:block">Исходный код на GitHub</p>
        <div class="xl:flex xl:justify-between">
          <div class="mt-4 md:mt-8">
            <a
              href="https://github.com/Marakezz/TicTacToe"
              class="w-56 inline-block rounded bg-emerald-600 py-3 text-sm font-medium text-white transition hover:bg-emerald-700 focus:outline-none focus:ring focus:ring-yellow-400"
            >
              Крестики-нолики
            </a>
          </div>
          <div class="mt-4 md:mt-8">
            <a
              href="https://github.com/Marakezz/Simple-Clicker-node.js-socket.io-React-"
              class="w-56 inline-block rounded bg-emerald-600 py-3 text-sm font-medium text-white transition hover:bg-emerald-700 focus:outline-none focus:ring focus:ring-yellow-400"
            >
              Кликер
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
