
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,2.45V17.73a58.35,58.35,0,0,0-21,0V2.45A58.35,58.35,0,0,0,22.5,2.45Z"/><line class="cls-1" x1="12" y1="21.55" x2="12" y2="16.77"/><line class="cls-1" x1="7.23" y1="21.55" x2="16.77" y2="21.55"/></svg>
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