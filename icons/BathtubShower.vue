
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M2.42,13.92H21.58a0,0,0,0,1,0,0v2.87a5.75,5.75,0,0,1-5.75,5.75H8.17a5.75,5.75,0,0,1-5.75-5.75V13.92A0,0,0,0,1,2.42,13.92Z"/><rect class="cls-1" x="12" y="13.92" width="4.79" height="4.79"/><line class="cls-1" x1="23.5" y1="13.92" x2="0.5" y2="13.92"/><path class="cls-1" d="M2.42,14.12V4.33A2.87,2.87,0,0,1,5.29,1.46h1A2.87,2.87,0,0,1,9.12,4.33v1"/><line class="cls-1" x1="11.04" y1="5.29" x2="7.21" y2="5.29"/></svg>
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