
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.4,22.5H9.6a4.7,4.7,0,0,1-.92-.09l-.57-.12a4.65,4.65,0,0,1-3.75-4.56h-1A1.92,1.92,0,0,1,1.5,15.82V12a1.92,1.92,0,0,1,1.91-1.91h1V7.23A1.91,1.91,0,0,1,6.27,5.32H17.73a1.91,1.91,0,0,1,1.91,1.91v2.86h.95A1.92,1.92,0,0,1,22.5,12v3.82a1.92,1.92,0,0,1-1.91,1.91h-.95a4.65,4.65,0,0,1-3.75,4.56l-.57.12A4.7,4.7,0,0,1,14.4,22.5Z"/><path class="cls-1" d="M17.73,5.32H6.27l.2-.4A6.18,6.18,0,0,1,12,1.5h0a6.18,6.18,0,0,1,5.53,3.42Z"/><line class="cls-1" x1="9.14" y1="8.18" x2="14.86" y2="8.18"/><path class="cls-1" d="M6.27,13v1a1.92,1.92,0,0,0,1.91,1.91h0A3.82,3.82,0,0,0,12,19.64h0a3.82,3.82,0,0,0,3.82-3.82h0a1.92,1.92,0,0,0,1.91-1.91V13a1.91,1.91,0,0,0-1.91-1.9H8.18A1.91,1.91,0,0,0,6.27,13Z"/></svg>
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