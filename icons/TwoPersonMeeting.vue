
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.13,23.5A2.88,2.88,0,0,1,12,20.63h0a2.88,2.88,0,0,1,2.87,2.87"/><circle class="cls-1" cx="12" cy="16.8" r="1.91"/><path class="cls-1" d="M9.13,10.11A2.87,2.87,0,0,1,12,7.24h0a2.87,2.87,0,0,1,2.87,2.87"/><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><polyline class="cls-1" points="15.83 19.67 21.57 19.67 19.65 11.06 4.35 11.06 2.44 19.67 8.17 19.67"/></svg>
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