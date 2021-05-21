<template>
    <div>
        <h1>CONTACTEZ NOUS</h1>
        <form action="#">
            <input type="text" v-model="nom" placeholder="Nom">
            <input type="text" v-model="prenoms" placeholder="Prénoms">
            <input type="text" v-model="email" placeholder="Adresse Email">
            <input type="text" v-model="telephone" placeholder="Nom">
            
            
        </form>
    </div>
</template>
<script>
export default {
    name:"Contact",
    props:[]
}
</script>