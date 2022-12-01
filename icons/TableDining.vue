
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.38" y="4.35" width="17.25" height="3.83"/><line class="cls-1" x1="23.5" y1="4.35" x2="0.5" y2="4.35"/><line class="cls-1" x1="3.38" y1="20.65" x2="3.38" y2="8.19"/><line class="cls-1" x1="20.63" y1="20.65" x2="20.63" y2="8.19"/></svg>
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