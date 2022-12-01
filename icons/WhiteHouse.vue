
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19,11H5.05A7,7,0,0,1,19,11Z"/><path class="cls-1" d="M14.32,11H9.68c0-3.83,1-6.95,2.32-6.95S14.32,7.19,14.32,11Z"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="4.33"/><line class="cls-1" x1="22.52" y1="14.85" x2="1.48" y2="14.85"/><line class="cls-1" x1="23.48" y1="22.5" x2="0.52" y2="22.5"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="14.85"/><line class="cls-1" x1="15.83" y1="22.5" x2="15.83" y2="14.85"/><line class="cls-1" x1="19.65" y1="22.5" x2="19.65" y2="14.85"/><line class="cls-1" x1="4.35" y1="22.5" x2="4.35" y2="14.85"/><line class="cls-1" x1="8.17" y1="22.5" x2="8.17" y2="14.85"/><rect class="cls-1" x="3.39" y="11.02" width="17.22" height="3.83"/></svg>
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