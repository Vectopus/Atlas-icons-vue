
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="package_1" data-name="package 1"><polygon class="cls-1" points="18.68 1.5 5.32 1.5 1.5 8.18 1.5 22.5 22.5 22.5 22.5 8.18 18.68 1.5"/><line class="cls-1" x1="4.36" y1="18.68" x2="8.18" y2="18.68"/><line class="cls-1" x1="12" y1="1.5" x2="12" y2="12"/><line class="cls-1" x1="1.5" y1="8.18" x2="22.5" y2="8.18"/></g></svg>
</template>
<script>
    export default {
        props: {
            size: {
                type: Number,
                default: 24,
                required: false,
            },
            weight: {
                type: Number,
                default: 2,
                required: false,
            },
        }
    }
</script>
<style scoped>
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>