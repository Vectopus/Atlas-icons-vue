
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="medical_sign" data-name="medical sign"><polygon class="cls-1" points="9.14 1.5 8.18 1.5 8.18 8.18 1.5 8.18 1.5 15.82 8.18 15.82 8.18 22.5 15.82 22.5 15.82 15.82 22.5 15.82 22.5 8.18 15.82 8.18 15.82 1.5 12.96 1.5 9.14 1.5"/><polyline class="cls-1" points="19.64 12 7.23 12 6.27 12 4.36 12"/><line class="cls-1" x1="12" y1="4.36" x2="12" y2="19.64"/></g></svg>
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