<template class="">
  <div class="index max-w-6xl w-auto relative left-80 top-10 flex flex-col justify-start items-start ">
    <h1 class="text-5xl font-extrabold my-8 text-gray-900">Identidad de Informativos Telecinco</h1>
    <!-- header -->
    <GlobalHeader />
    <!--title-->
    <img src="../static/svg/Recurso 9.svg" alt="">
    
    <Title 
    title="Bienvenido a Informativos Telecinco Manual"
    subtitle="Aquí encontrarás todo lo que necesitas saber sobre nuestro rediseño."
    />
    <p class="font-medium w-8/12 mt-2">
      En este manual encontrarás todo lo que necesitas saber sobre el rediseño de la marca. Dedidado a la identidad visual de Informativos Telecinco un tele informativo que dedica su actividad a la información periodística, debe tener las siguientes características:
    </p>
    <div class="inicio my-4 p-8 bg-gray-200 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-90 rounded-md bg-pink-600 text-white">Transmitir veracidad y ser informativa.</h3>
      <p class=" w-8/12">Que el público vea al informativo como una referencia informativa en la que confiar. 
      </p>
      <img src="" alt="">
    </div>
    <div class="inicio my-4 p-8">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-90 rounded-md bg-pink-600 text-white">Mostrar seriedad e integrar la modernidad.</h3>
      <p class=" w-8/12">El rigor y la profesionalidad no están reñidos con la actualidad, por eso planteamos la posibilidad de que el usuario pueda informarse por varios canales, como lo son nuestras redes.
      </p>
    </div>
    <div class="inicio my-4 p-8 bg-gray-200 w-full">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-90 rounded-md bg-pink-600 text-white">Identificarse con el resto de la cadena alejándose de la prensa amarillista.</h3>
      <p class=" w-8/12">La cadena es muy conocida por sus programas de entretenimiento, pero nuestro informativo tiene un cometido muy concreto y es transmitir la actualidad informativa. 
      </p>
      
    </div>
    <div class="inicio my-4 p-8">
      <h3 class="my-4 font-bold text-lg py-2 px-4 w-90 rounded-md bg-pink-600 text-white">Acercarse a Mediaset</h3>
      <p class=" w-8/12">En este manual la marca va a mostrarse como parte de un sistema, que pretende modernizarse e integrarse con la cadena (Telecinco) y aproximarse a Factoría de Ficción.
      </p>
    </div>
    
    <!--<div class="container bg-gray-200 p-4 w-full">
    <IndividualContainer
    name="Paleta de color"
    text="abwssbiewvsde3ws"/>
    <img src="../static/silla2.jpg" alt="">
    </div>
    <HomeRecommendations>
      <CardTypeA
        v-for="(card, i) in rec" :key="i"
        :title="card.title"
        :text="card.text"
        :picture="card.picture"
        buttonContent="clicka aquí"
      />

    </HomeRecommendations>

-->
  </div>
</template>

<script>
import Title from "~/components/RepetedElements/Title.vue"
import CardTypeA from "~/components/Cards/CardTypeA.vue";
import IndividualContainer from "~/components/RepetedElements/IndividualContainer.vue";
export default {
    name: "IndexPage",
    components: { CardTypeA, Title, IndividualContainer }, 
}
</script>