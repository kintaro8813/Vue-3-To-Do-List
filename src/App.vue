<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import TodoList from "./components/TodoList.vue";
</script>

<template>
    <div class="min-h-screen bg-slate-900 py-5">
        <div class="container mx-auto px-4">
            <h1 class="text-white text-center text-3xl font-bold mb-6">Vue 3 - Todo List with Drag & Drop</h1>
            <hr class="mb-6">
            <TodoList />
        </div>
    </div>
</template>
