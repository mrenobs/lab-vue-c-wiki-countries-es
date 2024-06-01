<script setup>
const paises = [
    {
        alpha3Code: 'FRA'
        pais: "Francia",
        foto: "https://flagpedia.net/data/flags/icon/72x54/fr.png"
    },
    {
        alpha3Code: 'ALE'
        pais: "Alemania",
        foto: "https://flagpedia.net/data/flags/icon/72x54/fr.png"
    },
    {
        alpha3Code: 'BRA'
        pais: "Brasil",
        foto: "https://flagpedia.net/data/flags/icon/72x54/fr.png"
    },

]
</script>
<template>
    <div>
        <p>{{ paises[0].pais }}</p>
        <a href=""><img src={{ paises[0].foto }} alt="Francia"></a>
    </div>
    <div>
        <p>{{ paises[1].pais }}</p>
        <a href=""><img src={{ paises[1].foto }} alt="Alemania"></a>
    </div>
    <div>
        <p>{{ paises[2].pais }}</p>
        <a href=""><img src={{ paises[2].foto }} alt="Brasil"></a>
    </div>
</template>
<style></style>