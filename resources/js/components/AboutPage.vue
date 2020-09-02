<template>
                <div class="card">
                    <div class="card-header">About Page</div>

                    <div class="card-body">
                        Call laravel route from vue component.
                        <a class="nav-link" :href="route('home')">Go Home</a>
                    </div>
                </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
