
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="19.64 22.5 4.36 22.5 10.09 1.5 13.91 1.5 19.64 22.5"/><line class="cls-1" x1="1.5" y1="22.5" x2="22.5" y2="22.5"/><line class="cls-1" x1="8.18" y1="9.14" x2="15.82" y2="9.14"/><line class="cls-1" x1="6.27" y1="15.82" x2="17.73" y2="15.82"/></svg>
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