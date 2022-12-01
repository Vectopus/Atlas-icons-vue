
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="1.5" y1="0.52" x2="1.5" y2="23.48"/><line class="cls-1" x1="3.41" y1="15.83" x2="7.24" y2="15.83"/><line class="cls-1" x1="3.41" y1="19.65" x2="7.24" y2="19.65"/><line class="cls-1" x1="3.41" y1="2.43" x2="7.24" y2="2.43"/><line class="cls-1" x1="3.41" y1="6.26" x2="7.24" y2="6.26"/><line class="cls-1" x1="9.15" y1="15.83" x2="23.5" y2="15.83"/><line class="cls-1" x1="9.15" y1="19.65" x2="23.5" y2="19.65"/><line class="cls-1" x1="7.24" y1="23.48" x2="7.24" y2="0.52"/><path class="cls-1" d="M7.24.52C7.24,8.17,16.8,12,23.5,12"/><line class="cls-1" x1="11.07" y1="8.17" x2="11.07" y2="13.91"/><line class="cls-1" x1="15.85" y1="11.04" x2="15.85" y2="13.91"/><line class="cls-1" x1="19.67" y1="12" x2="19.67" y2="13.91"/></svg>
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