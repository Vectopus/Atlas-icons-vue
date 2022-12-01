
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="15.82 2.85 8.18 1.94 1.5 2.85 1.5 20.2 8.18 19.29 15.82 20.2 22.5 19.29 22.5 1.94 15.82 2.85"/><line class="cls-1" x1="8.18" y1="1.52" x2="8.18" y2="19.66"/><line class="cls-1" x1="15.82" y1="2.48" x2="15.82" y2="20.61"/><line class="cls-1" x1="1.5" y1="23.48" x2="1.5" y2="20.61"/><line class="cls-1" x1="8.18" y1="22.52" x2="8.18" y2="19.66"/><line class="cls-1" x1="15.82" y1="23.48" x2="15.82" y2="20.61"/><line class="cls-1" x1="22.5" y1="22.52" x2="22.5" y2="19.66"/></svg>
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