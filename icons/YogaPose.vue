
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="4.37" r="2.87"/><polyline class="cls-1" points="9.13 23.5 9.13 9.15 14.87 9.15 14.87 23.5"/><polyline class="cls-1" points="14.87 15.85 21.57 18.72 21.57 20.63 12.96 20.63"/><polyline class="cls-1" points="9.13 15.85 2.44 18.72 2.44 20.63 11.04 20.63"/></svg>
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