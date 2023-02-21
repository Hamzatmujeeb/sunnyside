<template>
  
  <div class="grid-container">
      <div class="grid-item">
        <h2 class="grid-item-text">Transform your<wbr> brand</h2>
        <p>We are a full-service creative agency 
            specializing in helping brands grow fast. Engage your clients through
             compelling visuals that do most of the marketing for you.</p>
             <h5>Learn More</h5>
              <div class="learn-more-yellow" ></div>
      </div>
      <div class="grid-item"><img src="@/assets/MyImage/egg.jpg" alt="">
      </div>

      <div class="grid-item"><img src="@/assets/MyImage/cup.jpg" alt="">
      </div>
      <div class="grid-item">
        <h2 class="grid-item-text">Stand out to the right <br/> audience</h2>
         <p>Using a collaborative formula of designers, researchers,
             photographers, 
             videographers, and copywriters, we’ll build and extend your brand in digital places. </p>
              <h5>Learn More</h5>
              <div class="learn-more-pink" ></div>
    </div>
    </div>

     
</template>

<style scoped>
   
   .grid-container{
                   display: grid;
                   column-gap: 0px;
                   grid-template-columns: auto auto ;
                   padding: 0px 35px 0px 35px;
            }

            .grid-item{
                border: none;
                padding:auto;
            }

            .grid-item-text{
                font-family: 'Fraunces 9pt Soft';
                font-style: normal;
                 font-weight: 900;
                  font-size: 40px;
                  line-height: 49px;
                  text-align: center;
                   letter-spacing: 2.285714px;
                    color: #24303E;
                    height: 98px;
                    left: 35px;
                    top: 70px;
                    padding-top: 50px;
                    width: 445px;
                   height: 98px;
            }
    

            p{
        width: 445px;
         height: 60px;
         left: 15px;
         top: 108px;
        font-family: 'Barlow';
        font-style: normal;
        font-weight: 600;
         font-size: 15px;
       line-height: 30px;
       margin: 70px;
     /* or 167% */

        letter-spacing: -0.128571px;

        color: #808397;
   
   }

   img{
      height: 590px;
   }

 

h5{
  position: absolute;
height: 25px;
top: 100%;
top: calc(50% - 25px/2);
padding: 100px;
font-family: 'Fraunces 9pt Soft';
font-style: normal;
font-weight: 900;
font-size: 15px;
line-height: 25px;
/* identical to box height, or 167% */
letter-spacing: 1px;
text-transform: uppercase;

color: #24303E;
}

 .learn-more-yellow{
  position: absolute;
left: 14%;
right: 0%;
top: 67.70%;
bottom: 0%;
height: 6px;
width: 113px;
background: #FAD400;
border-radius: 28px;
 }

 .learn-more-pink{
  position: absolute;
left: 14%;
right: 0%;
top: 67.70%;
bottom: 0%;
height: 6px;
width: 113px;
background: #FE7766;
border-radius: 28px;
 }
</style>
