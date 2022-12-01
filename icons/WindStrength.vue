
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="1.5" y1="0.55" x2="1.5" y2="23.45"/><polygon class="cls-1" points="22.5 12.96 8.18 14.86 7.23 14.86 7.23 3.41 8.18 3.41 22.5 5.32 22.5 12.96"/><line class="cls-1" x1="18.68" y1="5.32" x2="18.68" y2="12.95"/><line class="cls-1" x1="14.86" y1="4.36" x2="14.86" y2="13.91"/><line class="cls-1" x1="11.05" y1="4.36" x2="11.05" y2="13.91"/><polyline class="cls-1" points="7.23 3.41 2.46 9.14 7.23 14.86"/></svg>
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