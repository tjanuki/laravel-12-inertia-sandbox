<script setup lang="ts">
import { Head, Link } from '@inertiajs/vue3';
</script>

<template>
    <Head title="404 - Page Not Found" />
    <div class="flex flex-col items-center justify-center min-h-screen bg-gray-100">
        <div class="p-8 bg-white rounded-lg shadow-md max-w-md w-full">
            <h1 class="text-4xl font-bold text-red-500 mb-4">404</h1>
            <p class="text-xl text-gray-700 mb-6">Oops! The page you are looking for doesn't exist.</p>
            <Link
                :href="route('home')"
                class="px-4 py-2 bg-blue-500 text-white rounded hover:bg-blue-600 transition-colors"
            >
                Return Home
            </Link>
        </div>
    </div>
</template>
