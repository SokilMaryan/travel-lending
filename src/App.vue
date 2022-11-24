<!-- eslint-disable vue/no-parsing-error -->
<!-- eslint-disable max-len -->
<template>
  <header class="text-gray-600 body-font">
    <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
      <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
        <img class="w-[42px]" src="./images/logo.png" alt="">
        <span class="ml-3 text-xl">Salty</span>
      </a>
      <nav class="md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-gray-400	flex flex-wrap items-center text-base justify-center">
        <a class="mr-5 hover:text-gray-900">Home</a>
        <a class="mr-5 hover:text-gray-900">About us</a>
        <a class="mr-5 hover:text-gray-900">Destinations</a>
        <a class="mr-5 hover:text-gray-900">Tours</a>
        <a class="mr-5 hover:text-gray-900">Blog</a>
      </nav>
      <button class="inline-flex items-center justify-center bg-gray-100 text-[#F66F4D] border-solid border-[1px] border-[#F66F4D] rounded-full mt-8 lg:mt-0 hover:opacity-80  h-14 w-44 ">
        Button
        <img src="src\images\icons\book.svg">
      </button>
    </div>
  </header>

  <section class="container mx-auto my-20 lg:mt-20 lg:mb-40">
    <div class="grid lg:grid-cols-2 items-center gap-16">
      <div>
        <h1 class="text-6xl " style="word-spacing: 20px;">Discover the Best Lovely Places</h1>
        <p class="text-base pt-6 pb-8 text-[#5B5F62]">Plan and book your perfect trip with expert advice, travel tips, destination information and inspiration from us.</p>
        <form class="h-20 2-full bg-white py-4 px-8 rounded-full flex justify-between items-center gap-4">
          <div class="flex flex-col flex-1">
            <label for="location" class="text-lg font-medium">Where</label>
            <div class="flex gap-2">
              <input name="location" type="text" class="text-xs focus:outline-none w-full lg:w-[140px]" placeholder="Center Point, Lo...">
              <img src="src\images\icons\location.svg" alt="" class="inline">
            </div>
          </div>
          <div class="border h-full" />
          <div class="flex flex-col flex-1">
            <label for="location" class="text-lg font-medium">Date</label>
            <div class="flex gap-2">
              <input name="location" class="text-xs text-gray-400 w-full lg:w-[140px]  " placeholder="09th March,2021">
              <img src="src\images\icons\calendar.svg" alt="" class="inline">
            </div>
          </div>
          <div class="w-10 h-10">
            <button>
              <img src="src\images\icons\search.svg" alt="">
            </button>
          </div>
        </form>
      </div>
      <div>
        <img src="./images/bannerHeader.png" alt="">
      </div>
    </div>
  </section>

  <section class="carousel-group container mx-auto">
    <div class="">
      <h2 class="text-5xl font-semibold w-96">Categories</h2>
      <p class="text-[#5B5F62] pt-6 pb-8 w-80">Here are lots of interesting destinations to visit, but don’t be confused—they’re already grouped by category.</p>

      <div class="overflow-hidden relative">
        <div class="items flex mt-10 gap-8 justify-items-center overflow-x-scroll hide-scrollbar unselectable">
          <div class="p-4 rounded-[84px] shadow-sm flex-shrink-0 w-fit">
            <img class="w-[170px] h-[230px]" src="src\images\category1.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4 flex items-center justify-center">Beach</h5>
          </div>

          <div class="p-4 rounded-[84px] shadow-sm flex-shrink-0 w-fit">
            <img class="w-[170px] h-[230px]" src="src\images\category2.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4 flex items-center justify-center">Beach</h5>
          </div>
          <div class="p-4 rounded-[84px] shadow-sm flex-shrink-0 w-fit">
            <img class="w-[170px] h-[230px]" src="src\images\category3.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4 flex items-center justify-center">Beach</h5>
          </div>
          <div class="p-4 rounded-[84px] shadow-sm flex-shrink-0 w-fit">
            <img class="w-[170px] h-[230px]" src="src\images\category4.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4 flex items-center justify-center">Beach</h5>
          </div>
          <div class="p-4 rounded-[84px] shadow-sm flex-shrink-0 w-fit">
            <img class="w-[170px] h-[230px]" src="src\images\category5.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4 flex items-center justify-center">Beach</h5>
          </div>
          <div class="p-4 rounded-[84px] shadow-sm flex-shrink-0 w-fit">
            <img class="w-[170px] h-[230px]" src="src\images\category6.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4 flex items-center justify-center">Beach</h5>
          </div>
          <div class="p-4 rounded-[84px] shadow-sm flex-shrink-0 w-fit">
            <img class="w-[170px] h-[230px]" src="src\images\category1.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4 flex items-center justify-center">Beach</h5>
          </div>
        </div>
        <div class="absolute top-48"><img src="src\images\icons\arrow-left.svg" alt=""></div>
        <div class="absolute top-48 right-0"><img src="src\images\icons\arrow-right.svg" alt=""></div>
      </div>
    </div>
  </section>

  <!-- experience -->
  <section class="container mx-auto my-20 lg:my-40">
    <div class="grid grid-cols-1 lg:grid-cols-2 items-center gap-16">
      <div><img src="src\images\banner2.png" alt="" class="mx-auto"></div>
      <div class="">
        <h6 class="text-[#F66F4D] text-xl font-semibold">Our Experience</h6>
        <h2 class="text-5xl font-semibold my-6">Our Stories Have Adventures</h2>
        <p>We are experienced in bringing adventures to stay their journey, with all outdoor destinations in the world as our specialties. Start your adventure now! Nature has already called you!</p>
        <div class="flex overflow-auto mt-10 gap-5 hide-scrollbar">
          <div class="bg-white h-44 w-40 flex justify-center pl-8 flex-col gap-5 flex-shrink-0">
            <h3 class="text-4xl font-semibold text-[#F66F4D]">12K+</h3>
            <h6 class="text-xl">Success Journey</h6>
          </div>
          <div class="bg-white h-44 w-40 flex justify-center pl-8 flex-col gap-5 flex-shrink-0">
            <h3 class="text-4xl font-semibold text-[#F66F4D]">16+</h3>
            <h6 class="text-xl">Awards Winning</h6>
          </div>
          <div class="bg-white h-44 w-40 flex justify-center pl-8 flex-col gap-5 flex-shrink-0">
            <h3 class="text-4xl font-semibold text-[#F66F4D]">20+</h3>
            <h6 class="text-xl">Years of Experience</h6>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- popular destination -->
  <section class="carousel-group container mx-auto">
    <div class="">
      <h2 class="text-5xl font-semibold w-96">Find Popular Destination</h2>
      <div class="overflow-hidden relative">
        <div class="items flex mt-10 gap-8 justify-items-center overflow-x-scroll hide-scrollbar unselectable">
          <div class="bg-[#FAF8ED] p-4 rounded-3xl shadow-sm flex-shrink-0 w-fit">
            <img class="w-[362px]" src="src\images\destination1.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4">Mountain Hiking Tour</h5>
            <p class="text-sm">Mountain Hiking Tour</p>
            <div class="flex justify-between py-6">
              <div><span class="text-2xl font-semibold">$89</span><span class="text-xl">/Person</span></div>
              <div class="bg-[#2D3134] text-white px-4 py-2 rounded-full hover:opacity-80"><a href="">Book Now</a></div>
            </div>
          </div>
          <div class="bg-[#FAF8ED] p-4 rounded-3xl shadow-sm flex-shrink-0 w-fit">
            <img class="w-[362px]" src="src\images\destination2.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4">Machu Picchu, Peru</h5>
            <p class="text-sm">Machu Picchu, Peru</p>
            <div class="flex justify-between py-6">
              <div><span class="text-2xl font-semibold">$99</span><span class="text-xl">/Person</span></div>
              <div class="bg-[#2D3134] text-white px-4 py-2 rounded-full hover:opacity-80"><a href="">Book Now</a></div>
            </div>
          </div>
          <div class="bg-[#FAF8ED] p-4 rounded-3xl shadow-sm flex-shrink-0 w-fit">
            <img class="w-[362px]" src="src\images\destination3.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4">The Grand Canyon, Arizona</h5>
            <p class="text-sm">Mountain Hiking Tour</p>
            <div class="flex justify-between py-6">
              <div><span class="text-2xl font-semibold">$70</span><span class="text-xl">/Person</span></div>
              <div class="bg-[#2D3134] text-white px-4 py-2 rounded-full hover:opacity-80"><a href="">Book Now</a></div>
            </div>
          </div>
          <div class="bg-[#FAF8ED] p-4 rounded-3xl shadow-sm flex-shrink-0 w-fit">
            <img class="w-[362px]" src="src\images\destination1.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4">Mountain Hiking Tour</h5>
            <p class="text-sm">Mountain Hiking Tour</p>
            <div class="flex justify-between py-6">
              <div><span class="text-2xl font-semibold">$89</span><span class="text-xl">/Person</span></div>
              <div class="bg-[#2D3134] text-white px-4 py-2 rounded-full hover:opacity-80"><a href="">Book Now</a></div>
            </div>
          </div>
          <div class="bg-[#FAF8ED] p-4 rounded-3xl shadow-sm flex-shrink-0 w-fit">
            <img class="w-[362px]" src="src\images\destination2.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4">Machu Picchu, Peru</h5>
            <p class="text-sm">Machu Picchu, Peru</p>
            <div class="flex justify-between py-6">
              <div><span class="text-2xl font-semibold">$99</span><span class="text-xl">/Person</span></div>
              <div class="bg-[#2D3134] text-white px-4 py-2 rounded-full hover:opacity-80"><a href="">Book Now</a></div>
            </div>
          </div>
          <div class="bg-[#FAF8ED] p-4 rounded-3xl shadow-sm flex-shrink-0 w-fit">
            <img class="w-[362px]" src="src\images\destination3.png" alt="" draggable="false">
            <h5 class="text-2xl font-semibold py-4">The Grand Canyon, Arizona</h5>
            <p class="text-sm">Mountain Hiking Tour</p>
            <div class="flex justify-between py-6">
              <div><span class="text-2xl font-semibold">$70</span><span class="text-xl">/Person</span></div>
              <div class="bg-[#2D3134] text-white px-4 py-2 rounded-full hover:opacity-80"><a href="">Book Now</a></div>
            </div>
          </div>
        </div>
        <div class="absolute top-48"><img src="./icons/arrow-left.svg" alt=""></div>
        <div class="absolute top-48 right-0"><img src="./icons/arrow-right.svg" alt=""></div>
      </div>
    </div>
  </section>

  <!-- top destination -->
  <section class="container mx-auto my-20 lg:my-40">
    <h2 class="text-5xl font-semibold text-center">Top Destination</h2>
    <P class="py-4 text-center">Sost Brilliant reasons Entrada should be your one-stop-shop!</P>
    <div class="flex overflow-auto hide-scrollbar gap-4 lg:justify-center">
      <div class="bg-[#2D3134] text-white px-4 py-2 rounded-full"><a href="">London</a></div>
      <div class="border-[#2D3134] border px-4 py-2 rounded-full hover:bg-[#2D3134] hover:text-white duration-200"><a href="">Bangkok</a></div>
      <div class="border-[#2D3134] border px-4 py-2 rounded-full hover:bg-[#2D3134] hover:text-white duration-200"><a href="">England</a></div>
      <div class="border-[#2D3134] border px-4 py-2 rounded-full hover:bg-[#2D3134] hover:text-white duration-200"><a href="">Singapore</a></div>
      <div class="border-[#2D3134] border px-4 py-2 rounded-full hover:bg-[#2D3134] hover:text-white duration-200"><a href="">Italy</a></div>
    </div>
    <div class="grid grid-cols-2 lg:grid-cols-3 gap-6 mt-10 justify-items-center">
      <div><img src="src\images\Rectangle4389.png" alt=""></div>
      <div><img src="src\images\Rectangle4390.png" alt=""></div>
      <div><img src="src\images\Rectangle4390.png" alt=""></div>
      <div><img src="src\images\Rectangle4390.png" alt=""></div>
      <div class="hidden lg:block"><img src="src\images\Rectangle4390.png" alt=""></div>
      <div class="hidden lg:block"><img src="src\images\Rectangle4390.png" alt=""></div>
    </div>
  </section>

  <!-- review -->
  <section class="container mx-auto">
    <div class="grid grid-cols-1 lg:grid-cols-2 items-center gap-8">
      <div><img src="src\images\banner3.png" alt="" class="mx-auto w-[407px]"></div>
      <div class="">
        <div class="w-16 border-4 border-[#F66F4D]" />
        <h2 class="text-5xl font-semibold my-6">A customer said about us:</h2>
        <div class="bg-white rounded-2xl w-full px-5 py-6">
          <p class="text-lg">Salty helped me a lot in finding the best place for our first outdoor adventure trip. They responded very quickly and gave me a detailed account of the place—its history, as well as its best features.</p>
          <div class="flex pt-8 pb-4 gap-1">
            <img src="src\images\icons\star.svg" alt="">
            <img src="src\images\icons\star.svg" alt="">
            <img src="src\images\icons\star.svg" alt="">
            <img src="src\images\icons\star.svg" alt="">
            <img src="src\images\icons\star.svg" alt="">
          </div>
          <div>
            <div>
              <h6 class="text-xl">Andrew Sarma</h6>
              <p class="text-xs pt-1">Enterpreneur</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- newsletter -->
  <section class="container mx-auto my-20 lg:mt-40">
    <div class="bg-[#FFD482] rounded-3xl h-96 flex items-center justify-center">
      <div class=" text-center px-4">
        <h4 class="text-3xl font-semibold">
          Sign Up to Our Newsletter
        </h4>
        <p class="w-full sm:w-96 mt-6 mb-8 mx-auto">
          Reciev latest news, update, and many other things every week.
        </p>
        <div class="flex bg-white rounded-lg h-16 w-full  pl-4 items-center justify-between mx-auto">
          <input type="email" name="email" class="text-sm h-4 focus:outline-none block" placeholder="Enter your email address">
          <a href="" class="block">
            <img src="src\images\icons\send.svg" alt="" class="pt-2">
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- footer -->
  <footer class="container mx-auto py-24">
    <div class="grid grid-cols-2 lg:grid-cols-6 gap-16 justify-items-center">
      <div class="col-span-2 ml-0 mx-auto ml-auto lg:ml-0">
        <a class="logo w-[100%] no-underline flex items-center mb-20px" href="index.html">
          <img class="w-[20%]" src="./images/logo.png" alt="">
          <span class="font-bold font-[Sen] text[20px]  ml-[10px] leading-[20px]">Salty</span>
        </a>
        <p class="font-normal Snter text-[16px] leading-[26px] text-semiGray m-0 mb-[40px]">Enjoy the touring with Salty</p>
        <div class="social flex gap-[14px]">
          <a class="flex items-center justify-center border-solid border-[1px] rounded-full m-10px border-semiGray w-[40px] h-[40px] hover:border-orange1 hover: text transition-all 0.5s ease-in-out " href="#"><i class="fab fa-facebook-f text-semiGray text-[14px] hover:border-solid border[1px] hover:border-orange1 hover:text-orange1" /> </a>
          <a class="flex items-center justify-center border-solid border-[1px] rounded-full m-10px border-semiGray w-[40px] h-[40px]  hover:border-orange1 hover: text transition-all 0.5s ease-in-out" href="#"> <i class="fab fa-instagram  text-semiGray text-[14px] hover:border-solid border[1px] hover:border-orange1 hover:text-orange1" /></a>
          <a class="flex items-center justify-center border-solid border-[1px] rounded-full m-10px border-semiGray w-[40px] h-[40px]  hover:border-orange1 hover: text transition-all 0.5s ease-in-out" href="#"> <i class="fab fa-twitter    text-semiGray text-[14px] hover:border-solid border[1px] hover:border-orange1 hover:text-orange1" /></a>
        </div>
      </div>
      <div>
        <p class="text-lg font-medium">Resources</p>
        <ul class="mt-6 text-sm">
          <li class="pb-3"><a href="">Download</a></li>
          <li class="pb-3"><a href="">Help Center</a></li>
          <li class="pb-3"><a href="">Guide Book</a></li>
          <li class="pb-3"><a href="">App Directory</a></li>
        </ul>
      </div>
      <div>
        <p class="text-lg font-medium">Travellers</p>
        <ul class="mt-6 text-sm">
          <li class="pb-3"><a href="">Why Travellers</a></li>
          <li class="pb-3"><a href="">Enterprise</a></li>
          <li class="pb-3"><a href="">Custom Stories</a></li>
          <li class="pb-3"><a href="">Instagram Post</a></li>
        </ul>
      </div>
      <div>
        <p class="text-lg font-medium">Company</p>
        <ul class="mt-6 text-sm">
          <li class="pb-3"><a href="">Travelling</a></li>
          <li class="pb-3"><a href="">About location</a></li>
          <li class="pb-3"><a href="">Success</a></li>
          <li class="pb-3"><a href="">Information</a></li>
        </ul>
      </div>
      <div>
        <p class="text-lg font-medium">Get App</p>
        <ul class="mt-6 text-sm">
          <li class="pb-3"><a href="">App Store</a></li>
          <li class="pb-3"><a href="">Google Play Store</a></li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<script lang="ts" setup>
// YOUR CODE HERE
const isEdited = ref(false)
const contactInput = ref()

const selectEditView = async () => {
  isEdited.value = true
  await nextTick()
  contactInput.value.focus()
}
</script>

<style lang="scss">
.app-container {
  max-width: 1440px;
  padding: 30px;
}

.contact-list {
  grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
}
</style>
