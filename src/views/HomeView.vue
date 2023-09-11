<script setup lang="ts">

</script>

<template>

    <section class="relative block" style="height: 500px;">
        <div
          class="absolute top-0 w-full h-full bg-center bg-cover"
          style='background-image: url("img/header.png");'
        >
          <span
            id="blackOverlay"
            class="w-full h-full absolute opacity-50 bg-black"
          ></span>
        </div>
        <div
          class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
          style="height: 70px;"
        >
          <svg
            class="absolute bottom-0 overflow-hidden"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="none"
            version="1.1"
            viewBox="0 0 2560 100"
            x="0"
            y="0"
          >
            <polygon
              class="text-gray-300 fill-current"
              points="2560 0 2560 100 0 100"
            ></polygon>
          </svg>
        </div>
      </section>
      <section class="relative py-16 bg-gray-300">
        <div class="container mx-auto">
          <div
            class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-xl rounded-lg -mt-64"
          >
            <div class="px-6">
              <div class="flex flex-wrap justify-center">
                <div
                  class="w-full lg:w-3/12 px-4 lg:order-2 flex justify-center"
                >
                  <div class="relative">
                    <img src="../../public/img/profile.png" alt="profile" class="shadow-xl rounded-full h-auto align-middle border-none -m-16 -ml-20 lg:-ml-16"
                      style="max-width: 180px;">
                  </div>
                </div>
                <div class="w-full lg:w-4/12 px-4 lg:order-3 lg:text-right lg:self-center">
                  <div class="py-6 px-3 mt-32 sm:mt-0">
                    <button
                      class="bg-pink-500 active:bg-pink-600 uppercase text-white font-bold hover:shadow-md shadow text-xs px-4 py-2 rounded outline-none focus:outline-none sm:mr-2 mb-1"
                      type="button"> NSFW</button>
                  </div>
                </div>
                <div class="w-full lg:w-4/12 px-4 lg:order-1">                
                </div>
              </div>
              <div class="text-center mt-12">
                <h3
                  class="text-4xl font-semibold leading-normal mb-2 text-gray-800 mb-2"
                >
                  Riodile
                </h3>
                <div
                  class="text-sm leading-normal mt-0 mb-2 text-gray-500 font-bold uppercase">
                  Indonesia
                </div>
                <div class="mb-2 text-gray-700 mt-10">
          He/Him/ | 28 | Commission Status: Closed | Birb | May contain furry muscles or cute stuffs
                </div>
              </div>

              <div class="mt-10 py-10 border-t border-gray-300 text-center">
                <div class="text-4xl leading-normal mt-0 mb-2 text-slate-900 font-bold uppercase">
                  Example 
                </div>
                <div class="flex flex-wrap justify-center">

                  <div class="pb-8 text-2xl leading-normal mt-0 mb-2 text-slate-900 font-bold uppercase">
                  Puyo Puyo Samples 
                </div>
                  <div class="hidden md:contents">
                  <div class="grid grid-cols-3 gap-4">
                    <div><img src="../../public/img/Sample1.png" alt="profilebiasa1"></div>
                      <div><img src="../../public/img/Sample2.png" alt="profilebiasa5"></div>
                      <div><img src="../../public/img/Sample3.png" alt="profilebiasa3"></div>
                  </div>
                  <div class="pt-24 pb-8 text-2xl leading-normal mt-0 mb-2 text-slate-900 font-bold uppercase">
                    Gradient Shade
                </div>
                  <div class="grid grid-cols-3 gap-4">
                    <div><img src="../../public/img/GradientShadeSamples/sample1.png" alt="profilebiasa2"></div>
                      <div><img src="../../public/img/GradientShadeSamples/sample2.png" alt="profilebiasa5"></div>
                      <div><img src="../../public/img/GradientShadeSamples/sample3.png" alt="profilebiasa3"></div>
                  </div>
                </div>

                <div class="contents md:hidden">
                    <div><img src="../../public/img/Sample1.png" alt="profilebiasa1"></div>
                      <div><img src="../../public/img/Sample2.png" alt="profilebiasa5"></div>
                      <div><img src="../../public/img/Sample3.png" alt="profilebiasa3"></div>
                      <div class="pt-24 pb-8 text-2xl leading-normal mt-0 mb-2 text-slate-900 font-bold uppercase">
                  Gradient Shade 
                </div>
                      <div class="" ><img src="../../public/img/GradientShadeSamples/sample1.png" alt="profilebiasa2"></div>
                      <div><img src="../../public/img/GradientShadeSamples/sample2.png" alt="profilebiasa5"></div>
                      <div><img src="../../public/img/GradientShadeSamples/sample3.png" alt="profilebiasa3"></div>
                </div>
                  <div class="w-full lg:w-9/12 px-4">
                    <p class="mb-4 text-lg leading-relaxed text-gray-800">
Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat, perferendis. Porro veniam neque minus ullam animi reiciendis ipsa, dolorem nemo mollitia obcaecati, fuga fugiat quod illum quisquam possimus? Tenetur, quo.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

</template>

