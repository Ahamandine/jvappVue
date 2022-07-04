<script setup>
import { ref } from "vue";
</script>

<template>
    <div class="grid grid-cols-4 text-white bg-slate-900 h-18 font-serif">

        <h1 class="place-self-center mb-2 -ml-8 font-extrabold text-3xl -mr-8 text-orange-500 tracking-tight">GreatGames</h1>

        <div class="flex justify-around m-4 -ml-8 text-xl font-bold" id="topnav">
            <a class="active" href="#home">Accueil</a>
            <a href="#news">Jeux</a>
            <a href="#contact">Catégories</a>
            <a href="#about">Panier</a>
        </div>

        <div class="flex justify-center">
            <div class="m-2">
                <div class="input-group relative flex flex-wrap items-stretch w-full mb-4 mt-2">
                <input type="search" class="form-control relative flex-auto min-w-0 block w-full text-base font-normal text-gray-700 bg-white bg-clip-padding border border-solid border-gray-300 rounded transition ease-in-out m-1 focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none" placeholder="Zelda, Mario, Bioshock..." aria-label="Search" aria-describedby="button-addon2">
                <button class="btn inline-block p-1 mt-1 h-6 bg-gray-900 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover: hover:shadow-lg focus:  focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out flex items-center" type="button" id="button-addon2">
                    <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="search" class="w-4" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                    <path fill="currentColor" d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z"></path>
                    </svg>
                </button>
                </div>
            </div>
        </div>

        <div class="flex justify-center m-6">
            <label class="form-check-label inline-block mr-4" for="flexSwitchCheckDefault">Livraison</label>
            <div class="form-check form-switch">
            <input class="form-check-input appearance-none w-9 -ml-10 rounded-full float-left h-5 align-top bg-white bg-no-repeat bg-contain bg-gray-300 focus:outline-none cursor-pointer shadow-sm" type="checkbox" role="switch" id="flexSwitchCheckDefault">
            <label class="form-check-label inline-block ml-2" for="flexSwitchCheckDefault">Click & Collect</label>
            </div>
        </div>
    </div>
</template>

<style>

</style>
