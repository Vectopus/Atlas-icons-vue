
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="4.37" r="2.87"/><path class="cls-1" d="M12,7.24h0A4.78,4.78,0,0,1,16.78,12v1a0,0,0,0,1,0,0H7.22a0,0,0,0,1,0,0V12A4.78,4.78,0,0,1,12,7.24Z"/><line class="cls-1" x1="23.48" y1="12.98" x2="0.52" y2="12.98"/><polyline class="cls-1" points="3.39 23.5 3.39 12.98 20.61 12.98 20.61 23.5"/><rect class="cls-1" x="7.22" y="16.8" width="9.57" height="3.83"/></svg>
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