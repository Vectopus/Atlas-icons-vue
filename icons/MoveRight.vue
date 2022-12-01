
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M8,23,2.62,17.62a2.12,2.12,0,0,1,3-3L7,16V6.11A2.08,2.08,0,0,1,8.82,4,2,2,0,0,1,11,6v6l5.28.75a2,2,0,0,1,1.72,2h0a18,18,0,0,1-1.91,8.09L16,23"/><polyline class="cls-1" points="19 7 22 4 19 1"/><line class="cls-1" x1="14" y1="4" x2="22" y2="4"/></svg>
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