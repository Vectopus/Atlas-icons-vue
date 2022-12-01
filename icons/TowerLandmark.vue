
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="13.92" y1="17.75" x2="13.92" y2="23.5"/><line class="cls-1" x1="10.08" y1="23.5" x2="10.08" y2="17.75"/><path class="cls-1" d="M5.29,23.5V20.94a6.87,6.87,0,0,1,6.71-7h0a6.87,6.87,0,0,1,6.71,7V23.5"/><path class="cls-1" d="M6.25,17.33V14.88a5.74,5.74,0,0,1,9.81-4.07,5.69,5.69,0,0,1,1.69,4.07v2.45"/><path class="cls-1" d="M8.17,10.6V9.12a3.83,3.83,0,1,1,7.66,0V10.6"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="5.29"/><rect class="cls-1" x="11.04" y="4.33" width="1.92" height="0.96"/></svg>
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