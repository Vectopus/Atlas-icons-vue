
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M8.18,16.8,5,13.57A2,2,0,0,0,3.52,13h0a2,2,0,0,0-2,2h0a2,2,0,0,0,.59,1.43l4.18,4.18H20.59A1.9,1.9,0,0,0,22.5,18.7h0a1.9,1.9,0,0,0-1.91-1.9Z"/><line class="cls-1" x1="6.27" y1="23.48" x2="6.27" y2="20.61"/><line class="cls-1" x1="19.64" y1="23.48" x2="19.64" y2="20.61"/><polygon class="cls-1" points="20.59 8.21 3.41 8.21 12 1.52 20.59 8.21"/><line class="cls-1" x1="12" y1="16.8" x2="12" y2="8.2"/><line class="cls-1" x1="12" y1="23.48" x2="12" y2="20.61"/></svg>
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