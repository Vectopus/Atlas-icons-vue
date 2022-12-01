
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="20 8.5 20 22.5 4 22.5 4 8.5"/><polyline class="cls-1" points="23 10.5 12 1.5 1 10.5"/><circle class="cls-1" cx="12" cy="18.5" r="1"/><path class="cls-1" d="M9.17,15.67a4,4,0,0,1,5.66,0"/><path class="cls-1" d="M7.05,13.55a7,7,0,0,1,9.9,0"/></svg>
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