
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="7.2" cy="12" r="5.73"/><path class="cls-1" d="M9.11,12A1.91,1.91,0,1,1,7.2,10.09"/><polyline class="cls-1" points="2.43 8.84 3.38 1.5 11.02 1.5 11.97 8.84"/><polyline class="cls-1" points="11.97 15.16 11.02 22.5 3.38 22.5 2.43 15.16"/><line class="cls-1" x1="14.84" y1="12" x2="12.93" y2="12"/><path class="cls-1" d="M16.58,9.3a3.82,3.82,0,0,1,0,5.4"/><path class="cls-1" d="M19.13,6.75a7.42,7.42,0,0,1,0,10.5"/></svg>
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