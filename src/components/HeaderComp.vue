<template>
    <div class="header">
        <div class="hamburger">
            <Hamburger />
        </div>
        <button class="btn">
            Log Out
        </button>
        
    </div>

</template>
<script setup>
    import Hamburger from './icons/Hamburger.vue'
</script>
<style scoped>
    .hamburger {
        width: fit-content;
        height: fit-content;
        border: 2px solid black;
        border-radius: 5px;
        background-color: aqua;
        padding: 0 0.2rem;
    }
    .header {
        height: fit-content;
        display: flex;
        padding: 0.5rem 1rem;
        justify-content: space-between;
        align-items: stretch;
    }
</style>