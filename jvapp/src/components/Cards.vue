<script setup>

import { ref } from 'vue'

</script>

<template>

    <div class="flex justify-around my-20">
        <div id="card1">
            <div class="flex justify-center">
                <div class="block p-6 rounded-lg shadow-lg bg-white max-w-sm">
                    <img src="src/components/img/hollowKnight.jpg" >
                    <h5 class="text-gray-900 text-xl leading-tight font-medium mb-2">
                    Hollow Knight
                    </h5>
                    <p class="text-gray-700 text-base mb-4">

                    </p>
                    <button
                    type="button"
                    class="inline-block px-6 py-2.5 bg-amber-200 text-slate-500 font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-amber-500 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out">
                    Découvrir le jeu
                    </button>
                </div>
            </div>
        </div>
        

        <div id="card2">
            <div class="flex justify-center">
                <div class="block p-6 rounded-lg shadow-lg bg-white max-w-sm">
                    <img src="src/components/img/madelineBadeline.jpg">
                    <h5 class="text-gray-900 text-xl leading-tight font-medium mb-2">
                    Céleste
                    </h5>
                    <p class="text-gray-700 text-base mb-4">

                    </p>
                    <button
                    type="button"
                    class="inline-block px-6 py-2.5 bg-blue-600 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out">
                    Découvrir le jeu
                    </button>
                </div>
            </div>
        </div>

        <div id="card3">
            <div class="flex justify-center">
                <div class="block p-6 rounded-lg shadow-lg bg-white max-w-sm">
                    <img src="src/components/img/kateMarsh.jpg">
                    <h5 class="text-gray-900 text-xl leading-tight font-medium mb-2">
                    Life is Strange
                    </h5>
                    <p class="text-gray-700 text-base mb-4">

                    </p>
                    <button
                    type="button"
                    class="inline-block px-6 py-2.5 bg-blue-600 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out">
                    Découvrir le jeu
                    </button>
                </div>
            </div>
        </div>
    </div>
    

</template>

<style>

</style>
