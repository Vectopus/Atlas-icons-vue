
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="0.5" x2="12" y2="5.29"/><line class="cls-1" x1="12" y1="18.71" x2="12" y2="23.5"/><line class="cls-1" x1="23.5" y1="12" x2="18.71" y2="12"/><line class="cls-1" x1="5.29" y1="12" x2="0.5" y2="12"/><circle class="cls-1" cx="12" cy="12" r="9.58"/><path class="cls-1" d="M9.12,16.79A2.87,2.87,0,0,1,12,13.92h0a2.87,2.87,0,0,1,2.88,2.87"/><circle class="cls-1" cx="12" cy="10.08" r="1.92"/></svg>
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