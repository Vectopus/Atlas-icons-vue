
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.82,11.05l-5.9,6.73a2.63,2.63,0,0,1-2,.9h0a2.62,2.62,0,0,1-2.62-2.62h0a2.63,2.63,0,0,1,.9-2L13,8.18"/><path class="cls-1" d="M18.68,5.32l-2.86,5.73h3.82A2.87,2.87,0,0,0,22.5,8.18h0a2.86,2.86,0,0,0-2.86-2.86Z"/><line class="cls-1" x1="1.5" y1="22.5" x2="5.8" y2="18.2"/><path class="cls-1" d="M13,8.18l5.73-2.86v-1A2.86,2.86,0,0,0,15.82,1.5h0A2.87,2.87,0,0,0,13,4.36V8.18"/><line class="cls-1" x1="7.23" y1="12.95" x2="11.05" y2="16.77"/></svg>
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