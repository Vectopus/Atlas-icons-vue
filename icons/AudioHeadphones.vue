
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.8,13h.48a0,0,0,0,1,0,0v8.59a0,0,0,0,1,0,0H5.8a4.3,4.3,0,0,1-4.3-4.3v0A4.3,4.3,0,0,1,5.8,13Z"/><path class="cls-1" d="M17.73,13h.48a4.3,4.3,0,0,1,4.3,4.3v0a4.3,4.3,0,0,1-4.3,4.3h-.48a0,0,0,0,1,0,0V13a0,0,0,0,1,0,0Z"/><path class="cls-1" d="M3.41,13.91V11.05A8.6,8.6,0,0,1,12,2.45h0a8.6,8.6,0,0,1,8.59,8.6v2.86"/></svg>
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