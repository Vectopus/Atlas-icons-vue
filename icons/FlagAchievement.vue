
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="10.11 22.5 17.75 22.5 16.8 18.68 11.07 18.68 10.11 22.5"/><line class="cls-1" x1="20.61" y1="22.5" x2="7.25" y2="22.5"/><polyline class="cls-1" points="13.93 18.68 13.93 1.5 4.39 1.5 4.39 8.18 13.93 8.18"/></svg>
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