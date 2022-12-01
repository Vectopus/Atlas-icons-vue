
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="8.58" r="6.83"/><polyline class="cls-1" points="15.9 14.36 15.9 22.25 12 20.3 8.1 22.25 8.1 14.36"/><polyline class="cls-1" points="13.95 7.12 13.95 11.51 10.05 11.51 10.05 7.12"/><polyline class="cls-1" points="8.1 8.58 12 5.66 15.9 8.58"/></svg>
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