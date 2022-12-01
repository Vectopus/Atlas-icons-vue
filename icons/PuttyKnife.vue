
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.09,15.82h3.82a0,0,0,0,1,0,0v4.77A1.91,1.91,0,0,1,12,22.5h0a1.91,1.91,0,0,1-1.91-1.91V15.82A0,0,0,0,1,10.09,15.82Z"/><path class="cls-1" d="M12,1.5h0a1.46,1.46,0,0,0-1.34.87L7.35,9.81a1.48,1.48,0,0,0-.12.59v.13A1.47,1.47,0,0,0,8.7,12h6.6a1.47,1.47,0,0,0,1.47-1.47V10.4a1.48,1.48,0,0,0-.12-.59L13.34,2.37A1.46,1.46,0,0,0,12,1.5Z"/><line class="cls-1" x1="12" y1="8.18" x2="12" y2="15.82"/></svg>
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