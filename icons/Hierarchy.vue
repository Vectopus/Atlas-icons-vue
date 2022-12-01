
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="sitemap"><rect class="cls-1" x="9.14" y="1.5" width="5.73" height="5.73"/><rect class="cls-1" x="10.09" y="18.68" width="3.82" height="3.82"/><rect class="cls-1" x="1.5" y="18.68" width="3.82" height="3.82"/><rect class="cls-1" x="18.68" y="18.68" width="3.82" height="3.82"/><line class="cls-1" x1="12" y1="18.68" x2="12" y2="8.18"/><polyline class="cls-1" points="3.41 18.68 3.41 12.96 20.59 12.96 20.59 18.68"/></g></svg>
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