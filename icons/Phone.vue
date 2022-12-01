
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.32" y="1.5" width="13.36" height="21" rx="1.91"/><path class="cls-2" d="M9.14,1.5h5.73a0,0,0,0,1,0,0v1a1,1,0,0,1-1,1H10.09a1,1,0,0,1-1-1v-1A0,0,0,0,1,9.14,1.5Z"/><line class="cls-1" x1="11.05" y1="19.64" x2="12.95" y2="19.64"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>