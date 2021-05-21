
<template>
    <div class="w-full max-w-lg mx-auto">
        <h1 class="mb-3">CONTACTEZ NOUS</h1>
        <form action="#" class="bg-white p-8 pt-6 shadow-lg">
            <div class="mb-2">
                <label for="lastName" class="block  text-sm text-gray-300 text-left font-bold">Nom</label>
                <input  type="text" v-model="lastName" placeholder="Nom" class="p-2 mb-3 rounded w-full block border">
            </div>
            <input type="text"  v-model="firstName" placeholder="Prénoms" class="mb-3 p-2 rounded w-full block border">
            <input type="email" v-model="email"  placeholder="Adresse Email" class="mb-3 p-2 rounded w-full block border">
            <input type="tel"  v-model="telephone" placeholder="Téléphone" class="mb-3 p-2 rounded w-full block border">
            <button type="submit" v-on:click="loginData">SOUMETTRE</button>
            
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