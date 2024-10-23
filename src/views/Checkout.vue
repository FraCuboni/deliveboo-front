<script>
import axios from 'axios';
import { store } from '../store';
import Jumbo from '../components/Jumbo.vue';
import RestaurantCard from '../components/partials/RestaurantCard.vue';
import Loader from '../components/partials/loader.vue';
export default{
    name: 'Checkout',
    
}
</script>

<template>
    <h2>SONO IL CHECKOUT</h2>
</template>

<style lang="scss" scoped>
@use '../styles/general.scss' as *;
@use '../styles/partials/variables' as *;
@use '../styles/partials/mixins' as *;

</style>
