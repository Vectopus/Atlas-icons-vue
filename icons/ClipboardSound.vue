
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="10.09" x2="12" y2="17.73"/><line class="cls-1" x1="15.82" y1="12" x2="15.82" y2="15.82"/><line class="cls-1" x1="8.18" y1="12" x2="8.18" y2="15.82"/><polyline class="cls-1" points="15.82 2.46 15.82 2.46 20.59 2.46 20.59 22.5 3.41 22.5 3.41 2.46 8.18 2.46 8.18 2.46"/><path class="cls-1" d="M15.82,1.5V3.41a1.92,1.92,0,0,1-1.91,1.91H10.09A1.92,1.92,0,0,1,8.18,3.41V1.5Z"/></svg>
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