<template>
    <div>
        <h1>CONTACTEZ NOUS</h1>
        <form action="#">
            <input type="text" aria-label="true" v-model="nom" placeholder="Nom">
            <input type="text" aria-label="true" v-model="prenoms" placeholder="Prénoms">
            <input type="email" aria-label="true" v-model="email" placeholder="Adresse Email">
            <input type="tel" aria-label="true" v-model="telephone" placeholder="Téléphone">
            <button type="submit">SOUMETTRE</button>
            
        </form>

        <div>NOM:</div>
    </div>
</template>
<script>
export default {
    name:"Contact",
    props:{
        nom:String,
        prenoms:String,
        email:String,
        telephone:Number
    }
}
</script>