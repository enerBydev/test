<script setup lang="ts">

</script>

<template>
    <div>
        <nuxt-link to="/">Home</nuxt-link>
        <nuxt-link to="/about">About</nuxt-link>
        <nuxt-link to="/products">Products</nuxt-link>
        <nuxt-link to="/login">login</nuxt-link>
        <nuxt-link to="/register">Register</nuxt-link>
        <slot />
            <footer>
                <p> 
                @2024 My Nuxt App     
                </p>
            </footer>
    </div>
</template>