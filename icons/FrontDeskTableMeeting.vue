
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="6.25 23.52 6.25 15.85 5.29 13.94 5.29 7.23 11.04 7.23 11.04 13.94 10.08 15.85 10.08 23.52"/><path class="cls-1" d="M13.92,11.06v-1a2.87,2.87,0,0,1,2.87-2.87h0a2.88,2.88,0,0,1,2.88,2.87v1"/><circle class="cls-1" cx="16.79" cy="3.4" r="1.92"/><circle class="cls-1" cx="8.17" cy="3.4" r="1.92"/><polyline class="cls-1" points="21.58 23.52 21.58 12.02 11.04 12.02"/><polyline class="cls-1" points="5.29 12.02 2.42 12.02 2.42 23.52"/><polyline class="cls-1" points="23.5 12.02 21.58 12.02 11.04 12.02"/><polyline class="cls-1" points="5.29 12.02 2.42 12.02 0.5 12.02"/></svg>
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