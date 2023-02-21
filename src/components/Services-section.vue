<script>

</script>

<template>
   <idiv class="grid-container">
<div class="grid-item">
      <img src="@/assets/MyImage/apple.jpg" alt="">
      <h2>Graphics Design</h2>
          <p>Great design 
            makes you memorable. We deliver<br /> artwork that underscores your brand message
             <br />and captures potential clients’ attention.</p>     
    </div>
    <div class="grid-item">
      <img src="@/assets/MyImage/orange.jpg" alt="">
         <h2>Photography</h2>
          <p>Increase your credibility by getting the most<br /> stunning,
             high-quality photos that improve your<br /> business image.</p> 
    </div>
  
     </idiv>
      
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
   
            img{
      height: 590px;
   }    


            h2{
                position: absolute;
height: 35px;
left: 17.4%;
right: 17.4%;
top: calc(55%);

font-family: 'Fraunces 9pt Soft';
font-style: normal;
font-weight: 900;
font-size: 28px;
line-height: 35px;
/* identical to box height */

text-align: center;
letter-spacing: -0.2px;

color: #24554A;
            }
 p{
    position: absolute;
left: 0%;
right: 0%;
top: 70.36%;
bottom: 0%;
margin: auto 0;
font-family: 'Barlow';
font-style: normal;
font-weight: 600;
font-size: 16px;
line-height: 27px;
/* or 169% */

text-align: center;
letter-spacing: -0.114286px;

color: #24554A;
 }

</style>