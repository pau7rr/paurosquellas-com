<template>
    <div>
        <h1 class=" font-mono text-4xl font-extrabold text-gray-100 md:text-6xl mb-10">
            hi, I'm <span class=" text-green-200"> Pau Rosquellas 👋 </span>
        </h1>
        <span class="typing text-white mx-auto text-3xl"> Web Developer! </span>
    </div>
</template>

<style scoped>
    .typing {
        display: block;
        font-family: monospace;
        white-space: nowrap;
        border-right: 4px solid;
        width: 15ch;
        animation: typing 2s steps(12), blink .5s infinite step-end alternate;
        overflow:hidden;
    }

    @keyframes typing {
        from { width: 0}
    }
    
    @keyframes blink {
        50% { border-color: transparent}
    }
</style>