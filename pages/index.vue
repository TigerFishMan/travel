<template>
  <div>
    <main class="h-screen flex items-center px-6 lg:px-32 text-white" style="backgroundImage: url(/images/10.jpg); background-size: cover;">
      <header class="w-full absolute left-0 top-0 p-6 lg:px-32 lg:py-16">
        <div class="flex justify-between">
          <div>
            <h1 class="text-3xl font-bold">{Logo}</h1>
            <span>Design is everything...</span>
          </div>

          <div>
            <ul class="flex">
              <li class="ml-10">
                <a href="">
                  <div class="text-right">Home</div>
                </a>
              </li>
              <li class="ml-10">
                <a href="">
                  <div class="text-right">Locations</div>
                </a>
              </li>
              <li class="ml-10">
                <a href="">
                  <div class="text-right">About us</div>
                </a>
              </li>
              <li class="ml-10">
                <a href="">
                  <div class="text-right">Contact us</div>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </header>
      <section class="w-full md:w-9/12 xl:w-8/12">
        <h1 class="text-3xl lg:text-5xl font-bold text-pink-100">
          Company Name
        </h1>
        <p>Lorem ipsum dolor sit amet...</p>
      </section>
    </main>

    <div class="p-6 lg:px-32 lg:pt-32 lg:pb-0">
      <div class="w-full text-center p-6 lg:px-32 lg:py-8 mb-4 text-4xl">About Us</div>
      <div class="w-full text-center p-6 lg:px-32 lg:py-8 mt-4">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi non enim et nulla rutrum semper sed vel tortor. Mauris gravida nulla sem. Sed nibh ligula, tristique ullamcorper rutrum nec, facilisis sit amet nulla. Maecenas in ligula ante. Donec at elementum velit. Praesent eget dui velit. Pellentesque efficitur imperdiet ipsum, nec imperdiet turpis semper quis. Integer mattis lacinia ipsum id blandit. Praesent condimentum convallis erat ac posuere.
      </div>
    </div>

    <div class="p-6 lg:px-32 lg:pt-32 lg:pb-0">
      <div class="w-full text-center p-6 lg:px-32 lg:py-8 mb-4 text-4xl">Locations</div>
      <div class="grid grid-cols-3 gap-4 text-white">
        <div v-for="i in 9" :key="i" class="w-full h-40" style="background-size: cover" :style="{ backgroundImage: 'url(/images/' + i + '.jpg)' }"></div>
      </div>
      <div class="w-full text-center p-6 lg:px-32 lg:py-8 mt-4">View all locations</div>
    </div>

    <div class="p-6 lg:px-32 lg:p-32">
      <div class="w-full text-center p-6 lg:px-32 lg:py-8 mb-4 text-4xl">Contact Us</div>
      <div class="grid grid-cols-2 gap-4">
        <div v-for="j in 2" :key="j" class="w-full">
          <div class="w-full text-center p-6 mb-4">Send us a message</div>
          <div class="w-full text-center p-6">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi non enim et nulla rutrum semper sed vel tortor. Mauris gravida nulla sem. Sed nibh ligula, tristique ullamcorper rutrum nec, facilisis sit amet nulla. Maecenas in ligula ante. Donec at elementum velit. Praesent eget dui velit. Pellentesque efficitur imperdiet ipsum, nec imperdiet turpis semper quis. Integer mattis lacinia ipsum id blandit. Praesent condimentum convallis erat ac posuere.
          </div>
        </div>
      </div>
    </div>

    <div>
      <footer class="w-full p-6 lg:p-32 bg-gray-900 text-gray-400">
        <div class="flex justify-between">
          <div>
            <p class="font-bold mb-1">Name</p>
            <p>Copyright</p>
          </div>

          <div>
            <ul class="flex">
              <li class="ml-10">
                <a href="">
                  <div class="text-right">Home</div>
                </a>
              </li>
              <li class="ml-10">
                <a href="">
                  <div class="text-right">Locations</div>
                </a>
              </li>
              <li class="ml-10">
                <a href="">
                  <div class="text-right">About us</div>
                </a>
              </li>
              <li class="ml-10">
                <a href="">
                  <div class="text-right">Contact Us</div>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
