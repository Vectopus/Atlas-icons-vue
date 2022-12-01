
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="1.44" x2="23.5" y2="1.44"/><line class="cls-1" x1="0.5" y1="5.27" x2="2.42" y2="5.27"/><line class="cls-1" x1="4.33" y1="5.27" x2="6.25" y2="5.27"/><line class="cls-1" x1="8.17" y1="5.27" x2="10.08" y2="5.27"/><line class="cls-1" x1="12" y1="5.27" x2="13.92" y2="5.27"/><line class="cls-1" x1="15.83" y1="5.27" x2="17.75" y2="5.27"/><line class="cls-1" x1="19.67" y1="5.27" x2="21.58" y2="5.27"/><line class="cls-1" x1="0.5" y1="19.65" x2="12" y2="19.65"/><line class="cls-1" x1="0.5" y1="15.81" x2="2.42" y2="15.81"/><line class="cls-1" x1="4.33" y1="15.81" x2="6.25" y2="15.81"/><line class="cls-1" x1="8.17" y1="15.81" x2="10.08" y2="15.81"/><polygon class="cls-1" points="14.88 21.56 14.88 15.81 20.63 18.69 14.88 21.56"/></svg>
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