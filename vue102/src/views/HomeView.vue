<script setup>
  import Navbar from '../components/Navbar.vue'
</script>

<template>
  <div class="w-full mx-auto h-screen bg-[#271740] bg-cover">
    <Navbar />
    <div class="grid grid-cols-2">
        <div class="text-white flex justify-center items-center h-[90vh] mx-32">
            <div>
                <h1 class="text-3xl font-medium">HI, I'm modtanoii</h1>
                <h1 class="text-4xl font-bold mt-2">Busabawan Prasertsuk</h1>
                <p class="mt-2 font-sans">I'm a 3rd-year Information Technology student, King Mongkut's Institute of Technology Ladkrabang</p>
                <div class="mt-10 mx-16">
                  <a href="/about">
                    <button class="bg-[#4F8446] rounded-lg py-3 px-4 font-medium text-2xl">More About Me</button>
                  </a>
                </div>
                
            </div> 
        </div>
        <div class="text-white flex justify-center items-center h-[80vh] mx-32">
            <div class="bg-[#D9D9D9] w-96 h-96 rounded-full"></div> 
        </div>
    </div>
</div>



</template>
