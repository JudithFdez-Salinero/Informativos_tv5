<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-pink-600 static pt-20 px-10" >
        <img class=" w-full h-80 mr-6 z-0 absolute top-8 left-0 opacity-50" src="../static/svg/Recurso 73.svg" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Construcción y espacio de la marca</h1>
    </div>
    <Title 
    title="Aquí verás como se forma la estructura de la marca"
    subtitle="El tamaño o proporción de referencia para la construcción de las marcas es la proporción de la ‘i’."
    />
    <p class="font-medium w-8/12 mt-2">
        La relación entre los componentes se dará a partir de una estructura en la que sus módulos son cuadrados donde la letra (i) queda enmarcada.
    </p>
    <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4  rounded-md text-blue-400">CONSTRUCCIÓN DE LA MARCA PRINCIPAL</h3>
      <p class=" w-8/12 mb-4">Esta sería la base de la que hemos hablado.</p>
       <div class="flex justify-start items-start flex-col">
           <img class="w-2/3  mr-4"  src="../static/svg/estructura_logo_p.png" alt="primera base"> 
       </div>
    </div>
     <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-64 rounded-md bg-pink-500 text-white">CONSTRUCCIÓN DE MARCAS SECUNDARIAS</h3>
      <p class=" w-8/12 mb-8">Progresivamente vemos como se forman las diferentes marcas a partir del mismo módulo. 
        Es más se puede apreciar como la tipografía tiene exactamente la misma posición en todas ellas.
      </p>

      <div class="grid grid-cols-2">
        <img class="w-72 mr-4 mb-4 h-auto"  src="../static/svg/estructura_logo_info.png" alt="text-web">
        <img class="w-52 mr-4 mb-4"  src="../static/svg/estructura_logo_not.png" alt="text-web">
        <img class="w-96 mr-4 mt-4"  src="../static/svg/seccion_estructura.png" alt="text-web">
        <img class="w-96 mr-4 mt-4"  src="../static/svg/seccion_estructura_2.png" alt="text-web">
      </div>
       <!-- <div class="flex justify-start items-baseline flex-col">
         <div class="flex flex-row ">
            <img class="w-80 mr-4 mb-4 h-auto"  src="../static/svg/estructura_logo_info.png" alt="text-web">
            <img class="w-64 mr-4 mb-4"  src="../static/svg/estructura_logo_not.png" alt="text-web">
         </div>
         <div class="flex flex-row">
           <img class="w-64 mr-4"  src="../static/svg/seccion_estructura.png" alt="text-web">
           <img class="w-64 mr-4"  src="../static/svg/seccion_estructura_2.png" alt="text-web">
         </div>
        </div> -->
  </div>
</div>

</template>

<script>
import ButtonBase from "~/components/Dsys/ButtonBase.vue";
import Title from "~/components/RepetedElements/Title.vue";
export default {
  components: { ButtonBase, Title },
};
</script>

<style>
</style>