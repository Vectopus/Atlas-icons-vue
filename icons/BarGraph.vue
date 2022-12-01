
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.45" y="14.86" width="3.82" height="7.64"/><rect class="cls-1" x="17.73" y="1.5" width="3.82" height="21"/><rect class="cls-1" x="10.09" y="9.14" width="3.82" height="13.36"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/></svg>
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