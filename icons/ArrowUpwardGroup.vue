
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.78,23.5a2.88,2.88,0,0,1,2.87-2.87h0a2.87,2.87,0,0,1,2.87,2.87"/><circle class="cls-1" cx="19.65" cy="16.8" r="1.91"/><path class="cls-1" d="M9.13,23.5A2.88,2.88,0,0,1,12,20.63h0a2.88,2.88,0,0,1,2.87,2.87"/><circle class="cls-1" cx="12" cy="16.8" r="1.91"/><path class="cls-1" d="M1.48,23.5a2.87,2.87,0,0,1,2.87-2.87h0A2.88,2.88,0,0,1,7.22,23.5"/><circle class="cls-1" cx="4.35" cy="16.8" r="1.91"/><polyline class="cls-1" points="4.35 11.06 10.09 5.33 12.96 8.2 19.65 1.5"/><polyline class="cls-1" points="15.83 1.5 19.65 1.5 19.65 5.33"/></svg>
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