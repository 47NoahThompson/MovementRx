<template>
    <div class="navbar">
        <div class="brand"><p>MovementRx</p></div>
        <div class="title">{{ pageTitle }}</div>
        <div><p class="menu">☰</p></div>
    </div>
</template>

<script>
export default {
    props: ['pageTitle'],
    setup () {
        return {}
    }
}
</script>

<style>
body {
    margin: 0;
}

.navbar {
    top: 0;
    position: fixed; 
    width: 99vw;
    display: grid;
    grid-template-columns: 1fr auto 1fr;
    align-items: center;
    /* background-color: #076BB4; */
    background-color: #0665AA;
    color: white;
    height: 75px; /* Adjust the height as needed */
    padding: 0 10px; /* Add padding if needed */
}

.brand {
    justify-self: start;
    font-size: 1.5em;
    font-weight: bold;
}

.title {
    justify-self: center;
    font-size: 1.2em;
}

.menu {
    display: flex;
    justify-content: flex-end;
    font-size: 1.5em;
    cursor: pointer;
}

.menu:hover {
    color: #ddd;
}
</style>