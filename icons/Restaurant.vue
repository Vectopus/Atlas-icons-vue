
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M11,.5V6.76a3.81,3.81,0,0,1-2.12,3.42h0a3.83,3.83,0,0,1-3.43,0h0A3.83,3.83,0,0,1,3.37,6.76V.5"/><line class="cls-1" x1="7.21" y1="0.5" x2="7.21" y2="23.5"/><path class="cls-1" d="M14.87,23.5v-22h0a5.74,5.74,0,0,1,5.74,5.75V13l-5.75,2.87"/></svg>
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