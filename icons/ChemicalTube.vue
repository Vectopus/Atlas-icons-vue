
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.83,22.5h0a3.38,3.38,0,0,1-3.38-3.37h0a3.38,3.38,0,0,1,1-2.39L13.91,6.27l4.77,4.78L8.22,21.51A3.42,3.42,0,0,1,5.83,22.5Z"/><line class="cls-1" x1="12.48" y1="4.84" x2="20.11" y2="12.48"/><path class="cls-1" d="M17.25,1.5a2.37,2.37,0,0,0,0,2.86,2.39,2.39,0,0,1,0,2.87"/><path class="cls-1" d="M21.07,3.41a2.37,2.37,0,0,0,0,2.86,2.42,2.42,0,0,1,0,2.87"/><line class="cls-1" x1="6.27" y1="13.91" x2="15.82" y2="13.91"/></svg>
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