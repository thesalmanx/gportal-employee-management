<template>
    <div>
        <nav class="navbar navbar-expand-md custom-navbar">
            <div class="container-fluid">
                <span class="navbar-brand mb-0 h1 portal-title">GPortal</span>

                <ul class="navbar-nav mx-auto">
                    <li class="nav-item mx-2">
                        <router-link class="nav-link btn btn-custom" to="/home">Home</router-link>
                    </li>
                    <li class="nav-item mx-2">
                        <router-link class="nav-link btn btn-custom" to="/department">Department</router-link>
                    </li>
                    <li class="nav-item mx-2">
                        <router-link class="nav-link btn btn-custom" to="/employee">Employee</router-link>
                    </li>
                </ul>

                <router-link to="/get-started" class="btn btn-get-started">Get Started</router-link>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    name: "NavBar",
};
</script>

<style scoped>
.custom-navbar {
    background-color: #f1f5f9;
    border-radius: 20px;
    margin-top: 10px;
    padding: 1rem;
    display: flex;
    align-items: center;
}

.portal-title {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5rem;
    color: #4a5568;
    font-weight: 600;
}

.btn-custom {
    background-color: #e2e8f0;
    color: #2b6cb0;
    font-weight: 500;
    border: none;
    border-radius: 8px;
    padding: 0.5rem 1.25rem;
    font-size: 1rem;
    transition: background-color 0.3s ease, color 0.3s ease;
}

.btn-custom:hover {
    background-color: #cbd5e0;
    color: #2c5282;
}

.btn-get-started {
    background-color: #4f46e5;
    color: white;
    font-weight: 600;
    border: none;
    border-radius: 8px;
    padding: 0.5rem 1.5rem;
    font-size: 1rem;
    transition: background-color 0.3s ease;
}

.btn-get-started:hover {
    background-color: #4338ca;
}

.navbar-nav {
    display: flex;
    align-items: center;
}

.navbar-nav .nav-link {
    color: inherit;
    text-decoration: none;
}
</style>