
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.09,8.18h3.82A3.82,3.82,0,0,1,17.73,12v4.77A5.73,5.73,0,0,1,12,22.5h0a5.73,5.73,0,0,1-5.73-5.73V12a3.82,3.82,0,0,1,3.82-3.82Z"/><line class="cls-1" x1="12" y1="11.05" x2="12" y2="13.91"/><polyline class="cls-1" points="9.14 4.36 12 1.5 14.86 4.36"/></svg>
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