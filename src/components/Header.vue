<template>
    <header class="flex justify-between p-6 bg-slate-100 shadow-md">
        <RouterLink to="/">Logo</RouterLink>
        <nav class="space-x-2">
            <RouterLink class="hover:text-gray-500" to="/about">About</RouterLink>
            <RouterLink class="hover:text-gray-500" to="/register">Register</RouterLink>
        </nav>
    </header>
</template>
<script>
export default {

}
</script>