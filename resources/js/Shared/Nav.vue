<template>
    <ul>
        <li><Link href="/">Home</Link></li>
        <li><Link href="/users">Users</Link></li>
        <li><Link href="/settings">Settings</Link></li>
    </ul>
</template>

<script>
import { Link } from '@inertiajs/inertia-vue3';

export default {
    name: "Nav",
    components: { Link },
}

</script>

<style scoped>

</style>
