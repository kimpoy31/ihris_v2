<script setup lang="ts">
    import ScreenContainer from "@/Layouts/ScreenContainer.vue";
    import Navbar from "@/Components/Navbar.vue";
</script>

<template>
    <ScreenContainer>
        <div>
            <Navbar />
        </div>
        <div>
            <slot />
        </div>
    </ScreenContainer>
</template>