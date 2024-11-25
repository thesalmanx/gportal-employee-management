<template>
    <div class="container my-5 text-center">
        <div class="jumbotron p-5 rounded-lg shadow-sm">
            <h1 class="display-3 fw-bold mb-3 portal-heading">Welcome to GPortal</h1>
            <h2 class="display-6 text-muted">Effortless Employee Management at Your Fingertips</h2>
            <p class="lead mt-2">
                <strong>Quickly: </strong> Add, update, view, and organize employee details in one place with ease and
                efficiency.
            </p>
            <hr class="my-4">
            <a href="#features" class="btn btn-get-started btn-lg mt-3">Get Started</a>
        </div>
    </div>
</template>

<script>
export default {
    name: "HomePage",
};
</script>

<style scoped>
.container {
    animation: fadeIn 1s ease-in-out;
}

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(20px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.jumbotron {
    background: #f1f5f9;
    border-radius: 20px;
}

.portal-heading {
    color: #4a5568;
}

h2 {
    color: #6c757d;
}

.lead {
    font-size: 1.2em;
    color: #4a5568;
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
</style>
