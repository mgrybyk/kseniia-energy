<script setup lang="ts"></script>

<template>
  <h1>Ксения Крутенко - Энерготерапевт</h1>
  <div class="flex flex-wrap-reverse md:flex-nowrap">
    <div class="about mr-5 p-2">
      <section class="mb-10">
        <h2>Я это Я</h2>
        <p>Делаю что делаю</p>
      </section>

      <section class="mb-10">
        <h3>Медитации</h3>
        <p>Более подробно и посмотреть рассписание можно в моём телеграм канале:</p>
        <div>
          <a
            tabindex="0"
            href="https://t.me/blessing936energy"
            target="_blank"
            rel="noopener"
            class="social-button mb-2 mr-2 inline-block rounded-3xl px-2 py-1 leading-10 text-white shadow-md transition duration-150 ease-in-out active:shadow-lg focus:shadow-lg hover:shadow-lg focus:outline-none focus:ring-0"
            style="background-color: #0088cc"
          >
            <span class="i-fa6-brands:telegram"></span>
            <span>t.me/blessing936energy</span>
          </a>

          <!-- Youtube -->
          <a
            class="social-button disabled mb-2 mr-2 inline-block select-none rounded-3xl px-2 py-1 leading-10 text-white shadow-md transition duration-150 ease-in-out active:shadow-lg focus:shadow-lg hover:shadow-lg focus:outline-none focus:ring-0"
            style="background-color: #666666"
          >
            <span class="i-fa6-brands:youtube"></span>
            <span>Скоро будет!</span>
          </a>
        </div>
      </section>

      <section class="inmb-10dividual">
        <h3>Индивидуальные сессии</h3>
        <p>Записаться:</p>
        <p>
          <!-- Telegram Button -->
          <a
            tabindex="0"
            href="https://t.me/blessing936"
            target="_blank"
            rel="noopener"
            class="social-button mb-2 mr-2 inline-block rounded-3xl px-2 py-1 leading-10 text-white shadow-md transition duration-250 ease-in-out focus:shadow-xl hover:shadow-xl hover:ring-1 hover:ring-inset hover:saturate-120"
            style="background-color: #0088cc"
          >
            <span class="i-fa6-brands:telegram"></span>
            <span>@blessing936</span>
          </a>

          <!-- Instagram Button -->
          <a
            tabindex="0"
            href="https://www.instagram.com/ksu_cosmicgirl"
            target="_blank"
            rel="noopener"
            class="social-button mb-2 mr-2 inline-block rounded-3xl px-2 py-1 leading-10 text-white shadow-md transition-all duration-150 ease-in-out focus:shadow-xl hover:shadow-xl hover:ring-1 hover:ring-inset"
            style="background-color: #c13584"
          >
            <span class="i-fa6-brands:instagram"></span>
            <span>ksu_cosmicgirl</span>
          </a>

          <!-- Facebook Button -->
          <a
            tabindex="0"
            href="https://www.facebook.com/KseniyaKrutenko"
            target="_blank"
            rel="noopener"
            class="social-button mb-2 mr-2 inline-block rounded-3xl px-2 py-1 leading-10 text-white shadow-md transition-all duration-150 ease-in-out focus:shadow-xl hover:shadow-xl hover:ring-1 hover:ring-inset"
            style="background-color: #1877f2"
          >
            <span class="i-fa6-brands:facebook"></span>
            <span>KseniyaKrutenko</span>
          </a>
        </p>
      </section>
    </div>
    <img
      src="/img/kseniia.png"
      class="profile-img p2 md:-mt-4"
      alt="Ксения Крутенко"
      width="177"
      height="300"
    />
  </div>
</template>

<style scoped lang="css">
div.flex {
  font-family: Arial, Helvetica, sans-serif;
}
.social-button {
  white-space: nowrap;
  font-size: 1rem;
  text-decoration: none;
}
.social-button span {
  margin-right: 0.5rem;
  margin-bottom: 0.1rem;
  width: 2rem;
  height: 2rem;
}

[class*='hover:']:not(.disabled) {
  cursor: pointer;
}

[class*='hover:'].disabled {
  cursor: not-allowed;
}
</style>
