
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.42" y="14.9" width="19.17" height="6.71"/><line class="cls-1" x1="4.33" y1="23.52" x2="4.33" y2="21.6"/><line class="cls-1" x1="19.67" y1="23.52" x2="19.67" y2="21.6"/><line class="cls-1" x1="10.08" y1="17.77" x2="13.92" y2="17.77"/><rect class="cls-1" x="2.42" y="8.19" width="19.17" height="6.71"/><line class="cls-1" x1="10.08" y1="11.06" x2="13.92" y2="11.06"/><rect class="cls-1" x="2.42" y="1.48" width="19.17" height="6.71"/><line class="cls-1" x1="10.08" y1="4.35" x2="13.92" y2="4.35"/><line class="cls-1" x1="0.5" y1="1.48" x2="23.5" y2="1.48"/></svg>
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