
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="6.64 4.18 10.66 8.2 17.36 1.5"/><path class="cls-1" d="M14.87,20.63A2.88,2.88,0,0,0,12,17.76h0a2.88,2.88,0,0,0-2.87,2.87V23.5"/><circle class="cls-1" cx="12" cy="13.93" r="1.91"/><circle class="cls-1" cx="19.65" cy="15.85" r="1.91"/><path class="cls-1" d="M1.48,23.5v-1a2.87,2.87,0,0,1,2.87-2.87h0a2.88,2.88,0,0,1,2.87,2.87v1"/><path class="cls-1" d="M16.78,23.5v-1a2.88,2.88,0,0,1,2.87-2.87h0a2.87,2.87,0,0,1,2.87,2.87v1"/><circle class="cls-1" cx="4.35" cy="15.85" r="1.91"/><line class="cls-1" x1="14.87" y1="20.63" x2="14.87" y2="23.5"/></svg>
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