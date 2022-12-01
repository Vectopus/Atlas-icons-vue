
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="10.08 23.5 10.08 17.75 13.92 17.75 13.92 23.5"/><line class="cls-1" x1="5.29" y1="22.54" x2="5.29" y2="10.08"/><line class="cls-1" x1="18.71" y1="10.08" x2="18.71" y2="22.54"/><line class="cls-1" x1="5.29" y1="8.17" x2="5.29" y2="0.5"/><line class="cls-1" x1="18.71" y1="0.5" x2="18.71" y2="8.17"/><line class="cls-1" x1="21.58" y1="5.29" x2="21.58" y2="14.87"/><line class="cls-1" x1="2.42" y1="5.29" x2="2.42" y2="14.87"/><line class="cls-1" x1="0.5" y1="10.08" x2="23.5" y2="10.08"/><line class="cls-1" x1="8.17" y1="17.75" x2="15.83" y2="17.75"/><line class="cls-1" x1="2.42" y1="22.54" x2="8.17" y2="22.54"/><line class="cls-1" x1="15.83" y1="22.54" x2="21.58" y2="22.54"/></svg>
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