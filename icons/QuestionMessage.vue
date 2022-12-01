
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,5.3v9.54a3.82,3.82,0,0,0,3.82,3.82H7.23v2.86L13,18.66h5.73a3.82,3.82,0,0,0,3.82-3.82V5.3a3.82,3.82,0,0,0-3.82-3.82H5.32A3.82,3.82,0,0,0,1.5,5.3Z"/><path class="cls-1" d="M12,12V10.86a1.9,1.9,0,0,1,.56-1.35l.79-.79a1.92,1.92,0,0,0,.56-1.35V7.2A1.91,1.91,0,0,0,12,5.3h0a1.91,1.91,0,0,0-1.91,1.9"/><line class="cls-1" x1="11.05" y1="13.89" x2="12.95" y2="13.89"/></svg>
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