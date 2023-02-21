<template>
  <div class="home">
    <HelloWorld msg="Implementando Bootstrap 5 en Vue 3" /> 
    <AccordionBoot msg="1. Ejemplos de Acordeones (Accordions)" />
    <AlertBoot msg="2. Ejemplos de Alertas (Alerts)" />
    <BadgeBoot msg="3. Ejemplos de Insignias (Badges)" />
    <BreadCrumb msg="4. Ejemplos de Migas de Navegación (Breadcrumbs)" />
    <ButtonBoot msg="5. Ejemplos de Botones (Buttons)" />
    <ButtonGroup msg="6. Ejemplos de Grupos de Botones" />
    <CardBoot msg="7. Ejemplos de Tarjetas (Cards)" />
    <CarouselBoot msg="8. Ejemplos de Carruseles (Carousels)" />
    <CloseButton msg="9. Ejemplos de Botones de Cierre (Close Buttons)" />
    <CollapseBoot msg="10. Ejemplos de Colapsos (Collapses)" />
    <FlipCard msg="#. Ejemplos de Tarjetas Giratorias (Flip Cards)" />
    <FlipCard2 />
    <h1 style="color: purple"><strong>FIN</strong></h1>
    <img alt="Vue logo" src="./assets/logo.png" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AccordionBoot from './components/AccordionBoot.vue'
import AlertBoot from './components/AlertBoot.vue'
import BadgeBoot from './components/BadgeBoot.vue'
import BreadCrumb from './components/BreadCrumb.vue'
import ButtonBoot from './components/ButtonBoot.vue'
import ButtonGroup from './components/ButtonGroup.vue'
import CardBoot from './components/CardBoot.vue'
import CarouselBoot from './components/CarouselBoot.vue'
import CloseButton from './components/CloseButton.vue'
import CollapseBoot from './components/CollapseBoot.vue'
import FlipCard from './components/FlipCard.vue'
import FlipCard2 from './components/FlipCard2.vue'

export default {
  name: 'App',
  components: {
    HelloWorld, AccordionBoot, AlertBoot, BadgeBoot, BreadCrumb, ButtonBoot, ButtonGroup, CardBoot, CarouselBoot, CloseButton, CollapseBoot, FlipCard, FlipCard2
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
