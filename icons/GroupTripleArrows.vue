
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="15.82" r="1.91"/><circle class="cls-1" cx="19.64" cy="15.82" r="1.91"/><path class="cls-1" d="M1.5,22.5a2.86,2.86,0,0,1,2.86-2.86h0A2.86,2.86,0,0,1,7.23,22.5"/><path class="cls-1" d="M16.77,22.5a2.86,2.86,0,0,1,2.87-2.86h0A2.86,2.86,0,0,1,22.5,22.5"/><circle class="cls-1" cx="4.36" cy="15.82" r="1.91"/><path class="cls-1" d="M14.86,22.5A2.86,2.86,0,0,0,12,19.64h0A2.86,2.86,0,0,0,9.14,22.5"/><polyline class="cls-1" points="9.14 4.36 12 1.5 14.86 4.36"/><polyline class="cls-1" points="18.68 4.36 21.55 7.23 18.68 10.09"/><line class="cls-1" x1="12" y1="12" x2="12" y2="1.5"/><path class="cls-1" d="M21.55,7.23H17.73a2.87,2.87,0,0,0-2.87,2.86V13"/><polyline class="cls-1" points="5.32 4.36 2.46 7.23 5.32 10.09"/><path class="cls-1" d="M2.45,7.23H6.27a2.87,2.87,0,0,1,2.87,2.86V13"/></svg>
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