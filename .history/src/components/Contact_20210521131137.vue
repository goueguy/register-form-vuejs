
<template>
    <div id="contact">
        <h1>CONTACTEZ NOUS</h1>
        <form action="#">
            <input  name="telephone" v-model="telephone" placeholder="Nom">
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
    
}

</script>