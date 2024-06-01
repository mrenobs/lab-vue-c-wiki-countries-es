<script setup>
import { useRoute } from 'vue-router';
import CountryDetail from './views/CountryDetail.vue'
const route = useRoute():


</script>
<template>
    <CountryDetail>
        <li>
            <Routerlink :to="{name:'list'}"></Routerlink>

        </li>
        <li>
            <RouterLink :to="{name:'details'}"></RouterLink>

        </li>

    </CountryDetail>
    

</template>
<style></style>