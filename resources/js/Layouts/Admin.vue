<template>
    <div class="page">
        <!-- Sidebar -->
        <Sidebar />
        <!-- Navbar -->
        <Navbar />

        <div class="page-wrapper">
            <slot />
            <Footer />
        </div>
    </div>
</template>

<script>
import { Link } from "@inertiajs/inertia-vue3";
//import navbar
import Navbar from "../Components/Navbar.vue";

//import sidebar
import Sidebar from '../Components/Sidebar.vue';

//omport Footer
import Footer from "../Components/Footer.vue";
export default {

    //register components
    components: {
        Navbar,
        Sidebar,
        Footer
    },
}

</script>

<style></style>