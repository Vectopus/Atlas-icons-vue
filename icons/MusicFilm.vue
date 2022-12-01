
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="1.46" x2="23.5" y2="1.46"/><line class="cls-1" x1="0.5" y1="5.29" x2="2.42" y2="5.29"/><line class="cls-1" x1="4.33" y1="5.29" x2="6.25" y2="5.29"/><line class="cls-1" x1="8.17" y1="5.29" x2="10.08" y2="5.29"/><line class="cls-1" x1="12" y1="5.29" x2="13.92" y2="5.29"/><line class="cls-1" x1="15.83" y1="5.29" x2="17.75" y2="5.29"/><line class="cls-1" x1="19.67" y1="5.29" x2="21.58" y2="5.29"/><line class="cls-1" x1="0.5" y1="19.67" x2="13.92" y2="19.67"/><line class="cls-1" x1="0.5" y1="15.83" x2="2.42" y2="15.83"/><line class="cls-1" x1="4.33" y1="15.83" x2="6.25" y2="15.83"/><line class="cls-1" x1="8.17" y1="15.83" x2="10.08" y2="15.83"/><circle class="cls-1" cx="18.71" cy="20.63" r="1.92"/><polyline class="cls-1" points="23.5 13.92 20.63 13.92 20.63 20.63"/><line class="cls-1" x1="12" y1="15.83" x2="13.92" y2="15.83"/><line class="cls-1" x1="15.83" y1="15.83" x2="17.75" y2="15.83"/></svg>
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