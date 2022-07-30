<template>
  <NavbarComponent/>
   <HeaderComponent/>
   <CardsComponent/>
   <MissionComponent/>
   <HelpComponent/>
   <FooterComponent/>
</template>

<script>

import NavbarComponent from './components/NavbarComponent.vue'
import HeaderComponent from './components/HeaderComponent.vue'
import CardsComponent from './components/CardsComponent.vue'
import MissionComponent from './components/MissionComponent.vue'
import HelpComponent from './components/HelpComponent.vue'
import FooterComponent from './components/FooterComponent.vue'



export default {
  name: 'App',
  components: {
    NavbarComponent,
    HeaderComponent,
     CardsComponent,
     MissionComponent, 
     HelpComponent,
     FooterComponent,
    // HelloWorld
  }
}
</script>


