<script>
export default {
    name: 'Navlink',
    props: ['url', 'text']
}
</script>

<template>
    <a :href="url">{{ text }}</a>
</template>

<style>
a {
    text-decoration: none;
}
</style>