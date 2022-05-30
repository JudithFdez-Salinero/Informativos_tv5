<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-blue-500 static pt-20 px-10" >
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Estilo de animaciones</h1>
    </div>
    <Title 
    title="Animaciones destinadas a la web y el informativo"
    subtitle="Estos son los inputs, barras de navegación y los desplegables de la aplicación."
    />
    <p class="font-medium w-8/12">
      Estos elementos nos ayudarán en la creación de formularios, de las portadas y la reducción de información.
    </p>
    <div class="ejemplos mb-4 p-8  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md text-pink-500 ">PACK INFORMATIVO</h3>
      <p class=" px-4 w-8/12 mb-4">El planteamiento de las animaciones para la gráfica televisiva, 
        se fundamenta en el movimiento de la diagonal, inspirado en la inclinación de la letra ‘i’. Las transiciones suelen tener un movimiento lateral en la entrada de las manchetas de color y un leve delay en la entrada de texto junto con un sutil fade-in.
         En el caso de la cabecera, empleamos cortinillas diagonales para generar transiciones entre los videos de archivo. 
         También generamos un carrusel que nos permite mostrar los diferentes temas que se pueden tratar en un informativo.
          En cuanto a la doble pantalla, la imagen del presentador en el plató es dividida por la diagonal y de esta sale la conexión en directo o la noticia en cuestión.
          En cuanto a las animaciones de los logotipos, generamos una transición entre ellos para generar la marca responsive, a partir de una máscara que oculta marca principal y revela la más reducida. 
          Además sobre esta el cinco tiene un movimiento lateral y posteriormente ascendente colocándose como notificación.
          Para las secciones utilizamos una máscara que revela el bocadillo a partir de la versión son la notificación.</p>
        <div class="flex justify-start items-start flex-col px-4">
           <div class="flex flex-wrap justify-start items-start w-full">
              <div class=" mr-6 flex justify-center w-auto flex-col my-4 items-center p-4 border-4 border-blue-400 rounded-md">
                  <a class="font-bold" href="">Cabecera</a>
                  <img class="w-2/3 mr-4 mt-4"  src="../static/svg/Cabecera final (1).gif" alt="primera base"> 
              </div>
              <div class="mr-6 flex justify-center w-auto flex-col my-4 items-center p-4 border-4 border-blue-400 rounded-md">
                  <a class="font-bold" href="">Rotulos</a>
                  <img class="w-2/3 mr-4 mt-4"  src="../static/svg/ROTULOS MOVIMIENTO (1).gif" alt="primera base"> 
              </div>
              <div class="mr-6 flex justify-center w-auto flex-col my-4 items-center p-4 border-4 border-blue-400 rounded-md">
                  <a class="font-bold" href="">Doble pantalla</a>
                  <img class="w-2/3 mr-4 mt-4"  src="../static/svg/Doble pantalla (1).gif" alt="primera base">
              </div>
              <div class="mr-6 flex justify-center w-auto flex-col my-4 items-center p-4 border-4 border-blue-400 rounded-md">
                  <a class="font-bold" href="">Animación marca</a>
                  <img class="w-2/3 mr-4 mt-4"  src="../static/svg/SP3AU.Marca_variacion.gif" alt="primera base">
              </div>
              <div class="mr-6 flex justify-center w-auto flex-col my-4 items-center p-4 border-4 border-blue-400 rounded-md">
                  <a class="font-bold" href="">Animación marca sección</a>
                  <img class="w-2/3 mr-4 mt-4"  src="../static/svg/SP3AU.marca_DEPORTES_1 (1).gif" alt="primera base">
              </div>
           </div>
        </div> 
    </div>
    <div class="ejemplos mb-4 p-8  w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-60 rounded-md text-pink-500 ">WEB</h3>
      <p class=" px-4 w-8/12 mb-4">El estilo de las animaciones destinadas a la web, son sencillas. 
        El texto se desliza con el mismo patrón de movimiento diagonal, esta vez desde el margen derecho de la imagen, 
        sobre una mancheta en la que el logotipo aparece con la notificación.
        
        En el resto de animaciones, vemos como las manchetas se desplazan desde la izquierda, a través de la diagonal de la “i” 
        cobran dinamismo. En cuando a la doble pantalla observamos como la diagonal las enmarca primero y la conexión en directo 
        sale de la correspondiente al plató. Lo que las caracteriza globalmente es la lateralidad y la diagonalidad. Generando un mismo patrón dinámico para todas las aplicaciones. En cuanto a los logotipos, las animaciones se basan en el concepto de notificación, generando primero una máscara en los bocadillos por los que discurre la marca de la cadena, y colocándose como si esta fuera una alerta. </p>
        <div class="flex justify-start items-start flex-col px-4">
           <div class="flex flex-wrap justify-start items-start w-full">
              <div class=" mr-6 flex justify-center w-auto flex-col my-4 items-center p-4 border-4 border-blue-400 rounded-md">
                  <a class="font-bold" href="">Instagram 1080x1080</a>
                  <img class="w-2/3 mr-4 mt-4"  src="../static/svg/Insta cuadrado 1080x1080.gif" alt="primera base"> 
              </div>
              <div class="mr-6 flex justify-center w-auto flex-col my-4 items-center p-4 border-4 border-blue-400 rounded-md">
                  <a class="font-bold" href="">Instagram 1080x1350</a>
                  <img class="w-2/3 mr-4 mt-4"  src="../static/svg/Insta vertical 1080x1350 (1).gif" alt="primera base"> 
              </div>
              <div class="mr-6 flex justify-center w-auto flex-col my-4 items-center p-4 border-4 border-blue-400 rounded-md">
                  <a class="font-bold" href="">Facebook 1200x900</a>
                  <img class="w-2/3 mr-4 mt-4"  src="../static/svg/Facebook horizontal 1200x900.gif" alt="primera base">
              </div>
              <div class="mr-6 flex justify-center w-auto flex-col my-4 items-center p-4 border-4 border-blue-400 rounded-md">
                  <a class="font-bold" href="">Facebook 1200x1200</a>
                  <img class="w-2/3 mr-4 mt-4"  src="../static/svg/Facebook cuadrado 1200x1200 (1).gif" alt="primera base">
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