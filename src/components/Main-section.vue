<script setup>

</script>

<template>
        
      <!-- Jumbo section-->
      <section >
            <div class="container">
                  <img src="@/assets/MyImage/jumbo-bg.jpg" class="bg">
                  <h1  class="image-text">We are creatives</h1>
             <img src="@/assets/MyImage/down-arrow.png" class="arrow">
             
     </div>
        
      </section>
       
</template>

<style scoped>
  

  .image-text {
  position: absolute;
  top: 160px;
  left: 340.5px;;
  font-size:60px;
  color: white;
  font-family: 'Fraunces 9pt Soft';
  font-style: normal;
   font-weight: 900;
   font-size: 56px;
 line-height: 69px;
 text-align: center;
 letter-spacing: 8.75px;
 text-transform: uppercase;
}

           .arrow{
                  position: absolute;
                  bottom: 22vw;
                  left:50%;
                  transform: translate(-60%);
           }

           .bg{
               object-fit: contain;
               max-width: 1800px;
            margin: auto;
           }




</style>