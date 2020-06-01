<template>
    <div>
        <h2>Nav Bar</h2>
        <nav>
            <router-link to="/home">Home</router-link>
            <router-link to="/contact">Contact</router-link>
            <router-link to="/about">About</router-link>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'Navigation'
}
</script>