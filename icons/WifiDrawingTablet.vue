
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.48" width="21" height="15.27" rx="1.91"/><circle class="cls-2" cx="5.32" cy="9.11" r="1.43"/><line class="cls-3" x1="4.36" y1="5.3" x2="6.27" y2="5.3"/><line class="cls-3" x1="4.36" y1="12.93" x2="6.27" y2="12.93"/><path class="cls-2" d="M1.5,21.05l2.86-.48a1,1,0,0,1,.32,1.91c0,.09-3-.47-3.18-.48a.48.48,0,0,1,0-.95Z"/><line class="cls-1" x1="22.5" y1="21.52" x2="4.36" y2="21.52"/><circle class="cls-2" cx="13.91" cy="12.93" r="0.95"/><path class="cls-3" d="M11.52,10.55a3.38,3.38,0,0,1,4.78,0"/><path class="cls-3" d="M9.14,8.16a6.74,6.74,0,0,1,9.54,0"/></svg>
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