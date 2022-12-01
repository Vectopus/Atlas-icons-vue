
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="1.5" y1="22.5" x2="17.76" y2="6.24"/><line class="cls-1" x1="16.8" y1="0.5" x2="16.8" y2="4.33"/><line class="cls-1" x1="16.8" y1="10.07" x2="16.8" y2="13.89"/><line class="cls-1" x1="10.11" y1="7.2" x2="13.93" y2="7.2"/><line class="cls-1" x1="19.67" y1="7.2" x2="23.5" y2="7.2"/><line class="cls-1" x1="12.07" y1="2.46" x2="14.78" y2="5.17"/><line class="cls-1" x1="18.83" y1="9.22" x2="21.54" y2="11.93"/><line class="cls-1" x1="18.83" y1="5.17" x2="21.54" y2="2.46"/></svg>
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