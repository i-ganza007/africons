<template>
<div>
  <NavBar/>
  <Hero/>
  <ServiceSect/>
  <AboutSect/>
  <statNumbers/>
  <ProjectsSect/>
  <!-- <clientsComp/> -->
  <contactComp/>
  <formComp/>
</div>
  
</template>

<script>
import NavBar from './components/NavBar.vue'
import Hero from './components/HeroComp.vue'
import ServiceSect from './components/ServiceSect.vue'
import AboutSect from './components/AboutSect.vue'
import statNumbers from './components/statNumbers.vue'
import ProjectsSect from './components/ProjectsSect.vue'
import contactComp from './components/contactsComp.vue'
import formComp from './components/formComp.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Hero,
    ServiceSect,
    AboutSect,
    statNumbers,
    ProjectsSect,
    contactComp,
    formComp
  }
}
</script>

