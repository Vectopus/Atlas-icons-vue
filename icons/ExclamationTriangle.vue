
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,3.41h0a1.71,1.71,0,0,0-1.46.81L1.73,18.32a1.48,1.48,0,0,0-.23.79h0A1.48,1.48,0,0,0,3,20.59H21a1.48,1.48,0,0,0,1.48-1.48h0a1.48,1.48,0,0,0-.23-.79L13.46,4.22A1.71,1.71,0,0,0,12,3.41Z"/><line class="cls-1" x1="12" y1="8.18" x2="12" y2="14.86"/><line class="cls-1" x1="12" y1="15.82" x2="12" y2="17.73"/></svg>
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