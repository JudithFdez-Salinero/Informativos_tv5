<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-14  px-10" >
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Estructura</h1>
    </div>
    <Title 
    title="Estructuras constructivas"
    subtitle="En este caso, mostramos los diferentes 
    estructuras constructivas que hemos aplicado tanto a soportes audiovisuales como los destinados a aplicaciones web."
    />
    <div class="ejemplos my-2 p-4 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-pink-600">LAYOUT (16:9)</h3>
      <p class=" px-4 w-8/12 mb-4"> La lógica en la que se basa su construcción es la relación con la “i”. 
        La proporción se basa en la altura de la ‘’i’ ya que todo el sistema gira en torno a su diagonal. 
        En este caso hablamos de 30 filas y 20 columnas. Esta estructura tendrá en cuenta las diferentes resoluciones de pantalla, pues su área de seguridad permite que esta pueda adaptarse a los diferentes dispositivos. De tal forma que se respete el espacio visible y no se invada una zona en la que pueda perderse información de un dispositivo a otro.
        El área de seguridad tiene una altura de 90 px y un ancho de 160 px (pixeles relativos). </p>
       <div class="px-4 flex justify-start items-start flex-col">
           <img class="w-2/3 mr-4 mt-4"  src="../static/svg/estructura_1.png" alt="primera base"> 
       </div>
    </div>
    <div class="px-4 my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-80 rounded-md text-pink-600">ESTRUCTURA PARA APLICACIONES</h3>
      <p class="mr-2 ml-4 w-2/3 mb-8 text-lg font-medium">La relación que se da,
         en la construción de la estructura es la proporción del cuadrado en función de las dimensiones del soporte.</p>
      <div class="flex flex-row">
         <!--FACE-->
        <div class="flex flex-column">
          <div class="flex flex-row">
            <div class="flex flex-col mr-4">
              <h3 class="mr-2 ml-4 font-medium text-lg">Facebook</h3>
              <p class="mr-2 ml-4 w-40">La estructura se divide en 9 columnas y 9 filas (formato cuadrado) y en cuanto a su formato horizontal, 12 columnas por 9 filas.</p>
            </div>
            <div class="flex flex-col">
              <img class="w-2/3 mr-4 mb-4"  src="../static/svg/facebook1_Facebook.png" alt="primera base">
              <img class="w-2/3 mr-4"  src="../static/svg/facebook2-12.png" alt="primera base">
            </div> 
          </div>
        </div>
        <!--INSTA-->
        <div class="flex flex-column">
          <div class="flex flex-row">
            <div class="flex flex-col mr-4">
              <h3 class="ml-4 font-medium text-lg">Instagram</h3>
              <p class="mr-4 ml-4 w-40">La estructura se divide en 10 columnas y 10 filas en su formato cuadrado y 12 columnas por 15 filas en el formato vertical.</p>
            </div>
            <div class="flex flex-col">
              <img class="w-3/4 mr-4 mb-4"  src="../static/svg/insta_cuadrado_Insta_cuadrado.png" alt="primera base">
              <img class="w-3/4 mr-4"  src="../static/svg/insta_vertical_Insta_vertical.png" alt="primera base">
            </div> 
          </div>
        </div>
        
      </div>
      <div class="flex flex-row">
        <!--TWITTER-->
        <div class="px-4 flex flex-column mt-20">
          <div class="flex flex-row">
            <div class="flex flex-col mr-4">
              <h3 class="mr-8 ml-4 font-medium text-lg">Twitter</h3>
              <p class="mr-4 ml-4 w-40">La estructura se divide en 8 columnas y 4 filas.</p>
            </div>
            <div class="flex flex-col">
              <img class="w-2/3 mr-4"  src="../static/svg/twitte_twitter.png" alt="primera base">
            </div> 
          </div>
        </div>
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