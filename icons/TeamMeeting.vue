
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.3,23.5a2.88,2.88,0,0,1,2.87-2.87h0A2.87,2.87,0,0,1,11,23.5"/><circle class="cls-1" cx="8.17" cy="16.8" r="1.91"/><path class="cls-1" d="M13,23.5a2.87,2.87,0,0,1,2.87-2.87h0A2.88,2.88,0,0,1,18.7,23.5"/><circle class="cls-1" cx="15.83" cy="16.8" r="1.91"/><path class="cls-1" d="M5.3,10.11A2.87,2.87,0,0,1,8.17,7.24h0A2.86,2.86,0,0,1,11,10.11"/><circle class="cls-1" cx="8.17" cy="3.41" r="1.91"/><path class="cls-1" d="M13,10.11a2.86,2.86,0,0,1,2.87-2.87h0a2.87,2.87,0,0,1,2.87,2.87"/><circle class="cls-1" cx="15.83" cy="3.41" r="1.91"/><path class="cls-1" d="M4.35,19.28a4.78,4.78,0,0,1,1.91-9.17H17.74a4.79,4.79,0,0,1,3.39,8.17,5,5,0,0,1-1.48,1"/></svg>
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