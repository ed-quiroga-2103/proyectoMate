<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-contrast-custom nav-height">
        <div class="container-fluid">
            <a class="navbar-brand">Instituto Tecnológico de Costa Rica</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
                <router-link class="nav-link" active-class="active" to="/home">Home</router-link>
                <router-link class="nav-link" active-class="active" to="/about">About</router-link>
                <router-link class="nav-link" active-class="active" to="/contact">Contact</router-link>
                <a class="nav-link disabled" tabindex="-1" aria-disabled="true">Disabled</a>
            </div>
            <div class="d-flex ms-auto p-2">
                <button class="btn btn-outline-primary" type="submit">Log In!</button>
            </div>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'navbar', 
}
</script>

<style>

.nav-height{
    height: 5vh;
}

</style>