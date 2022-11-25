<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
        <NuxtLink to="/" class="navbar-brand" href="#">NUXT</NuxtLink>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <NuxtLink to="/contacts" class="nav-link active" aria-current="page" href="#">Contacts</NuxtLink>
                </li>
                <li class="nav-item">
                    <NuxtLink to="/about" class="nav-link" href="#">About</NuxtLink>
                </li>
            </ul>
        </div>
    </div>
    </nav>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>