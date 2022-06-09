<script setup>
</script>

<template>
  <header class=" h-20 w-full">
      <nav class=" grid grid-cols-2 content-center h-full">
          <div class=" flex justify-center">
            <RouterLink to="/" class=" w-12 h-12 flex rounded bg-black bg-opacity-20 border-2 border-slate-900"><p class=" m-auto">P</p></RouterLink>
          </div>
          <div class=" flex justify-center items-center gap-x-3 text-slate-900">  
            <RouterLink to="/about" class=" w-20 h-10 flex rounded-md bg-black bg-opacity-20"><p class=" m-auto">About</p></RouterLink>
            <RouterLink to="/about" class=" w-20 h-10 flex rounded-md bg-black bg-opacity-20"><p class=" m-auto">Projects</p></RouterLink>
            <RouterLink to="/about" class=" w-20 h-10 flex rounded-md bg-black bg-opacity-20"><p class=" m-auto">Contact</p></RouterLink>
          </div>
      </nav>
  </header>
</template>

<style scoped>
    header {
        background-color: #85FFBD;
        background-image: linear-gradient(45deg, #85FFBD 0%, #FFFB7D 100%);
    }
</style>