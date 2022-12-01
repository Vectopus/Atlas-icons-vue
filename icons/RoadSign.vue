
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="5.32" width="21" height="4.77"/><line class="cls-1" x1="3.41" y1="5.32" x2="9.14" y2="10.09"/><line class="cls-1" x1="9.14" y1="5.32" x2="14.86" y2="10.09"/><line class="cls-1" x1="14.86" y1="5.32" x2="20.59" y2="10.09"/><path class="cls-1" d="M4.36,1.5h0A1.91,1.91,0,0,1,6.27,3.41V5.32a0,0,0,0,1,0,0H2.45a0,0,0,0,1,0,0V3.41A1.91,1.91,0,0,1,4.36,1.5Z"/><rect class="cls-1" x="2.45" y="10.09" width="3.82" height="12.41"/><path class="cls-1" d="M19.64,1.5h0a1.91,1.91,0,0,1,1.91,1.91V5.32a0,0,0,0,1,0,0H17.73a0,0,0,0,1,0,0V3.41A1.91,1.91,0,0,1,19.64,1.5Z"/><rect class="cls-1" x="17.73" y="10.09" width="3.82" height="12.41"/><line class="cls-1" x1="6.27" y1="16.77" x2="17.73" y2="16.77"/></svg>
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