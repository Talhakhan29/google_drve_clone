<template>
    <div class="h-screen bg-gray-50 flex w-full gap-4">
        <Navigation/>

    </div>
</template>

<script setup>
import { ref } from 'vue';
import ApplicationLogo from '@/Components/ApplicationLogo.vue';
import Dropdown from '@/Components/Dropdown.vue';
import DropdownLink from '@/Components/DropdownLink.vue';
import NavLink from '@/Components/NavLink.vue';
import ResponsiveNavLink from '@/Components/ResponsiveNavLink.vue';
import { Link } from '@inertiajs/vue3';
import Navigation from '@/components/Navigation.vue';

const showingNavigationDropdown = ref(false);
</script>
