<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <main>
    <div class="banner">
      <img src="/src/assets/MinhaNuvemBanner.jpg">
    </div>
    <div class="banner-text">
      <h1> Somos minha nuvem</h1>
      </div>
    <div class="resume">
      <p> Somos uma empresa focada em desenvolvimento de software, assistência técnica e manutenção de uma infraestrura de TI para micro e pequenas empresas</p>
      <br>
      <p> Fazemos backup seguro em um cofre virtual, criptografado e isolado </p>
      <br>
      <p> Centralizamos todo o seu negócio em uma interface simples e descomplicada, desde pedidos,
      finanças, monitoria, documentos até a rotina diária da empresa </p>
    </div>
  </main>
</template>

<style scoped>
.banner img{
  object-fit: cover;
  height: auto;
}
.banner-text{
  text-align: center;
  text-shadow: 2px;
  font-weight: bold;
  justify-content: center;
}
.resume{
  font-size: 16px;
  text-align: left;
  margin: 4px;
  padding: 10px;
  justify-content: center;
}
</style>
