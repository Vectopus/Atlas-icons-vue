
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="17.74 17.76 22.52 17.76 22.52 1.5 1.48 1.5 1.48 17.76 6.26 17.76"/><line class="cls-1" x1="5.3" y1="13.93" x2="18.7" y2="13.93"/><polyline class="cls-1" points="7.22 12.02 7.22 6.28 16.78 6.28 16.78 12.02"/><path class="cls-1" d="M7.22,13.93A29.75,29.75,0,0,1,9.13,23.5"/><path class="cls-1" d="M16.78,13.93a29.75,29.75,0,0,0-1.91,9.57"/><line class="cls-1" x1="12" y1="13.93" x2="12" y2="23.5"/><line class="cls-1" x1="8.17" y1="17.76" x2="15.83" y2="17.76"/><line class="cls-1" x1="8.17" y1="21.59" x2="15.83" y2="21.59"/></svg>
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