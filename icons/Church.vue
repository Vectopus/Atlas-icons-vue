
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="9.14 22.48 1.5 22.48 1.5 13.89 5.32 8.16 9.14 13.89 9.14 22.48"/><line class="cls-1" x1="5.32" y1="0.52" x2="5.32" y2="8.16"/><line class="cls-1" x1="2.45" y1="3.39" x2="8.18" y2="3.39"/><polyline class="cls-1" points="9.14 22.48 22.5 22.48 22.5 13.89 17.73 8.16 5.32 8.16"/><line class="cls-1" x1="22.5" y1="13.89" x2="9.14" y2="13.89"/><line class="cls-1" x1="5.32" y1="17.7" x2="5.32" y2="22.48"/><line class="cls-1" x1="5.32" y1="13.89" x2="5.32" y2="15.8"/><line class="cls-1" x1="12" y1="19.61" x2="12" y2="16.75"/><line class="cls-1" x1="15.82" y1="19.61" x2="15.82" y2="16.75"/><line class="cls-1" x1="19.64" y1="19.61" x2="19.64" y2="16.75"/></svg>
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