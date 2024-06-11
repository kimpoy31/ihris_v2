<script setup lang="ts">
    import { Link } from '@inertiajs/vue3'
</script>

<template>
    <div class="navbar bg-base-100 gap-2 flex justify-between">
        <div>
            <Link class="btn btn-ghost btn-square" href="/"><img src="/images/bayawanSeal.png" alt="bayawanSeal" class="max-w-10"></Link>
            <div class="font-bold hidden sm:block">LOCAL GOVERNMENT OF BAYAWAN CITY</div>
            <div class="font-bold text-xs block sm:hidden">LGU BAYAWAN CITY</div>
        </div>
        <div>
            <Link href="/login" class="btn btn-ghost btn-sm">Register</Link>
            <Link href="/login" class="btn btn-primary btn-outline btn-sm">Login</Link>
        </div>
    </div>
</template>