
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="9.14" y1="20.59" x2="9.14" y2="3.41"/><line class="cls-1" x1="11.05" y1="20.59" x2="7.23" y2="20.59"/><polyline class="cls-1" points="1.5 5.32 1.5 3.41 16.77 3.41 16.77 5.32"/><line class="cls-1" x1="17.73" y1="20.59" x2="17.73" y2="9.14"/><line class="cls-1" x1="19.64" y1="20.59" x2="15.82" y2="20.59"/><polyline class="cls-1" points="12.96 11.04 12.96 9.14 22.5 9.14 22.5 11.04"/></svg>
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