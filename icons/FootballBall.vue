
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M17.66,17.66A17.25,17.25,0,0,1,3.77,22.43a2.49,2.49,0,0,1-2.2-2.2A17.26,17.26,0,0,1,6.34,6.34,17.26,17.26,0,0,1,20.23,1.57a2.37,2.37,0,0,1,1.48.72,2.39,2.39,0,0,1,.72,1.48A17.25,17.25,0,0,1,17.66,17.66Z"/><line class="cls-1" x1="15.82" y1="8.18" x2="8.18" y2="15.82"/><line class="cls-1" x1="10.09" y1="10.09" x2="13.91" y2="13.91"/><line class="cls-1" x1="12.48" y1="7.7" x2="16.3" y2="11.52"/><line class="cls-1" x1="7.7" y1="12.48" x2="11.52" y2="16.3"/><path class="cls-1" d="M1.69,15.83a6.65,6.65,0,0,1,6.48,6.48"/><path class="cls-1" d="M15.83,1.69a6.65,6.65,0,0,0,6.48,6.48"/></svg>
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