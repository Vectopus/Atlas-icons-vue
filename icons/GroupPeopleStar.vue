
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.86,20.66A2.86,2.86,0,0,0,12,17.8h0a2.86,2.86,0,0,0-2.86,2.86v2.86"/><circle class="cls-1" cx="12" cy="13.98" r="1.91"/><circle class="cls-1" cx="19.64" cy="15.89" r="1.91"/><path class="cls-1" d="M1.5,23.52v-.95A2.87,2.87,0,0,1,4.36,19.7h0a2.87,2.87,0,0,1,2.87,2.87v.95"/><path class="cls-1" d="M16.77,23.52v-.95a2.87,2.87,0,0,1,2.87-2.87h0a2.87,2.87,0,0,1,2.86,2.87v.95"/><circle class="cls-1" cx="4.36" cy="15.89" r="1.91"/><line class="cls-1" x1="14.86" y1="20.66" x2="14.86" y2="23.52"/><polygon class="cls-1" points="12 3.48 12.46 4.42 13.51 4.57 12.75 5.3 12.93 6.34 12 5.85 11.07 6.34 11.25 5.3 10.49 4.57 11.54 4.42 12 3.48"/></svg>
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