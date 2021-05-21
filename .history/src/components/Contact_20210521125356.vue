<template>
    <div>
        <h1>CONTACTEZ NOUS</h1>
        <form action="#">
            <input type="text"  placeholder="Nom">
            <input type="text"   placeholder="Prénoms">
            <input type="email"   placeholder="Adresse Email">
            <input type="tel"  v-model="telephone" placeholder="Téléphone">
            <button type="submit">SOUMETTRE</button>
            
        </form>

        <p>NOM:{{nom}}</p>
    </div>
</template>
<script>
export default {
    name:"Contact",
    props:{
        nom: String,
        prenoms: String,
        email: String,
        telephone: Number
    }
}
</script>