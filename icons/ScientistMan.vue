
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,23.48h0A10.5,10.5,0,0,1,12,13h0a10.5,10.5,0,0,1,10.5,10.5h0"/><polyline class="cls-1" points="8.17 13.7 5.32 15.84 7.23 17.75 7.23 20.61 12 22.52 16.77 20.61 16.77 17.75 18.68 15.84 15.83 13.7 15.82 13.69"/><line class="cls-1" x1="12" y1="22.52" x2="9.25" y2="13.35"/><line class="cls-1" x1="14.75" y1="13.35" x2="12" y2="22.52"/><rect class="cls-1" x="7.23" y="1.52" width="9.55" height="11.45" rx="4.77"/><path class="cls-1" d="M10.09,4.39h0A3.46,3.46,0,0,0,13.18,6.3h3.59"/></svg>
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