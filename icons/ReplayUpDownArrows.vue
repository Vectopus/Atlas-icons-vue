
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="9 6 5 2 1 6"/><polyline class="cls-1" points="15 18 19 22 23 18"/><path class="cls-1" d="M11,6h4a4,4,0,0,1,4,4V22"/><path class="cls-1" d="M13,18H9a4,4,0,0,1-4-4V2"/></svg>
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