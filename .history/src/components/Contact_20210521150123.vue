
<template>
    <div class="w-full max-w-lg mx-auto">
        <h1 class="mb-3">CONTACTEZ NOUS</h1>
        <form action="#" class="bg-white p-8 pt-6 shadow-lg mb-5">
            <div class="mb-2">
                <label for="lastName" class="mb-3 block  text-sm text-gray-500 text-left font-bold">Nom</label>
                <input  type="text" v-model="lastName"  class="p-2 mb-3 rounded w-full block border">
            </div>
            <div class="mb-2">
                <label for="firstName" class="mb-3 block  text-sm text-gray-500 text-left font-bold">Prénoms</label>
                <input type="text"  v-model="firstName"  class="mb-3 p-2 rounded w-full block border">
            </div>
            <div class="mb-2">
                <label for="email" class="mb-3 block  text-sm text-gray-500 text-left font-bold">Adresse Email</label>
                <input type="email" v-model="email"   class="mb-3 p-2 rounded w-full block border">
            </div>

            <div class="mb-2">
                <label for="telephone" class="mb-3 block  text-sm text-gray-500 text-left font-bold">Numéro de Téléphone</label>
                <input type="tel"  v-model="telephone"  class="mb-3 p-2 rounded w-full block border">
            </div>
            <div class="flex items-center justify-between py-2">
                <button type="submit"  class="bg-blue-500 text-white hover:bg-gray-700 py-2 px-4 rounded" v-on:click="loginData">SOUMETTRE</button>
                <a href="#" class="text-blue-500 font-bold text-sm ">Mot de passe Oublié</a>
            </div>
        </form>
    </div>
    
</template>
<style>
    body{
        background-color: #EDF2F7;
    }
</style>
<script>
export default {
    name: 'Contact',
    data(){
        return{
            lastName: "",
            firstName: "",
            telephone: "",
            email: "",
            
        }
    },
    methods:{
        loginData(){
            
            
        }
    }
    
}
</script>