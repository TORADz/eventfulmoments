<script setup>
    import HeaderView from '@/components/HeaderView.vue';
    import { RouterLink,RouterView } from 'vue-router';
    import FormLoginView from '@/components/FormLoginView.vue';
    import Footerview from '@/components/FooterView.vue';
</script>

<template>
    <main>
        <HeaderView/>
        <h2>This is the Login Page</h2>
        <FormLoginView/>
        <Footerview/>
    </main>
</template>