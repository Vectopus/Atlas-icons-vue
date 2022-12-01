
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/><path class="cls-1" d="M16.77,4.36c0,1.06-2.13,1-4.77,1s-4.77.1-4.77-1S9.36,1.5,12,1.5,16.77,3.31,16.77,4.36Z"/><path class="cls-1" d="M10.09,5.32a39.08,39.08,0,0,1,1,8.59c0,2.86-1.91,8.59-3.82,8.59"/><path class="cls-1" d="M13.91,5.32a39.08,39.08,0,0,0-1,8.59c0,2.86,1.91,8.59,3.82,8.59"/><line class="cls-1" x1="8.18" y1="18.68" x2="15.82" y2="18.68"/></svg>
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