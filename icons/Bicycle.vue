
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="5.32" cy="14.86" r="3.82"/><circle class="cls-1" cx="18.68" cy="14.86" r="3.82"/><polygon class="cls-2" points="12 14.86 5.32 14.86 8.18 8.18 15.82 8.18 12 14.86"/><path class="cls-1" d="M18.68,14.86,15.82,8.18V5.32h1.91a1.91,1.91,0,0,1,1.91,1.91h0"/><line class="cls-1" x1="8.18" y1="5.32" x2="8.18" y2="8.18"/><line class="cls-1" x1="6.27" y1="5.32" x2="10.09" y2="5.32"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;}.cls-1{stroke-miterlimit:10;}.cls-2{stroke-linejoin:bevel;}
</style>