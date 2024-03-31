<template>
    <div class="navbar bg-[#271740] h-16 flex flex-wrap items-center justify-between mx-auto p-2">
      <div class="flex-1 mx-6">
        <a href="/" class="mr-4 text-white font-bold">PORTFOLIO/></a>
      </div>
      <ul class="flex flex-row mr-6">
        <li>
            <a href="/about" class="text-white font-bold m-4 hover:text-green-500 focus:text-green-500" :class="{ 'active-link': $route.path === '/about' }">ABOUT ME</a>
        </li>
        <li>
          <a href="/project" class="text-white font-bold m-4" :class="{ 'active-link': $route.path === '/project' }">PROJECTS</a>
        </li>
        <li>
          <a href="/contact" class="text-white font-bold m-4" :class="{ 'active-link': $route.path === '/contact' }">CONTACT</a>
        </li>
      </ul>
    </div>
</template>

<style>
  a.text-white:hover {
    color: #4F8446;
  }
  /* แต่งจาก class */
  .active-link { 
    color: #4F8446;
    }

</style>