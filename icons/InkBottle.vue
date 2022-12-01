
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="ink"><rect class="cls-1" x="8.18" y="14.86" width="7.64" height="3.82"/><path class="cls-1" d="M8.18,5.32v4.77A9.22,9.22,0,0,0,1.5,19v1.64A1.9,1.9,0,0,0,3.41,22.5H20.59a1.9,1.9,0,0,0,1.91-1.91V19a9.22,9.22,0,0,0-6.68-8.86V5.32"/><rect class="cls-1" x="6.27" y="1.5" width="11.45" height="3.82"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>