
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.92,21.5v-.95a2.87,2.87,0,0,0-.83-2,2.85,2.85,0,0,0-4,0,2.87,2.87,0,0,0-.83,2H3.5V1.61H18.66V15.82"/><line class="cls-1" x1="15.82" y1="20.55" x2="21.5" y2="20.55"/><line class="cls-1" x1="18.66" y1="17.71" x2="18.66" y2="23.39"/></svg>
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