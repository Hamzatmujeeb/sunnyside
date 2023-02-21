<script setup>
import Header from "./components/Header-section.vue";
import Section from "./components/Main-section.vue";
import About from   "./components/About-section.vue";
import Service from  "./components/Services-section.vue";
import Testimonials from  "./components/Testimonial-section.vue";
import Products from "./components/Project-section.vue";
import Footers from  "./components/Footer-section.vue";
</script>

<template>
     <div class="container">
          <Header /> 
          <main>
              <Section />
               <About />
                 <Service />
                 <Testimonials />
                 <Products />
                 <Footers />
          </main>
     </div>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


.container {
  max-width: 400rem;
  margin: 0 auto;
  padding: 0 auto;
}
</style>
