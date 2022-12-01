
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M17.74,7.24v3.83A11.48,11.48,0,0,1,6.26,22.54h0V7.24"/><circle class="cls-1" cx="12" cy="7.24" r="5.74"/><path class="cls-1" d="M3.39,1.5h0A3.83,3.83,0,0,0,7.22,5.33h1A3.82,3.82,0,0,1,12,9.15h0"/><path class="cls-1" d="M20.61,1.5h0a3.83,3.83,0,0,1-3.83,3.83h-1A3.82,3.82,0,0,0,12,9.15h0"/><line class="cls-1" x1="16.78" y1="23.5" x2="16.78" y2="15.67"/><line class="cls-1" x1="12.96" y1="20.63" x2="12.96" y2="23.5"/></svg>
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