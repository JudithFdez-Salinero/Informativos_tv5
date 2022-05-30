<template>
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
       <h1 class="text-5xl font-extrabold my-6 text-gray-900">Atributos de la marca</h1>
    <!-- header -->
    <GlobalHeader />
    <!--title-->
    <Title 
    title=""
    subtitle="La marca es solo una pieza más del sistema, pero el lenguaje que en este se utiliza, pretende reflejar lo siguiente:"/>
    <div class="flex flex-wrap">
      <div class="flex flex-col mt-4 ">
        <p class="atribut text-lg font-medium p-8 rounded-lg m-2 text-white">Modernidad</p>
        <img class="w-48 ml-4 mr-4 rounded-lg mt-4"  src="../static/svg/modernidad.jpg" alt="primera base">
      </div>
      <div class="flex flex-col mt-4 ">
        <p class="atribut text-lg font-medium p-8 rounded-lg m-2 text-white">Inmediatez</p>
        <img class="w-48 ml-4 mr-4 rounded-lg mt-4"  src="../static/svg/inmediatez.jpg" alt="primera base">
      </div>
      <div class="flex flex-col mt-4 ">
        <p class="atribut text-lg font-medium p-8 rounded-lg m-2 text-white">Tecnología</p>
        <img class="object-cover object-center w-48 ml-4 mr-4 h-32 rounded-lg mt-4" src="../static/svg/tecnologia.jpg" alt="primera base">
      </div>
      <div class="flex flex-col mt-4 ">
        <p class="atribut text-lg font-medium p-8 rounded-lg m-2 text-white">Consistencia</p>
        <img class="w-48 h-32 ml-4 mr-4 rounded-lg object-cover object-center mt-4"  src="../static/svg/consistencia.jpg" alt="primera base">
      </div>
      <div class="flex flex-col mt-4 ">
        <p class="atribut text-lg font-medium p-8 rounded-lg m-2 text-white">Dinamismo</p>
        <img class="object-cover object-center w-48 ml-4 mr-4 h-32 rounded-lg mt-4"  src="../static/svg/dinamismo.jpg" alt="primera base">
      </div>
      <div class="flex flex-col mt-4 ">
        <p class="atribut text-lg font-medium p-8 rounded-lg m-2 text-white">Cercanía</p>
        <img class="object-cover object-center w-48 ml-4 mr-4 h-32 rounded-lg mt-4"  src="../static/svg/cercania.jpg" alt="primera base">
      </div>
      <p class="font-medium w-1/2 py-8 ml-4 mt-4 ">
      ¿Cómo reflejaríamos estos atributos? La modernidad a través del flat design, la inmediatez y la tecnología a partir de alusiones a las RRSS. La consistencia se  centra en el uso de una tipografía variable y el uso de la paleta cromática. Con el uso de la diagonal se representaría el dinamísmo, en cuanto a la cercanía se refiere esta también se vería apoyada en las alusiones a redes.
    </p>
    </div>
    
    
  </div>
</template>

<script>
import ButtonBase from '~/components/Dsys/ButtonBase.vue';
import Title from "~/components/RepetedElements/Title.vue";
export default {
    components: { ButtonBase, Title }
}
</script>

<style>
  .ul{
    display: flex;
    flex-direction: row;
  }
  .atribut{
    background-color: rgb(56 189 248);
  }
</style>