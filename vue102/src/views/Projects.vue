<template>
    <div class="project w-full h-auto mx-auto">
        <Navbar/>
        <p>project : {{tel}}</p>
    </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },
    data() {
        return {
            tel: "06300033994"
        }
    },
}
</script>

<style>
    
</style>