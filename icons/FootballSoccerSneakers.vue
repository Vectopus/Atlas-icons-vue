
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.59,16.82H3.41A1.91,1.91,0,0,1,1.5,14.91V8.62A1.35,1.35,0,0,1,2.85,7.27h0a1.31,1.31,0,0,1,.95.4L4,7.83A4.57,4.57,0,0,0,7.23,9.18h0a4.6,4.6,0,0,0,3.26-1.35l.56-.56,8.81,3.67a4.31,4.31,0,0,1,2.64,4h0A1.91,1.91,0,0,1,20.59,16.82Z"/><line class="cls-1" x1="14.2" y1="8.59" x2="12.95" y2="11.09"/><line class="cls-1" x1="17.76" y1="10.07" x2="16.77" y2="12.05"/><line class="cls-1" x1="20.59" y1="18.73" x2="20.59" y2="16.82"/><line class="cls-1" x1="16.77" y1="18.73" x2="16.77" y2="16.82"/><line class="cls-1" x1="12.95" y1="18.73" x2="12.95" y2="16.82"/><line class="cls-1" x1="7.23" y1="18.73" x2="7.23" y2="16.82"/><line class="cls-1" x1="3.41" y1="18.73" x2="3.41" y2="16.82"/><path class="cls-1" d="M1.5,13H3.41a3.82,3.82,0,0,1,3.82,3.82h0"/></svg>
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