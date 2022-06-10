<script setup>
</script>

<template>
  <header class=" ">
      <nav class=" h-20 w-full grid grid-cols-2 content-center">
          <div class=" col-span-2 md:col-span-1 flex justify-center">
            <RouterLink to="/" class=" w-12 h-12 flex rounded bg-black bg-opacity-20 border-2 border-slate-900"><p class=" m-auto">P</p></RouterLink>
          </div>
          <div class=" hidden md:flex justify-center items-center gap-x-3 text-slate-900 font-mono">  
            <RouterLink to="/about" class=" w-24 h-10 flex rounded-md bg-black bg-opacity-20 hover:bg-opacity-40"><p class=" m-auto">About</p></RouterLink>
            <RouterLink to="/about" class=" w-24 h-10 flex rounded-md bg-black bg-opacity-20 hover:bg-opacity-40"><p class=" m-auto">Projects</p></RouterLink>
            <RouterLink to="/about" class=" w-24 h-10 flex rounded-md bg-black bg-opacity-20 hover:bg-opacity-40"><p class=" m-auto">Contact</p></RouterLink>
          </div>
      </nav>
      <div class=" md:hidden flex p-3 border-2 border-slate-900 justify-evenly font-mono text-gray-100 underline underline-offset-8 bg-slate-900">
        <RouterLink to="/about" class=""><p class="">About</p></RouterLink>
        <RouterLink to="/about" class=""><p class="">Projects</p></RouterLink>
        <RouterLink to="/about" class=""><p class="">Contact</p></RouterLink>
      </div>
  </header>
</template>

<style scoped>
    nav {
      background-color: #85FFBD;
      background-image: linear-gradient(45deg, #85FFBD 0%, #FFFB7D 100%);
    }
</style>