
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="6.27" width="12.41" height="16.23" rx="2.86"/><circle class="cls-2" cx="5.32" cy="10.09" r="0.95"/><line class="cls-3" x1="5.32" y1="14.86" x2="1.5" y2="14.86"/><line class="cls-3" x1="10.09" y1="14.86" x2="13.91" y2="14.86"/><line class="cls-3" x1="5.32" y1="18.68" x2="1.5" y2="18.68"/><line class="cls-3" x1="10.09" y1="18.68" x2="13.91" y2="18.68"/><path class="cls-3" d="M9.14,6.27h0A4.77,4.77,0,0,1,13.91,1.5h1.91a4.78,4.78,0,0,1,4.77,4.77v9.55"/><path class="cls-3" d="M20.59,14.86h0a1.91,1.91,0,0,1,1.91,1.91v1.91a0,0,0,0,1,0,0H18.68a0,0,0,0,1,0,0V16.77A1.91,1.91,0,0,1,20.59,14.86Z"/><rect class="cls-3" x="19.64" y="18.68" width="1.91" height="1.91"/></svg>
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
    .cls-1,.cls-3{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-1{stroke-linecap:round;}.cls-2{fill:currentColor;}
</style>