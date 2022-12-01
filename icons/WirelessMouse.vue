
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.09,8.18h3.82A3.82,3.82,0,0,1,16.73,12v4.77A5.73,5.73,0,0,1,11,22.5h0a5.73,5.73,0,0,1-5.73-5.73V12A3.82,3.82,0,0,1,9.09,8.18Z"/><line class="cls-1" x1="11" y1="11.05" x2="11" y2="13.91"/><path class="cls-1" d="M6.28,3.46a6.67,6.67,0,0,1,9.44,0"/><path class="cls-1" d="M8.3,5.48a3.82,3.82,0,0,1,5.4,0"/></svg>
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