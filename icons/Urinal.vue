
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="7.21" y1="0.5" x2="7.21" y2="23.5"/><path class="cls-1" d="M16.79,17.75A4.8,4.8,0,0,1,12,13V8.65a2.39,2.39,0,0,0-2.4-2.4h0a2.39,2.39,0,0,0-2.39,2.4h0v9.1A4.78,4.78,0,0,0,12,22.54h0a4.78,4.78,0,0,0,4.79-4.79Z"/><path class="cls-1" d="M9.12,2.5A1.91,1.91,0,0,1,11,4.41V6.25"/></svg>
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