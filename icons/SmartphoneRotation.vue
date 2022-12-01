
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.16" y="1.25" width="13.68" height="21.5" rx="1.95"/><path class="cls-1" d="M14,2.23h-3.9a1,1,0,0,1-1-1h5.86A1,1,0,0,1,14,2.23Z"/><path class="cls-1" d="M18.84,8c2.38.73,3.91,1.81,3.91,3s-1.53,2.3-3.91,3a20.46,20.46,0,0,1-3.91.74"/><path class="cls-1" d="M12,14.93A24.37,24.37,0,0,1,5.16,14c-2.38-.72-3.91-1.81-3.91-3S2.78,8.73,5.16,8"/><polyline class="cls-1" points="9.07 12 12 14.93 9.07 17.86"/></svg>
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