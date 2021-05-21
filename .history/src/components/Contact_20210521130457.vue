/* eslint-disable vue/no-mutating-props */
/* eslint-disable vue/no-mutating-props */
<template>
    <div>
        <h1>CONTACTEZ NOUS</h1>
        <form action="#">
           
            <input  placeholder="Nom">
            <input type="text"   placeholder="Prénoms">
            <input type="email"   placeholder="Adresse Email">
            <input type="tel"  placeholder="Téléphone">
            <button type="submit">SOUMETTRE</button>
            
        </form>

        
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