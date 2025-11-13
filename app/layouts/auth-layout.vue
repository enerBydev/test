<script setup lang="ts">


</script>

<template>
    <div>
        <nuxt-link to="/">Home</nuxt-link>
        <nuxt-link to="/login">login</nuxt-link>
        <nuxt-link to="/register">Register</nuxt-link>        <slot />
        <footer>
            Auth Layout Footer
        </footer>        
    </div>
</template>