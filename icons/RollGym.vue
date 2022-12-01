
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="9.13" y="3.38" width="5.75" height="17.25" rx="2.87"/><polyline class="cls-1" points="14.88 9.13 18.71 11.04 18.71 12.96 14.88 14.88"/><polyline class="cls-1" points="9.13 14.88 5.29 12.96 5.29 11.04 9.13 9.13"/><line class="cls-1" x1="18.71" y1="12" x2="23.5" y2="12"/><line class="cls-1" x1="5.29" y1="12" x2="0.5" y2="12"/></svg>
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