<template>
  <header class="fixed top-0 left-0 bottom-0 p-4 pt-6">
    <div class="logo flex items-center justify-between  mb-8">
      <img class="my-1 mx-2 h-auto w-12"  src="../../static/svg/Recurso 10.svg" alt="logo">
      <h2 class="mx-4 text-white text-xl font-bold leading-5">MANUAL INFORMATIVOS TELECINCO</h2>
    </div>
    <div class="navigation mx-2">
      <nav class="vertical_menu text-gray-300">
        <ul class="empezamos">
          <h3 class="text-lg font-bold text-blue-300 mt-2 ">Definición y concepto de la marca</h3>
          <li><nuxt-link class="navbar-item " to="/">Identidad de Informativos Telecinco</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="figma">Atributos de la marca</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="pdf">La marca Informativos Telecinco</nuxt-link></li>
        </ul>
        <ul class="basics">
          <h3 class="text-lg font-bold text-blue-300 mt-2 ">La marca</h3>
          <li><nuxt-link class="navbar-item " to="logotipo">Configuración y estados de la marca</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="layout">Construcción y espacio de la marca</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="tarjetas">Área de respeto </nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="images">Versiones en Negativo</nuxt-link></li>
        </ul>
        <ul class="reticulas">
          <h3 class="text-lg font-bold text-blue-300 mt-2 ">Sistema de Identidad Visual de marca</h3>
          <li><nuxt-link class="navbar-item " to="tipografia">La tipografía corporativa</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="paleta">Los colores corporativos</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="aplicacionesreticula">El estilo de imagen</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="reticulas">Estructura</nuxt-link></li>
          <li><nuxt-link class="navbar-item " to="inputs">Estilo de animaciones</nuxt-link></li>
        </ul>
        <ul class="web">
          <h3 class="text-lg font-bold text-blue-300 mt-2 ">Aplicaciones</h3>
          <li><nuxt-link class="navbar-item " to="iconos">Pack gráfico</nuxt-link></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="postcss" scoped>
header {
  width: 16rem;
  background-color: #002c35;
}
</style>