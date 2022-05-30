<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" w-full  mr-6 z-0 absolute top-0 left-0 h-96" src="../static/svg/duo tono 2.jpg" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Versiones en negativo</h1>
    </div>
    <Title 
    title="Aplicación de las versiones en negativo"
    subtitle="Normalmente están destinadas a soportes impresos."
    />
    <p class="font-medium w-8/12">
       Aunque también podrán utilizarse sobre las imágenes, facilitando su lectura.
    </p>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-pink-500 text-white">MARCA PRINCIPAL</h3>
       <div class="flex justify-start items-start flex-col">
           <img class="w-full  mr-4"  src="../static/svg/negativo.png" alt="primera base"> 
       </div>
    </div>
     <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-pink-500">MARCAS SECUNDARIAS</h3>
      <div class="flex justify-start items-start flex-row">
       <img class="w-96 mr-4"  src="../static/svg/negativo_i.png" alt="text-web">
       <img class="w-72 mr-4"  src="../static/svg/negativo_n.png" alt="text-web"> 
      </div>
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