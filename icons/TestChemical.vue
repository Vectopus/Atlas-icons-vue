
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14,2.52H13.5A12,12,0,0,0,1.61,12.9C1,17.71,4.33,22.32,9.17,22.52A8,8,0,0,0,14.64,8.39.49.49,0,0,1,15,7.52h.37a19.57,19.57,0,0,1,6.16,1h0l1-4A19,19,0,0,0,14,2.52Z"/><path class="cls-1" d="M1.5,12c8.65-2.86,8.65,2.87,16.23,0"/><line class="cls-1" x1="5.32" y1="14.89" x2="7.23" y2="14.89"/><line class="cls-1" x1="8.18" y1="18.71" x2="10.09" y2="18.71"/><line class="cls-1" x1="12" y1="16.8" x2="13.91" y2="16.8"/></svg>
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