
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12.13,3.41h-.26a1.48,1.48,0,0,0-1.26.7L1.73,18.32a1.48,1.48,0,0,0-.23.79h0A1.48,1.48,0,0,0,3,20.59H21a1.48,1.48,0,0,0,1.48-1.48h0a1.48,1.48,0,0,0-.23-.79L13.39,4.11A1.48,1.48,0,0,0,12.13,3.41Z"/><path class="cls-1" d="M14.86,14.86a2.86,2.86,0,1,1-5.72,0C9.14,13,12,10.09,12,10.09S14.86,13,14.86,14.86Z"/><path class="cls-2" d="M13,16.14a.95.95,0,0,1-1.9,0c0-.64.95-1.59.95-1.59S13,15.5,13,16.14Z"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>