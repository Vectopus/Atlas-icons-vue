
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.13,23.5A2.88,2.88,0,0,1,12,20.63h0a2.88,2.88,0,0,1,2.87,2.87"/><circle class="cls-1" cx="12" cy="16.8" r="1.91"/><path class="cls-1" d="M10.93,7.45a2.83,2.83,0,0,1,2.14,0"/><path class="cls-1" d="M18.58,7.45a3,3,0,0,1,1.07-.21,2.87,2.87,0,0,1,2.87,2.87"/><path class="cls-1" d="M1.48,10.11A2.86,2.86,0,0,1,4.35,7.24a3,3,0,0,1,1.07.21"/><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><circle class="cls-1" cx="19.65" cy="3.41" r="1.91"/><path class="cls-1" d="M5.3,16.8a2.88,2.88,0,0,1,2.87-2.87,2.78,2.78,0,0,1,1.08.22"/><path class="cls-1" d="M14.75,14.15a2.78,2.78,0,0,1,1.08-.22A2.9,2.9,0,0,1,18.7,16.8"/><circle class="cls-1" cx="8.17" cy="10.11" r="1.91"/><circle class="cls-1" cx="15.83" cy="10.11" r="1.91"/><circle class="cls-1" cx="4.35" cy="3.41" r="1.91"/></svg>
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