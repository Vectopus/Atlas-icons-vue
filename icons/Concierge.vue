
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M8.17,1.5h7.65a0,0,0,0,1,0,0V8.2A3.83,3.83,0,0,1,12,12h0A3.83,3.83,0,0,1,8.17,8.2V1.5a0,0,0,0,1,0,0Z"/><line class="cls-1" x1="8.17" y1="5.33" x2="18.7" y2="5.33"/><path class="cls-1" d="M4.35,23.5V19.67A7.65,7.65,0,0,1,12,12h0a7.65,7.65,0,0,1,7.65,7.65V23.5"/><line class="cls-1" x1="9.13" y1="17.76" x2="11.04" y2="17.76"/><line class="cls-1" x1="9.13" y1="21.59" x2="11.04" y2="21.59"/><polyline class="cls-1" points="8.93 12.66 12.96 15.85 12.96 23.5"/></svg>
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