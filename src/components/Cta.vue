<template>
   <div class="section-cta container">
      <h2 class="section-cta--heading">Last Call to Action</h2>
      <p class="section-cta--text">Another section content goes here</p>
      <div class="row mt-5">
         <div class="col-md-6">
            <div class="card card-left shadow-sm border-0">
               <div class="card-body">
                  <div class="row card-box">
                     <div class="col-md-4 section-cta--img-container">
                        <img src="../assets/badge.laravel-mix.svg" alt="automation">
                        <div class="badge text-uppercase">Automation</div>
                     </div>
                       <div class="col-md-8 text-container">
                           <h5 class="text-uppercase">Roll Out</h5>
                           <h2 class="font-weight-bold">Automatic Prototyping</h2>
                           <p>
                              Webpack is the most powerful and flexible asset compilattion tool available today.
                              With that power, however, comes a certain level of complexity.
                           </p>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="col-md-6">
            <div class="card card-right shadow-sm border-0">
               <div class="card-body">
                  <div class="row card-box">
                     <div class="col-md-4 section-cta--img-container">
                        <img src="../assets/badge.how-to-read-code.svg" alt="automation">
                        <div class="badge text-uppercase bg-blue">Simplicity</div>
                     </div>
                       <div class="col-md-8 text-container">
                           <h5 class="text-uppercase">Sip Coffee</h5>
                           <h2 class="font-weight-bold">Complexity Simplified</h2>
                           <p>
                              I know too many backend developers who are stifled by one glaring phobia: CSS. 
                              How do you construct a layout when nothing lines up.
                           </p>
                     </div>
                  </div>
               </div>
            </div>
         </div>
      </div>
      <img class="section-cta--bg-img" src="../assets/bg-decals3.svg" alt="decals">
   </div>
</template>


<script>
export default {
  name: 'Cta',
}
</script>