<script setup>
    import HeaderView from '@/components/HeaderView.vue';
    import { RouterLink,RouterView } from 'vue-router';
    import FormLoginView from '@/components/FormLoginView.vue';
    import Footerview from '@/components/FooterView.vue';
</script>

<template>
    <main>
        <HeaderView/>
        <FormLoginView/>
        <Footerview/>
    </main>
</template>