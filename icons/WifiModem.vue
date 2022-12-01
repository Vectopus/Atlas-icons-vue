
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="14.86" width="21" height="7.64" rx="1.91"/><path class="cls-1" d="M6.27,18.68h0Z"/><path class="cls-1" d="M10.09,18.68h0Z"/><line class="cls-1" x1="19.64" y1="18.68" x2="12" y2="18.68"/><line class="cls-1" x1="4.36" y1="3.41" x2="4.36" y2="14.86"/><circle class="cls-1" cx="4.36" cy="2.45" r="0.95"/><circle class="cls-2" cx="9.14" cy="11.05" r="0.95"/><path class="cls-1" d="M8.18,7.23A4.76,4.76,0,0,1,13,12"/><path class="cls-1" d="M8.18,3.41A8.59,8.59,0,0,1,16.77,12"/></svg>
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