
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="0.5" x2="2.42" y2="23.5"/><line class="cls-1" x1="21.58" y1="0.5" x2="12" y2="23.5"/><line class="cls-1" x1="10.08" y1="4.33" x2="19.67" y2="4.33"/><line class="cls-1" x1="8.17" y1="9.13" x2="17.75" y2="9.13"/><line class="cls-1" x1="6.25" y1="13.92" x2="15.83" y2="13.92"/><line class="cls-1" x1="4.33" y1="18.71" x2="13.92" y2="18.71"/></svg>
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