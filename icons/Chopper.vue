
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,6.23h0a6.71,6.71,0,0,1,6.71,6.71v1.92a3.83,3.83,0,0,1-3.83,3.83H9.13a3.83,3.83,0,0,1-3.83-3.83V12.94A6.71,6.71,0,0,1,12,6.23Z"/><path class="cls-1" d="M12,6.23h0a6.71,6.71,0,0,1,6.71,6.71v1.92a3.83,3.83,0,0,1-3.83,3.83H9.13a3.83,3.83,0,0,1-3.83-3.83V12.94A6.71,6.71,0,0,1,12,6.23Z"/><path class="cls-1" d="M18.61,11.85a3.82,3.82,0,0,1-3.73,3H9.12a3.82,3.82,0,0,1-3.73-3"/><line class="cls-1" x1="12" y1="0.48" x2="12" y2="6.23"/><line class="cls-1" x1="0.5" y1="2.4" x2="23.5" y2="2.4"/><path class="cls-1" d="M17.81,17.33a3.81,3.81,0,0,1,1.86,3.27v1.92"/><path class="cls-1" d="M4.33,22.52V20.6a3.81,3.81,0,0,1,1.86-3.27"/><line class="cls-1" x1="2.42" y1="22.52" x2="6.25" y2="22.52"/><line class="cls-1" x1="17.75" y1="22.52" x2="21.58" y2="22.52"/><line class="cls-1" x1="11.04" y1="5.27" x2="12.96" y2="5.27"/></svg>
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