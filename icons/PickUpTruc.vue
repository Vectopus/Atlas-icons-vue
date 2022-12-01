
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="15.34" y1="16.77" x2="7.7" y2="16.77"/><path class="cls-1" d="M3.89,16.77H1.5V11.05h9.55V5.32h4.34a1.9,1.9,0,0,1,1.81,1.3l1.48,4.43,2.37.59a1.9,1.9,0,0,1,1.45,1.85v3.28H19.16"/><circle class="cls-1" cx="17.25" cy="16.77" r="1.91"/><circle class="cls-1" cx="5.8" cy="16.77" r="1.91"/><line class="cls-1" x1="13.91" y1="11.05" x2="18.68" y2="11.05"/></svg>
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