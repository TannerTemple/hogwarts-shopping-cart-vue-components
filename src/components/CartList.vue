<template>
    <div>   
        <CartListItem v-for="cartItem in cartItems" :key="cartItem.id" :item="cartItem"/>
    </div>

</template>

<script setup>
import CartListItem from './CartListItem.vue';
defineProps(['cartItems'])

</script>

<style scoped>

</style>