
<template>
    <div class="w-full max-w-lg mx-auto">
        <h1>CONTACTEZ NOUS</h1>
        <form action="#" class="bg-white p-8 pt-6">
            
                <input  type="text" v-model="lastName" placeholder="Nom" class="p-2w-full block border">
            
            <input type="text"  v-model="firstName" placeholder="Prénoms">
            <input type="email" v-model="email"  placeholder="Adresse Email">
            <input type="tel"  v-model="telephone" placeholder="Téléphone">
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