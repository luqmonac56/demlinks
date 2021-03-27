<template>
  <section>
            <h2 class=" font-medium text-2xl   ">Our          <span class=" text-yellow-500">Story</span></h2>
            <div class=" bg-yellow-800 w-20 h-0.5 my-0 mx-auto"></div>

            <div class=" md:flex my-8 md:px-10 justify-between w-full items-center ">
                  <img src="@/assets/images/our-story.png" alt="our story " class=" shadow-2xl w-3/4 md:w-80  my-0 mx-auto md:m-0 rounded-2xl mb-6">
                  <div class=" md:flex flex-col justify-center items-center">
                        <p class=" leading-loose px-5 text-base md:text-left md:px-0 md:pb-6">We are a team of great minds dedicated to serving our consumers with an excellent delivery service thus greatly improving our client's revenue and engagements.</p>
                  <p class=" leading-loose px-5 text-base md:text-left hidden md:px-0  md:block ">We are a team of great minds dedicated to serving our consumers with an excellent delivery service thus greatly improving our client's revenue and engagements.</p>
                  </div>
            </div>
  </section>

  <section class=" flex flex-col justify-between items-center ">

        <div class=" p-6 bg-white rounded-3xl shadow-2xl w-80 mb-8 md:mb-0 ">
              <h2 class=" text-yellow-500 text-left mb-4">Mission</h2>
              <p class=" text-left w-full">Lorem ipsum dolor sit amet sectetur adipisicing elit.</p>
        </div>

        <div class=" p-6 bg-white rounded-3xl shadow-2xl w-80 mb-8 md:mb-0">
              <h2 class=" text-yellow-500 text-left mb-4">Vission</h2>
              <p class=" text-left w-full">Lorem ipsum dolor sit amet sectetur adipisicing elit.</p>
        </div>
  </section>

  <div class=" bg-gray-300 w-full h-0.5 mb-8"></div>

  <section class=" mb-10 w-full ">
      <h2 class=" font-medium text-2xl">What  <span class=" text-yellow-500">We Offer</span></h2>
      <div class=" bg-yellow-800 w-28 h-0.5 mt-0 mb-8 mx-auto"></div>

      <div class=" bg-yellow-500 w-full overflow-hidden md:flex justify-around items-center  ">
            <img src="@/assets/images/web-design.jpeg" alt="" class=" offer-img my-20 mx-auto transform -rotate-12 w-48 rounded-3xl shadow-2xl ">
            <div class=" text-white m-auto">
                  <h2 class=" font-medium text-2xl mb-4 md:text-left">Web Design & Development</h2>
                  <p class=" px-6 text-base leading-8 mb-6 text-center md:p-0 md:text-left">We are proficient in designing world class websites to suit your business and taste. We also manage your website  to become the most displayed when anything related to what you do is being searched for.</p>
                  <button class=" bg-yellow-800 px-10 py-4 rounded-2xl mb-6 md:mb-0 text-lg ">Learn more.</button>
            </div>
      </div>

      <div class=" bg-white w-full overflow-hidden ">
            <div class=" text-black mt-8">
                  <h2 class=" font-medium text-2xl mb-4">Web Design & Development</h2>
                  <p class=" px-6 text-base leading-8 mb-6 text-center ">We are proficient in designing world class websites to suit your business and taste. We also manage your website  to become the most displayed when anything related to what you do is being searched for.</p>
                  <button class=" bg-yellow-800 px-10 py-3 rounded-2xl mb-6 text-lg text-white">Learn more.</button>
            </div>
            <img src="@/assets/images/business-branding.png" alt="" class=" offer-img my-10 mx-auto transform -rotate-12 w-48 rounded-3xl shadow-2xl">
      </div>
        
  </section>

  <section class=" pl-6 flex items-baseline flex-col" >
        <h2 class=" mb-6 text-2xl font-medium text-left">Want to know more about our services?</h2>

        <button class="bg-yellow-800 px-12 py-3 rounded-2xl mb-6 text-lg text-white   ">Explore</button>
        
  </section>
<div class=" bg-gray-300 w-full h-0.5 mb-8"></div>


<section class=" mb-10">
      <h2 class="text-2xl">Testim<span class=" text-yellow-500 ">onials</span></h2>
      <div class=" bg-yellow-800 w-20 h-0.5 mt-0 mb-8 mx-auto"></div>

      <div class=" w-11/12 shadow-2xl my-0 mx-auto ">
            <img src="@/assets/images/testimony.svg" alt="testimony" class=" w-9/12 pt-3 ml-3">

<!-- class=" flex flex-col items-baseline " -->
            <div >
                  <div class=" flex flex-col items-baseline "  >
                        <img src="@/assets/images/upper-quotation.png" alt="" class="w-14">

                        <p class=" px-8 text-left ">Lorem, ipsum dolor sit amet consectetur adipisicing elit.  aperiam enim, atque quia unde, in delectus repudiandae recusandae ex?</p>

                        <img src="@/assets/images/lower-quotation.png" alt="" class="  w-14">
                  </div>

                  <h2 class=" text-left text-xl font-semibold text-yellow-500">John Tee</h2>          
                  <h3 class="text-left text-lg font-semibold">CEO, frit publications</h3>        
            </div>

            <img src="@/assets/images/next.png" alt="" class=" w-7 h-8 bg-yellow-700 ">

      </div>

</section>
  

</template>

<script>
// @ is an alias to /src


export default {
  name: 'mainBody',

}
</script>