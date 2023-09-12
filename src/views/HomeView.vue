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
                    <RouterLink to="/nsfw"> <button
                      class="bg-slate-800 active:bg-slate-600 uppercase text-white font-bold hover:shadow-md shadow text-xs px-2 py-2 rounded outline-none focus:outline-none sm:mr-2 mb-1"
                      type="button"><i class='bx bxs-vial'></i>NSFW</button> </RouterLink>
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
          He/Him | Birb | May contain furry muscles or cute stuffs
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
                      <div><img src="../../public/img/Sample2.png" alt="profilebiasa2"></div>
                      <div><img src="../../public/img/Sample3.png" alt="profilebiasa3"></div>
                      <div><img src="../../public/img/Sample4.png" alt="profilebiasa4"></div>
                      <div><img src="../../public/img/Sample5.png" alt="profilebiasa5"></div>
                      <div><img src="../../public/img/Sample6.png" alt="profilebiasa6"></div>
                  </div>
                  <!-- Gradient Shade -->
                  <div>
                  <div class="pt-24 pb-8 text-2xl leading-normal mt-0 mb-2 text-slate-900 font-bold uppercase">
                    Gradient Shade
                </div>
                  <div class="grid grid-cols-3 gap-4">
                    <div  class="col-start-1 col-end-7"><img src="../../public/img/GradientShadeSamples/sample2.png" alt="profilebiasa7"></div>
                      <div><img src="../../public/img/GradientShadeSamples/sample3.png" alt="profilebiasa8"></div>
                      <div><img src="../../public/img/GradientShadeSamples/sample1.png" alt="profilebiasa9"></div>
                      <div><img src="../../public/img/GradientShadeSamples/sample4.png" alt="profilebiasa10"></div>
                  </div>
                  </div>
                  <!-- CellShade -->
                  <div>
                  <div class="pt-24 pb-8 text-2xl leading-normal mt-0 mb-2 text-slate-900 font-bold uppercase">
                    Cell Shading
                </div>
                  <div class="grid grid-cols-3 gap-4">
                    <div class="col-span-2"><img src="../../public/img/CellShade/Sample1.png" alt="profilebiasa7"></div>
                    <div><img src="../../public/img/CellShade/Sample3.png" alt="profilebiasa9"></div>
                    <div><img src="../../public/img/CellShade/Sample5.png" alt="profilebiasa10"></div>
                    <div class="col-span-2"><img src="../../public/img/CellShade/Sample2.png" alt="profilebiasa8"></div>
                  </div>
                  </div>
                </div>
                
                <!-- Responsive -->
                <div class="contents md:hidden">
                  <div><img src="../../public/img/Sample1.png" alt="profilebiasa1"></div>
                      <div><img src="../../public/img/Sample2.png" alt="profilebiasa2"></div>
                      <div><img src="../../public/img/Sample3.png" alt="profilebiasa3"></div>
                      <div><img src="../../public/img/Sample4.png" alt="profilebiasa4"></div>
                      <div><img src="../../public/img/Sample5.png" alt="profilebiasa5"></div>
                      <div><img src="../../public/img/Sample6.png" alt="profilebiasa6"></div>
                      <div class="pt-24 pb-8 text-2xl leading-normal mt-0 mb-2 text-slate-900 font-bold uppercase">
                  Gradient Shade 
                </div>
                      <div class="" ><img src="../../public/img/GradientShadeSamples/sample1.png" alt="profilebiasa2"></div>
                      <div><img src="../../public/img/GradientShadeSamples/sample2.png" alt="profilebiasa5"></div>
                      <div><img src="../../public/img/GradientShadeSamples/sample3.png" alt="profilebiasa3"></div>
                      <div><img src="../../public/img/GradientShadeSamples/sample4.png" alt="profilebiasa3"></div>
                      <div class="pt-24 pb-8 text-2xl leading-normal mt-0 mb-2 text-slate-900 font-bold uppercase">
                    Cell Shading
                </div>
                <div><img src="../../public/img/CellShade/Sample1.png" alt="profilebiasa7"></div>
                <div><img src="../../public/img/CellShade/Sample3.png" alt="profilebiasa9"></div>
                <div><img src="../../public/img/CellShade/Sample5.png" alt="profilebiasa10"></div>
                <div><img src="../../public/img/CellShade/Sample2.png" alt="profilebiasa8"></div>
                </div>
                </div>

              </div>
            </div>
          </div>
        </div>
      </section>

      <footer class="relative bg-gray-300 pt-8 pb-6">
    <div
      class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20"
      style="height: 80px;"
    >

    </div>
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap">
        <div class="w-full lg:w-6/12 px-4">
          <h4 class="text-3xl font-semibold">Riodile PuyoBirb</h4>
          <h5 class="text-lg mt-0 mb-2 text-gray-700">
            He/Him | Birb | May contain furry muscles or cute stuffs
          </h5>
          <div class=" mt-6">
            <a href="https://www.facebook.com/profile.php?id=100074358756626" target="_blank"><box-icon type='logo' name='facebook' class="mr-2"></box-icon></a>
            <a href="https://twitter.com/RiodileArt"><box-icon name='twitter' type='logo' color='' class="mr-2" ></box-icon></a>
            <a href="https://t.me/Riodile" target="_blank"><box-icon type='logo' name='telegram'></box-icon></a>
          </div>
        </div>
        
        <div class="pt-5 w-full lg:w-6/12">
          <div class="flex flex-wrap items-top mb-6">
            <div class="w-full lg:w-4/12 px-4 ml-auto">
              <span
                class="block uppercase text-gray-600 text-sm font-semibold mb-2"
                >Useful Links</span
              >
              <ul class="list-unstyled">
                <li>
                  <a
                    class="text-gray-700 hover:text-gray-900 font-semibold block pb-2 text-sm"
                    href="#"
                    >About Us</a
                  >
                </li>

              </ul>
            </div>
            <div class="w-full lg:w-4/12 px-4">
              <span
                class="block uppercase text-gray-600 text-sm font-semibold mb-2"
                >Other Resources</span
              >
              <ul class="list-unstyled">
                <li>
                  <a
                    class="text-gray-700 hover:text-gray-900 font-semibold block pb-2 text-sm"
                    href="#"
                    >MIT License</a
                  >
                </li>
                <li>
                  <a
                    class="text-gray-700 hover:text-gray-900 font-semibold block pb-2 text-sm"
                    href="#"
                    >Terms &amp; Conditions</a
                  >
                </li>
                <li>
                  <a
                    class="text-gray-700 hover:text-gray-900 font-semibold block pb-2 text-sm"
                    href="#"
                    >Privacy Policy</a
                  >
                </li>
                <li>
                  <a
                    class="text-gray-700 hover:text-gray-900 font-semibold block pb-2 text-sm"
                    href="#"
                    >Contact Us</a
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>

      <hr class="my-6 border-gray-400" />

      <div
        class="flex flex-wrap items-center md:justify-between justify-center"
      >
        <div class="w-full md:w-4/12 px-4 mx-auto text-center">
          <div class="text-sm text-gray-600 font-semibold py-1">
            Copyright © 
            <a
              href="https://www.kitimaru.my.id"
              class="text-gray-600 hover:text-gray-900"
              >Kitimaru</a>.
          </div>
        </div>
      </div>
    </div>
  </footer>

</template>

