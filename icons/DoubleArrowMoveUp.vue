
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.77,2.5V8.8A5.71,5.71,0,0,1,14,13.71L10,16.1A5.73,5.73,0,0,0,7.23,21V23.5"/><polyline class="cls-1" points="20.59 6.32 16.77 2.5 12.96 6.32"/><line class="cls-1" x1="7.23" y1="23.5" x2="7.23" y2="2.5"/><polyline class="cls-1" points="11.04 6.32 7.23 2.5 3.41 6.32"/><line class="cls-1" x1="7.23" y1="13.95" x2="7.23" y2="21.59"/></svg>
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