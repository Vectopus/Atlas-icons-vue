
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.16" y="1.25" width="13.68" height="21.5" rx="1.95"/><path class="cls-1" d="M14,2.23h-3.9a1,1,0,0,1-1-1h5.86A1,1,0,0,1,14,2.23Z"/><path class="cls-1" d="M18.84,10c2.38.72,3.91,1.81,3.91,3s-1.53,2.29-3.91,3a21.26,21.26,0,0,1-3.91.74"/><path class="cls-1" d="M12,16.89A24.74,24.74,0,0,1,5.16,16c-2.38-.73-3.91-1.81-3.91-3s1.53-2.3,3.91-3"/><polyline class="cls-1" points="9.07 13.95 12 16.89 9.07 19.82"/><polygon class="cls-1" points="12.98 8.09 11.02 9.07 11.02 7.12 12.98 8.09 12.98 8.09"/></svg>
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