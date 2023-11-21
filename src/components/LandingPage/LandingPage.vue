<script setup lang="ts"></script>

<template>
  <h1>Ксения Крутенко - Энерготерапевт</h1>
  <div class="flex flex-wrap-reverse">
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
            class="social-button mb-2 mr-2 inline-block rounded-md px-2 py-1 leading-10 text-white shadow-md transition duration-150 ease-in-out active:shadow-lg focus:shadow-lg hover:shadow-lg focus:outline-none focus:ring-0"
            style="background-color: #0088cc"
          >
            <span class="i-fa6-brands:telegram"></span>
            <span>@blessing936energy</span>
          </a>

          <!-- Youtube -->
          <a
            class="social-button disabled mb-2 mr-2 inline-block select-none rounded-md px-2 py-1 leading-10 text-white shadow-md transition duration-150 ease-in-out active:shadow-lg focus:shadow-lg hover:shadow-lg focus:outline-none focus:ring-0"
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
            class="social-button mb-2 mr-2 inline-block rounded-md px-2 py-1 leading-10 text-white shadow-md transition duration-250 ease-in-out focus:shadow-xl hover:shadow-xl hover:ring-1 hover:ring-inset hover:saturate-120"
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
            class="social-button mb-2 mr-2 inline-block rounded-md px-2 py-1 leading-10 text-white shadow-md transition-all duration-150 ease-in-out focus:shadow-xl hover:shadow-xl hover:ring-1 hover:ring-inset"
            style="background-color: #c13584"
          >
            <span class="i-fa6-brands:instagram"></span>
            <span>@ksu_cosmicgirl</span>
          </a>
        </p>
      </section>
    </div>
    <img
      src="/img/kseniia.png"
      class="profile-img p2"
      alt="Ксения Крутенко"
      width="300"
      height="507"
    />
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
}
</style>
