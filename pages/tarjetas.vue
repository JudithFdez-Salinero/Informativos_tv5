<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" w-full  mr-6 z-0 absolute top-0 left-0 h-96" src="../static/svg/duo tono 2.jpg" alt="">
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Área de respeto</h1>
    </div>
    <Title 
    title="Este es el área de reserva que no se puede invadir salvo en concretas excepciones."
    subtitle="Explicamos como se conforman."
    />
    <p class="font-medium w-8/12">
      De la misma forma se toma como referencia la medida de la 'i' para todas sus versiones, en los únicos usos que se puede invadir este espacio es en las transiciones o si tienen un fin concretamente estético para la producción audiovisual, que no impresa.
    </p>
    <div class="ejemplos my-8 p-8 bg-gray-500  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-pink-500 text-white">MARCA PRINCIPAL</h3>
      <div class="flex flex-col">
        <p class=" w-8/12 mb-4 text-white">Se toma como referencia la altura de la 'i'. </p>
        <img class="w-2/3 mr-8"  src="../static/svg/espacio_respeto.png" alt="primera base">
      </div>
    </div>
     <div class="ejemplos mb-4 p-8 bg-gray-200  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md bg-blue-400 text-white">MARCAS SECUNDARIAS</h3>
      <p class=" w-8/12 mb-4"></p>
      <div class="flex flex-row mt-8">
        <img class="w-72 mr-8"  src="../static/svg/espacio_respeto_info.png" alt="primera base">  
        <img class="w-48 mr-8"  src="../static/svg/espacio_respeto_not.png" alt="primera base">
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