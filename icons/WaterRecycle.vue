
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.84,2.52a10.49,10.49,0,0,1,2.69,1.95,10.64,10.64,0,0,1-5.78,18"/><path class="cls-1" d="M7.16,21.48a10.49,10.49,0,0,1-2.69-1.95,10.64,10.64,0,0,1,5.78-18"/><polyline class="cls-1" points="16.84 6.19 16.84 2.32 20.71 2.32"/><polyline class="cls-1" points="7.16 17.81 7.16 21.68 3.29 21.68"/><path class="cls-1" d="M15.73,13.11a3.73,3.73,0,0,1-7.46,0C8.27,9.92,12,6.19,12,6.19S15.73,9.92,15.73,13.11Z"/></svg>
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