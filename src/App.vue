<template>
  <div id="root" class="text-white text-center">
    <div id="projects" class="flex py-20 flex-col items-center justify-center">
      <h1 class="text-3xl">Projects</h1>
      <div class="flex flex-col items-center justify-center gap-10 pt-10">
        <WcButton btitle="Number Game" @click="golink('https://vue-random-number.vercel.app/')">
          Number Game
        </WcButton>

        <WcButton btitle="Pasword Generator" @click="golink('https://vue-password-creater.vercel.app/')">
          Pasword Generator
        </WcButton>

        <WcButton btitle="Weather App" @click="golink('https://vue-weather-app-omega.vercel.app/')">
          Weather App
        </WcButton>

        <WcButton btitle="Quiz App" @click="golink('https://mon-quiz-app.vercel.app/')">
          Quiz App
        </WcButton>

        <WcButton btitle="Admin Panel" @click="golink('https://admin-panel-two-zeta.vercel.app/#/')">
          Basic Admin Panel
        </WcButton>
      </div>
    </div>
  </div>
</template>

<script setup>
import WcButton from '@/comp/WcB.vue'
function golink(link) {
  window.open(link)
}
</script>


<style>
body {
  background-color: rgba(0, 0, 0, 0.795);
}
</style>