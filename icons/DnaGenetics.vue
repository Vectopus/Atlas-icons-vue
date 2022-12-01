
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="DNA"><line class="cls-1" x1="12" y1="2" x2="5.14" y2="2"/><line class="cls-1" x1="13" y1="2" x2="15" y2="2"/><line class="cls-1" x1="18.86" y1="2" x2="16" y2="2"/><path class="cls-2" d="M18.71.5C18.71,12,5.29,12,5.29,23.5"/><path class="cls-2" d="M5.29.5c0,11.5,13.42,11.5,13.42,23"/><line class="cls-2" x1="10.08" y1="6.25" x2="6.71" y2="6.25"/><line class="cls-2" x1="11.04" y1="6.25" x2="12.96" y2="6.25"/><line class="cls-2" x1="17.29" y1="6.25" x2="13.92" y2="6.25"/><line class="cls-2" x1="10.08" y1="17.75" x2="6.71" y2="17.75"/><line class="cls-2" x1="11.04" y1="17.75" x2="12.96" y2="17.75"/><line class="cls-2" x1="17.29" y1="17.75" x2="13.92" y2="17.75"/><line class="cls-2" x1="9.13" y1="21.58" x2="5.43" y2="21.58"/><line class="cls-2" x1="10.08" y1="21.58" x2="12" y2="21.58"/><line class="cls-2" x1="18.57" y1="21.58" x2="12.96" y2="21.58"/></g></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-1{}
</style>