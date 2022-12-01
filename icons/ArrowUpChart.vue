
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="23.5 22.5 1.5 22.5 1.5 0.5"/><polyline class="cls-1" points="1.5 16.76 8.2 10.06 11.06 12.94 22.54 1.46"/><polyline class="cls-1" points="17.76 1.46 22.54 1.46 22.54 6.24"/><line class="cls-1" x1="7.24" y1="14.85" x2="7.24" y2="22.5"/><line class="cls-1" x1="12.98" y1="16.76" x2="12.98" y2="22.5"/><line class="cls-1" x1="18.72" y1="9.11" x2="18.72" y2="22.5"/></svg>
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