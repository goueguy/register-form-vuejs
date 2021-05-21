
<template>
    <div class="contact">
        <h1>CONTACTEZ NOUS</h1>
        <form action="#">
            <input  type="text" v-model="lastName" placeholder="Nom">
            <input type="text"  v-model="firstName" placeholder="Prénoms">
            <input type="email" v-model="email"  placeholder="Adresse Email">
            <input type="tel"  placeholder="Téléphone">
            <button type="submit">SOUMETTRE</button>
            
        </form>
        <p>{{email}}</p>
        
    </div>
</template>
<script>
export default {
    name: 'Contact',
    data(){
        return{
            email: "",
            
        }
    }
}
</script>