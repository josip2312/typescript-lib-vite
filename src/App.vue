<script setup lang="ts">

    // import { MyButton } from 'my-component-lib';
    // import '/node_modules/my-component-lib/dist/style.css';
    import MyButton from '@/components/MyButton.vue'

</script>


<template>
    <div>
        <div style="padding-bottom:20px;">button test</div>
        <MyButton>Testing</MyButton>
    </div>
</template>


<style>

    @import './assets/base.css';

    #app {
        max-width: 1280px;
        margin: 0 auto;
        padding: 2rem;
        font-weight: normal;
    }

</style>
