<template>
    <div class="btn-new">
        <button class="btn">New Project</button>
        <button class="btn">New Todo</button>
    </div>
    <nav>
        <a href="#">To-do</a>
        <a href="#">In-Progress</a>
        <a href="#">Done</a>
    </nav>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
</template>
<script>

</script>
<style scoped>
    .btn-new {
        display: flex;
        padding: 0.5rem;
        justify-content: space-between;
    }
    nav {
        display: flex;
        align-items: baseline;
    }
    a {
        flex: 1;
        display: block;
        border-top-left-radius: 5px;
        border-top-right-radius: 5px;
        border: 1px solid black;
        text-align: center;
        padding: 0.5rem;
        text-decoration: none;
        font-weight: 600;
    }
    ul {
        list-style: none;
    }
</style>