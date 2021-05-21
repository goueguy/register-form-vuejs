<template>
    <div>
        <h1>CONTACTEZ NOUS</h1>
        <form action="#">
            <input v-model="nom" placeholder="Nom">
            <input type="text"   placeholder="Prénoms">
            <input type="email"   placeholder="Adresse Email">
            <input type="tel"  placeholder="Téléphone">
            <button type="submit">SOUMETTRE</button>
            
        </form>

        <p>NOM:{{nom}}</p>
    </div>
</template>
<script>
export default {
    name:"Contact",
    props:{
        lastName: String,
        firstName: String,
        email: String,
        telephone: Number
    }
}
</script>