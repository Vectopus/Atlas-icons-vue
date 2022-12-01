
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M17.73,7.23v7.63a1.92,1.92,0,0,1-1.91,1.91H8.18a1.92,1.92,0,0,1-1.91-1.91V7.23A5.74,5.74,0,0,1,12,1.5a5.65,5.65,0,0,1,2,.35,2.46,2.46,0,0,0-.07.6,2.86,2.86,0,0,0,2.86,2.87,2.46,2.46,0,0,0,.6-.07A5.61,5.61,0,0,1,17.73,7.23Z"/><path class="cls-1" d="M10.09,16.77h3.82a0,0,0,0,1,0,0v3.82A1.91,1.91,0,0,1,12,22.5h0a1.91,1.91,0,0,1-1.91-1.91V16.77a0,0,0,0,1,0,0Z"/></svg>
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