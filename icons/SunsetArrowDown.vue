
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="0.46" x2="12" y2="2.38"/><line class="cls-1" x1="23.5" y1="11.96" x2="21.58" y2="11.96"/><line class="cls-1" x1="2.42" y1="11.96" x2="0.5" y2="11.96"/><line class="cls-1" x1="12" y1="0.46" x2="12" y2="2.38"/><line class="cls-1" x1="23.5" y1="11.96" x2="21.58" y2="11.96"/><line class="cls-1" x1="2.42" y1="11.96" x2="0.5" y2="11.96"/><line class="cls-1" x1="20.13" y1="3.83" x2="18.78" y2="5.18"/><line class="cls-1" x1="5.22" y1="5.18" x2="3.87" y2="3.83"/><line class="cls-1" x1="20.13" y1="3.83" x2="18.78" y2="5.18"/><line class="cls-1" x1="5.22" y1="5.18" x2="3.87" y2="3.83"/><path class="cls-1" d="M23.5,15.79h-6A6.56,6.56,0,0,0,18.71,12,6.71,6.71,0,0,0,5.29,12,6.56,6.56,0,0,0,6.5,15.79H.5"/><polyline class="cls-1" points="14.88 18.67 12 21.54 9.13 18.67"/><line class="cls-1" x1="12" y1="14.83" x2="12" y2="20.58"/></svg>
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