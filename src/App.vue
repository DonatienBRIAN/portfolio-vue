<template>
<div>
    <HeaderComp/>
    <main>
    <SkillsComp/>
    <PortfolioComp/>
    <ContactComp/>
    </main>
    <NavComp/>
</div>
</template>

<script>
import HeaderComp from './components/HeaderComp.vue';
import SkillsComp from './components/SkillsComp.vue';
import PortfolioComp from './components/PortfolioComp.vue';
import ContactComp from './components/ContactComp.vue';
import NavComp from './components/NavComp.vue';


export default {
  name: 'App',
  components: {
    HeaderComp,
    SkillsComp,
    PortfolioComp,
    ContactComp,
    NavComp
  },
  
  mounted() {
    document.title = "Donatien BRIAN";
    let Script = document.createElement("script");
    Script.setAttribute("src", "https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js");
    document.head.appendChild(Script);
    let Script2 = document.createElement("script");
    Script2.setAttribute("src", "https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js");
    document.head.appendChild(Script2);
    let btnIndex = document.createElement("script");
    btnIndex.setAttribute("src", "btnIndex.js");
    document.head.appendChild(btnIndex);
     }  
     
}
</script>

<style>
@import 'https://unpkg.com/ionicons@4.5.10-0/dist/css/ionicons.min.css';
@import './assets/css/style.css';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
