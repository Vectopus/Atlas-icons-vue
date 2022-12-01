
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><polyline class="cls-1" points="16.75 15.87 19.63 12.99 22.51 15.87"/><path class="cls-1" d="M15.79,20.66h0a3.84,3.84,0,0,0,3.84-3.83V13"/><polyline class="cls-1" points="7.16 8.19 4.28 11.07 1.41 8.19"/><path class="cls-1" d="M8.12,3.4h0A3.84,3.84,0,0,0,4.28,7.23v3.84"/><path class="cls-1" d="M20.59,5.32h-1v-1a2.88,2.88,0,1,0-5.75,0H13.4a2.4,2.4,0,1,0,0,4.79h7.19a1.92,1.92,0,1,0,0-3.83Z"/><path class="cls-1" d="M11,18.74H10v-1a2.88,2.88,0,0,0-5.76,0H3.8a2.4,2.4,0,0,0,0,4.8H11a1.92,1.92,0,1,0,0-3.84Z"/></g></svg>
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