
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="17.73" y1="3.41" x2="17.73" y2="14.86"/><line class="cls-1" x1="6.28" y1="9.14" x2="6.28" y2="22.5"/><polyline class="cls-1" points="12.84 7.11 17.73 2.22 22.62 7.11"/><line class="cls-1" x1="1.5" y1="17.73" x2="11.05" y2="17.73"/><path class="cls-1" d="M8.4,1.5A2.52,2.52,0,0,0,6.28,2.64,2.55,2.55,0,0,0,1.61,4.05c0,3.81,4.67,5.09,4.67,5.09s4.66-1.28,4.66-5.09A2.55,2.55,0,0,0,8.4,1.5Z"/><path class="cls-1" d="M15.61,22.5a2.55,2.55,0,0,0,2.12-1.14A2.55,2.55,0,0,0,22.4,20c0-3.81-4.67-5.09-4.67-5.09S13.06,16.14,13.06,20A2.55,2.55,0,0,0,15.61,22.5Z"/></svg>
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