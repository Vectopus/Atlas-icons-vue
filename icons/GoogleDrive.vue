
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="8.18 2.46 15.82 2.46 22.5 15.82 19.64 21.55 4.36 21.55 1.5 15.82 8.18 2.46"/><line class="cls-1" x1="8.18" y1="2.45" x2="15.82" y2="15.82"/><line class="cls-1" x1="22.5" y1="15.82" x2="8.18" y2="15.82"/><line class="cls-1" x1="4.36" y1="21.55" x2="12" y2="9.14"/></svg>
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