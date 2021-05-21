<template>
    <div>
        <h1>CONTACTEZ NOUS</h1>
        <form action="#">
            <input type="text" v-model="nom" placeholder="Nom">
            <input type="text" v-model="prenoms" placeholder="Prénoms">
            <input type="email" v-model="email" placeholder="Adresse Email">
            <input type="tel" v-model="telephone" placeholder="Téléphone">
            <button type="submit">SOUMETTRE</button>
            
        </form>
    </div>
</template>
<script>
export default {
    name:"Contact",
    props:{
        nom:
    }
}
</script>