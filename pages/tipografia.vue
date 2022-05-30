<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-20 px-10" >
        <img class=" mr-6 z-0 absolute h-64 t-0 l-0 " src="../static/svg/Recurso 11.svg" alt="">
        <h1 class="z-10 absolute top-64 left-2/4 text-5xl font-extrabold my-4 text-white">Tipografía</h1>
    </div>
    <Title 
    title="Esta es la guía de tipografía"
    subtitle="Puedes encontrar los distintos niveles tipográficos a la identidad. Tambien podrás encontrar enlaces de descarga a los archivos ttf."
    />
    <p class="font-medium w-8/12 mt-4">
        Búscamos una tipografía con carácter y dinamismo, consistente y variable en cuanto a su peso. 
        Además uno de sus rasgos fundamentales es que sus formas son amables a la par que legibles, algo de suma relevancia teniendo en cuenta el soporte al que se destina primordialmente.
        La tipografía corporativa será Ubuntu. Esta es una familia tipográfica sans-serif, ha sido desarrollada por la empresa Dalton Maag, con patrocinio de Canonical Ldt en 2010.
        Tiene un estilo contemporáneo y contiene características únicas, transmiten una actitud precisa, confiable y libre. Fue diseñada para la interfaz del sistema operativo Ubuntu y esta refuerza el atributo de tecnología que se pretende representar. La tipografía está liberada bajo la licencia Ubuntu Font Licence, que está basada en la SIL Open Font License. 
        Esta licencia es copyleft, y permite que las tipografías sean «usadas, estudiadas, modificadas y redistribuidas libremente» cumpliendo los términos estipulados en ella. 
    </p>
    <div class="logotipo my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md text-pink-500">TIPOGRAFÍA</h3>
      <p class=" w-8/12 mb-4">Puedes descargar la tipografía y probarla.</p> 
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
          <a class="font-bold text-gray-900" href="/static/types/Ubuntu-bold.ttf" download>Ubuntu Bold</a>
          <img class="w-8" src="../static/svg/Rectangle.svg" alt="">
      </div>
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
        <a class="font-bold text-gray-900" href="/static/types/Ubuntu-BoldItalic.ttf" download>Ubuntu Bold Italic</a>
        <img class="w-8" src="../static/svg/Rectangle.svg" alt="">
      </div>
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
        <a class="font-bold text-gray-900" href="/static/types/Ubuntu-Medium.ttf" download>Ubuntu Medium</a>
        <img class="w-8" src="../static/svg/Rectangle.svg" alt="">
      </div>
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
        <a class="font-bold text-gray-900" href="/static/types/Ubuntu-MediumItalic.ttf" download>Ubuntu Medium Italic</a>
        <img class="w-8" src="../static/svg/Rectangle.svg" alt="">
      </div>
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
        <a class="font-bold text-gray-900" href="/static/types/Ubuntu-Regular.ttf" download>Ubuntu Regular</a>
        <img class="w-8" src="../static/svg/Rectangle.svg" alt="">
      </div>
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
        <a class="font-bold text-gray-900" href="/static/types/Ubuntu-RegularItalic.ttf" download>Ubuntu Regular Italic</a>
        <img class="w-8" src="../static/svg/Rectangle.svg" alt="">
      </div>
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
        <a class="font-bold text-gray-900" href="/static/types/Ubuntu-Light.ttf" download>Ubuntu Light</a>
        <img class="w-8" src="../static/svg/Rectangle.svg" alt="">
      </div>
      <div class="bg-gray-200 w-full h-auto p-8 my-4 flex justify-between items-center">
        <a class="font-bold text-gray-900" href="/static/types/Ubuntu-LightItalic.ttf" download>Ubuntu Light Italic</a>
        <img class="w-8" src="../static/svg/Rectangle.svg" alt="">
      </div>
        
    </div>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
         <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-pink-500 text-white">ESTILOS PARA EL INFORMATIVO</h3>
         <p class=" w-8/12 mb-4">Estos son los tamaños y espaciados para el display televisivo, que se aplicarán a los diferentes sobreimpresiones y rtulos.</p>  
       <div class="flex justify-start items-start flex-col">
           <img class="w-2/3  mr-4"  src="../static/svg/Recurso 17.svg" alt="text-web"> 
       </div>
    </div>
    <div class="ejemplos my-4 p-8 bg-gray-100 w-full">
     <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md bg-blue-400 text-white">ESTILOS PARA WEB</h3>
     <p class=" w-8/12 mb-4">Estos son los tamaños y espaciados para la móvil, que se aplicarán a los diferentes elementos de las páginas</p>
     <div class="flex justify-start items-start flex-col">
         <img class="w-1/2 mr-4"  src="../static/svg/Recurso 19.svg" alt="text-web"> 
     </div>
    </div>
    <div class="ejemplos my-4 p-8 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-120 rounded-md text-pink-500">EJEMPLOS DE APLICACIÓN</h3>
      <p class=" w-8/12 mb-4">A continuación se muestran los estilos que se utilizan en el display televisivo e imágenes destinadas redes sociales, aplicables a su vez a la web de Informativos Telecinco.</p>
       <div class="flex justify-start items-start flex-row mt-10">
      <img class="w-8/12 mr-4"  src="../static/svg/ejemplo_aplicacion.png" alt="text-web">
      <img class="w-96 mr-4"  src="../static/svg/Recurso 3.png" alt="text-web">  
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