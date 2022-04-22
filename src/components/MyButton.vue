<script setup lang="ts">

    type MyButtonProps = {
        primary?: boolean;
    }

    const props = withDefaults(defineProps<MyButtonProps>(), {
        primary: false,
    });

</script>


<template>

    <button class="btn" :class="primary">
        <slot/>
    </button>

</template>


<style scoped>

    .btn {
        padding: 0.5rem 1rem;
    }
    .btn.primary {
        background: hsl(239, 100%, 27%);
        color: #fff;
    }

</style>
