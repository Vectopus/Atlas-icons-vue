
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.37,9.18a2,2,0,0,0-1.59,2h0A2.76,2.76,0,0,1,14,13.93H10a2.76,2.76,0,0,1-2.76-2.76h0a2,2,0,0,0-1.59-2,1.91,1.91,0,0,0-2.24,1.89h0a6.7,6.7,0,0,0,6.7,6.69h3.82a6.7,6.7,0,0,0,6.7-6.69h0A1.91,1.91,0,0,0,18.37,9.18Z"/><path class="cls-1" d="M6.26,9.42V7.24a5.74,5.74,0,1,1,11.48,0V9.42"/><line class="cls-1" x1="6.26" y1="23.5" x2="7.22" y2="16.8"/><line class="cls-1" x1="16.78" y1="16.8" x2="17.74" y2="23.5"/></svg>
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