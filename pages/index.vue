<template>
  <div>
    <main class="h-screen flex items-center px-6 lg:px-32 bg-purple-900 text-white">
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
        <span class="font-bold uppercase tracking-widest">Atomic</span>
        <h1 class="text-3xl lg:text-5xl font-bold text-pink-500">
          Tail<br/>Design
        </h1>
        <p class="font-bold mb-1">The Design is in the de{Tail}s...</p>
        <p>Lorem ipsum dolor sit amet...</p>
      </section>
    </main>
    <div class="p-6 lg:p-32">
      Test
    </div>
    <div>
      <footer class="w-full p-6 lg:p-32 bg-gray-900 text-gray-400">
        <div class="flex justify-between">
          <div>
            <p class="font-bold mb-1">Bloop</p>
            <p>More bloop</p>
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
