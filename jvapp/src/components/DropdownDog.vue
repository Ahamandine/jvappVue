<!-- <script>

import { ref } from 'vue'

async function start() {
    try {
        const response = await fetch("https://dog.ceo/api/breeds/list/all")
        const data = await response.json()
        console.log(data.message)
        menuDog(data.message)
    } catch (e) {
        console.log(e)
    }
}
start()

function menuDog(dogBreed) {
    document.getElementById("breed").innerHTML = 
    <select onchange="PLACEHOLDERDROPDOWNDOG0">
        <option>selectionner une race de chien</option>
        $(Object.keys(dogBreed).map(function (breed){
            return '<option>${breed}</option>'
        }).join('')}
    
    </select>
}

// function favTutorial() {
// var mylist = document.getElementById("myList");
// document.getElementById("favourite").value = mylist.options[mylist.selectedIndex].text;
// }

</script>


<template>

<!-- <div class="pl-6 mt-14 mb-14">
        <p class="mb-4">
            <button class="inline-block px-6 py-2.5 bg-blue-600 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-blue-700 hover:shadow-lg focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-blue-800 active:shadow-lg transition duration-150 ease-in-out" type="button" data-bs-toggle="collapse" data-bs-target="#collapseWidthExample" aria-expanded="false" aria-controls="collapseWidthExample">
                Liste de chiens
            </button>
        </p>
        <div style="min-height: 120px;">
            <div class="collapse collapse-horizontal" id="collapseWidthExample">
            </div>
        </div>
</div> -->

<form>
    <b> Select you favourite tutorial site using dropdown list </b>
    <select  onchange = "favTutorial()" >
        <option> ---Choose tutorial--- </option>
        <option> w3schools </option>
        <option> Javatpoint </option>
        <option> tutorialspoint </option>
        <option> geeksforgeeks </option>
    </select>
    <p> Your selected tutorial site is: 
    <input type = "text" id = "favourite" size = "20" /> </p>
</form>

</template>


<style>

</style> -->