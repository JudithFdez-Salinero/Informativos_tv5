<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <!-- header -->
    <GlobalHeader/>
    <!--title-->
    <div class="w-full h-96 bg-gray-900 static pt-14  px-10" >
        <h1 class="z-10 absolute top-64 left-12 text-5xl font-extrabold my-4 text-white">Estilo de imágenes</h1>
    </div>
    <Title 
    title="Imageniería"
    subtitle="Estas son las imágenes que proponemos y su tratamiento."
    />
    <div class="ejemplos my-4 p-8 w-full">
      <p class="">
        Con el fin de darle mayor personalidad a las imágenes se les aplicará un filtro con los colores corporativos PANTONE 2202 XGC y PANTONE P 68-8C. 
        Aunque podría variar aplicándose el resto de la gama y paleta cromática. Las imágenes pretenden reflejar la realidad, si bien es cierto intentamos que el plano sea americano, pues los sujetos son más visibles a la cámara.
      </p>
      <div class="flex flex-row mb-20">
        <div class="flex flex-col w-96 mr-20 ">
          <h3 class="mt-8 text-lg font-medium text-blue-500">MONOCROMO B/N</h3>
          <p class="text-base">
            Se aplicarán a la cabecera, con la intención de que estas no compitan cromáticamente entre sí y unificar la gráfica.
          </p>
        </div>
        <div class="flex flex-row ">
          <img class="w-42 mr-4 mt-16 w-80"  src="../static/svg/pexels-pixabay-87772.jpg" alt="primera base">
          <img class="w-42 mr-4 mt-16 w-80"  src="../static/svg/pexels-mentatdgt-1185433.jpg" alt="primera base">
        </div>
      </div>
      <div class="flex flex-row mb-20">
        <div class="flex flex-col w-96 mr-20 ">
          <h3 class="mt-8 text-lg font-medium text-blue-500">DUOTONO</h3>
          <p class="text-base">
            Serán las que más se utilicen en la Web esencialmente.
          </p>
        </div>
        <div class="flex flex-row ">
          <img class="w-42 mr-4 mt-16 w-80"  src="../static/svg/doutono48.jpg" alt="primera base">
          <img class="w-42 mr-4 mt-16 w-80"  src="../static/svg/duotono 3.jpg" alt="primera base">
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