
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="17.73 11.04 6.27 11.04 8.18 1.5 15.82 1.5 17.73 11.04"/><line class="cls-1" x1="6.27" y1="22.5" x2="17.73" y2="22.5"/><line class="cls-1" x1="12" y1="11.05" x2="12" y2="22.5"/><line class="cls-1" x1="15.82" y1="11.05" x2="15.82" y2="14.86"/></svg>
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