<script setup lang="ts">
import { ref } from 'vue'
</script>

<template>
  <div class="flex flex-wrap">
    <div class="about mr-5 p-2">
      <h1>Ксения Крутенко - Энерготерапевт</h1>
      <section class="mb-10">
        <h2>Я это Я</h2>
        <p>Делаю что делаю</p>
      </section>

      <section class="mb-10">
        <h3>Медитации</h3>
        <p>Более подробно и посмотреть рассписание можно в моём телеграм канале:</p>
        <div>
          <a
            tabindex="1"
            href="https://t.me/@telegram_channel"
            target="_blank"
            rel="noopener"
            class="social-button mr-2 inline-block rounded px-2 py-1 leading-10 text-white shadow-md transition duration-150 ease-in-out active:shadow-lg focus:shadow-lg hover:shadow-lg focus:outline-none focus:ring-0"
            style="background-color: #0088cc"
          >
            <span class="i-fa6-brands:telegram"></span>
            @telegram_channel
          </a>

          <!-- Youtube -->
          <a
            href="about:blank"
            target="_blank"
            rel="noopener"
            class="disabled social-button mr-2 inline-block rounded px-2 py-1 leading-10 text-white shadow-md transition duration-150 ease-in-out active:shadow-lg focus:shadow-lg hover:shadow-lg focus:outline-none focus:ring-0"
            style="background-color: #ff0000"
          >
            <span class="i-fa6-brands:youtube"></span>
            Скоро будет!
          </a>
        </div>
      </section>

      <section class="inmb-10dividual">
        <h3>Индивидуальные сессии</h3>
        <!-- <p>Записаться:</p> -->
        <p>
          <!-- Telegram Button -->
          <a
            tabindex="2"
            href="https://t.me/@blessing936"
            target="_blank"
            rel="noopener"
            class="social-button mr-2 inline-block rounded px-2 py-1 leading-10 text-white shadow-md transition duration-250 ease-in-out focus:shadow-xl hover:shadow-xl hover:ring-1 hover:ring-inset hover:saturate-120"
            style="background-color: #0088cc"
          >
            <span class="i-fa6-brands:telegram"></span>
            @blessing936
          </a>

          <!-- Instagram Button -->
          <a
            tabindex="3"
            href="https://www.instagram.com/todo"
            target="_blank"
            rel="noopener"
            class="social-button mr-2 inline-block rounded px-2 py-1 leading-10 text-white shadow-md transition-all duration-150 ease-in-out focus:shadow-xl hover:shadow-xl hover:ring-1 hover:ring-inset"
            style="background-color: #c13584"
          >
            <span class="i-fa6-brands:instagram"></span>
            @todo
          </a>
        </p>
      </section>
    </div>
    <img src="/img/kseniia.png" class="profile-img p2" />
  </div>
</template>

<style scoped lang="css">
div.flex {
  font-family: Arial, Helvetica, sans-serif;
}
img.profile-img {
  width: 300px;
}
.social-button {
  font-size: 1rem;
  /* display: block; */
  text-decoration: none;
}
.social-button span {
  margin-right: 0.5rem;
  width: 2rem;
  height: 2rem;
}

[class*='hover:']:not(.disabled) {
  cursor: pointer;
}

[class*='hover:'].disabled {
  cursor: not-allowed;
  opacity: 0.5;
}
</style>
