<script setup>
import TheWelcome from '@/components/TheWelcome.vue'
</script>

<template>
  <main>
    <TheWelcome />
    <div class="sosial-media">
        <li><a href=""><img src="@/assets/instagram.svg" alt=""></a></li>
        <li><a href=""><img src="@/assets/facebook.svg" alt=""></a></li>
        <li><a href=""><img src="@/assets/github.svg" alt=""></a></li>
      </div>
  </main>
</template>

<style scoped>
.sosial-media li{
  list-style: none;
  padding-bottom: 2rem;
}
.sosial-media img{ 
  width: 40px;
  top: -13rem;
  left: 5rem;
  position: relative;
  border: 1px solid rgb(115, 241, 115);
  border-radius: 3rem;
  padding: 4px;
}
.sosial-media img:hover {
  transform: rotate(20deg);
  scale: 1.4;
  transition: .6s;
}
</style>