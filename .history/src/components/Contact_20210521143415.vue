
<template>
    <div class="w-ful max-">
        <h1>CONTACTEZ NOUS</h1>
        <form action="#">
            
                <input  type="text" v-model="lastName" placeholder="Nom" class="w-full block border">
            
            <input type="text"  v-model="firstName" placeholder="Prénoms">
            <input type="email" v-model="email"  placeholder="Adresse Email">
            <input type="tel"  v-model="telephone" placeholder="Téléphone">
            <button type="submit" v-on:click="loginData">SOUMETTRE</button>
            
        </form>
    </div>
    
</template>
<style>
   
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