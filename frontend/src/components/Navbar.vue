<template>
<div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">APP</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <router-link to="/dashboard" class="nav-link active">dashboard</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/" class="nav-link active">Home</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/about" class="nav-link ">About</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/login" class="nav-link ">Login</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/register" class="nav-link ">Register</router-link>
                    </li>

                </ul>
            </div>
        </div>
    </nav>
</div>
</template>

<script>
export default {
    name: "Navbar"
}
</script>

<style scoped>

</style>
