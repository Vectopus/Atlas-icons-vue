
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.86,19.66A2.86,2.86,0,0,0,12,16.8h0a2.86,2.86,0,0,0-2.86,2.86v2.86"/><circle class="cls-1" cx="12" cy="12.98" r="1.91"/><circle class="cls-1" cx="19.64" cy="14.89" r="1.91"/><path class="cls-1" d="M1.5,22.52v-.95A2.87,2.87,0,0,1,4.36,18.7h0a2.87,2.87,0,0,1,2.87,2.87v.95"/><path class="cls-1" d="M16.77,22.52v-.95a2.87,2.87,0,0,1,2.87-2.87h0a2.87,2.87,0,0,1,2.86,2.87v.95"/><circle class="cls-1" cx="4.36" cy="14.89" r="1.91"/><line class="cls-1" x1="14.86" y1="19.66" x2="14.86" y2="22.52"/><polygon class="cls-1" points="12 2.48 12.46 3.42 13.51 3.57 12.75 4.3 12.93 5.34 12 4.85 11.07 5.34 11.25 4.3 10.49 3.57 11.54 3.42 12 2.48"/><polygon class="cls-1" points="19.64 5.34 20.1 6.28 21.14 6.43 20.39 7.17 20.57 8.21 19.64 7.71 18.71 8.21 18.88 7.17 18.13 6.43 19.17 6.28 19.64 5.34"/><polygon class="cls-1" points="4.36 5.34 4.83 6.28 5.87 6.43 5.12 7.17 5.29 8.21 4.36 7.71 3.43 8.21 3.61 7.17 2.86 6.43 3.9 6.28 4.36 5.34"/></svg>
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