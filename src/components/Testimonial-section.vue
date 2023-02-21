<script>
</script>

<template>
    <!-- Testimonials -->
    
      <div class="testimonials">
      <div class="inner">
       <div class="testimonials-text">CLIENT TESTIMONIALS</div>
        <div class="row">
            <div class="col-testimonial">
                <div class="testimonial">
                    <img src="@/assets/MyImage/jennie.png" alt="">
                     <p class="testimonialparagph">Incredible end result! Our sales increased over 400% when we worked with Sunnyside. Highly recommended!</p>
                        <div class="name">Jennie F. </div>
                        <h6>Business Owner</h6>
                </div>
            </div>
            <div class="col-testimonial">
                <div class="testimonial">
                    <img src="@/assets/MyImage/emily.png" alt="">
                     <p class="testimonialparagph">"We put our trust in Sunnyside and they delivered, making sure our needs were met and deadlines were always hit.</p>
                     <div class="name">Emily R.</div>
                     <h6>Marketing Director</h6>
                </div>
            </div>
            <div class="col-testimonial">
                <div class="testimonial">
                    <img src="@/assets/MyImage/thomas.png" alt="">
                     <p class="testimonialparagph">"Sunnyside’s enthusiasm coupled with their keen interest in our brand’s success made it a satisfying and enjoyable experienc.</p>
                        <div class="name">Thomas S.</div>
                         <h6>Chief Operating Officer</h6>
                </div> 
            </div>
        </div>
      </div>
</div>
      
</template>

<style scoped>
    .testimonials{
    padding: 40px;
    background: #fff;
    color: #434343;
    text-align: center;

}

.testimonials-text{
    
   font:Fraunces 9pt Soft ;
    color: #A7AAAD;
    text-align: center;
    font-size: 25px;
    font-weight: 900;
    padding-top: 10.19%;
    padding-bottom:5%;
    margin-left:380px;
    margin-right:380px;
}




.inner{
       max-width: 1200px;
       margin: auto;
       overflow: hidden;
       padding: 0 20px;
}



.row{
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.col-testimonial{
     flex:33.33%;
     max-width: 33.33%;
     padding-bottom: 10px;
     padding-bottom: 20px; 
}

.testimonial{
         background: #fff;
         padding-top: 30px;

}

.testimonial img{
         width: 90px;
         height: 90px;
         padding-bottom: 0px;
}

.name{
      font-size:18px;
      font: Barlow;
      padding: 25px;
      color:#24303E;
      text-align: center;
      line-height:22.19px;
      text-transform: uppercase;
      margin: 20px 0;
      font-weight:bolder;
}

.testimonialparagph{
    color: #5B636D;
    font-family: Barlow;
    margin: 15px;
    padding-top: 10px;
    font-size:18px;
    text-align: center;
    padding-top: 200px;
    font-weight:600;
    line-height:32px;
}

h6{
     color: #A7AAAD;
     text-align: center;
     font-size:14px;
     letter-spacing: -0.1 px;
     font-weight: 600;
     line-height:25px;
}

.column-table {
   float: left;
   width: 25%;
   padding: 10px;
   height: 300px;
   margin-right: -10px; 
 }
 


 .row-table:after {
   content: "";
   display: table;
   clear: both;
 }
</style>