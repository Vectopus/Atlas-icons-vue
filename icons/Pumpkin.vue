
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.44,6.27h.5A2.06,2.06,0,0,1,12,8.33v12.1A2.06,2.06,0,0,1,9.94,22.5h-.5a4.12,4.12,0,0,1-4.12-4.12v-8A4.12,4.12,0,0,1,9.44,6.27Z"/><path class="cls-1" d="M6.8,21.55H6.27A4.78,4.78,0,0,1,1.5,16.77V12A4.78,4.78,0,0,1,6.27,7.23H6.8"/><path class="cls-1" d="M16.12,6.27h.5a2.06,2.06,0,0,1,2.06,2.06v12.1a2.06,2.06,0,0,1-2.06,2.06h-.5A4.12,4.12,0,0,1,12,18.38v-8a4.12,4.12,0,0,1,4.12-4.12Z" transform="translate(30.68 28.77) rotate(-180)"/><path class="cls-1" d="M17.2,7.23h.53A4.78,4.78,0,0,1,22.5,12v4.77a4.78,4.78,0,0,1-4.77,4.78H17.2"/><path class="cls-1" d="M8.18,1.5h0A3.82,3.82,0,0,1,12,5.32V7.23"/></svg>
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