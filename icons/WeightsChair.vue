
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M8.17,15.83h7.67a1.92,1.92,0,0,1,1.92,1.92v1.92a0,0,0,0,1,0,0H6.25a0,0,0,0,1,0,0V17.75A1.92,1.92,0,0,1,8.17,15.83Z"/><line class="cls-1" x1="8.17" y1="23.5" x2="8.17" y2="19.67"/><line class="cls-1" x1="15.83" y1="23.5" x2="15.83" y2="19.67"/><rect class="cls-1" x="8.17" y="3.38" width="7.67" height="12.46"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="7.21"/><polyline class="cls-1" points="2.42 9.13 4.33 7.21 19.67 7.21 21.58 9.13"/></svg>
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