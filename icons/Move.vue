
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M7.12,22.75,1.86,17.49A2.08,2.08,0,0,1,1.25,16,2.08,2.08,0,0,1,3.32,14a2.08,2.08,0,0,1,1.47.61l1.35,1.35V6.24A2,2,0,0,1,7.92,4.18a2,2,0,0,1,2.13,2V12l5.17.74a2,2,0,0,1,1.67,1.94h0A17.61,17.61,0,0,1,15,22.57l-.09.18"/><line class="cls-1" x1="13.96" y1="6.13" x2="21.78" y2="6.13"/><line class="cls-1" x1="17.87" y1="2.22" x2="17.87" y2="10.04"/><polygon class="cls-2" points="15.67 2.95 17.87 0.75 20.07 2.95 15.67 2.95"/><polygon class="cls-2" points="21.05 3.93 23.25 6.13 21.05 8.33 21.05 3.93"/><polygon class="cls-2" points="20.07 9.31 17.87 11.51 15.67 9.31 20.07 9.31"/><polygon class="cls-2" points="14.69 8.33 12.49 6.13 14.69 3.93 14.69 8.33"/></svg>
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