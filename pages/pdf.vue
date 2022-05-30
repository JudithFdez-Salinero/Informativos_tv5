<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
       <h1 class="text-5xl font-extrabold my-6 text-gray-900">La marca Informativos Telecinco</h1>
    <!-- header -->
    <GlobalHeader />
    <!--title-->
    <!-- <img class=" w-full mb-8  mr-6 z-0 absolute top-0 left-0 h-96" src="../static/svg/marca-cabeza-13.jpg" alt=""> -->

    <Title 
    title="Descarga el PDF directamente para ver el sistema"
    subtitle="Clickea en el enlace para descargar el archivo."
    />
    <p class="font-medium w-8/12">
     Aquí tienes un pequeño resumen del sistema.
    </p>
    <div class="flex justify-center w-auto flex-col my-4 items-center p-4 border-4 border-pink-500 rounded-md">
        <!-- <svg width="26" height="12" viewBox="0 0 26 12" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M25.1798 4.09003C25.2176 4.09003 25.2553 4.09003 25.293 4.09003L25.293 0.0102539C25.2553 0.0102539 25.2176 0.0102539 25.1798 0.0102539C18.732 0.0102536 13.453 4.94307 13.0006 11.2111C12.5858 4.98016 7.30684 0.0102531 0.821276 0.0102528C0.783569 0.0102528 0.745863 0.0102528 0.708157 0.0102528L0.708156 4.09003C0.745863 4.09003 0.783569 4.09003 0.821276 4.09003C5.27067 4.09003 8.85282 7.61347 8.85282 11.9899L13.0006 11.9899L13.076 11.9899L17.1483 11.9899C17.1483 7.61347 20.7304 4.09003 25.1798 4.09003Z" fill="#00CC66"/>
        </svg> -->

     <a class="font-bold" href="/static/documents/GA1_Marca_Informativos_TV5.pdf" download >Download</a>
    </div>
  </div>
</template>

<script>
import Title from "~/components/RepetedElements/Title.vue";
export default {
    components: { Title }
}
</script>

<style>

</style>