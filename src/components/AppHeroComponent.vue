<script>
import AppDescrizioneComponent from './AppDescrizioneComponent.vue'
export default {
    name: "Immagine",
    components: {
        AppDescrizioneComponent
    }
}

</script>

<template>
    <div>
        <img src="../img/ok.jpg" alt="Pollice di conferma">
        <AppDescrizioneComponent />
    </div>
</template>

<style scoped>
div {
    margin: 0 auto;
    width: 40%;
    display: flex;
}

img {
    width: 60%;
}
</style>