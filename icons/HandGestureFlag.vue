
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M6.27,21.55H9.14l1.91.95h4.23a1.9,1.9,0,0,0,1.85-1.45l.55-2.17a1.84,1.84,0,0,0,.05-.41h0a1.7,1.7,0,0,0-1.7-1.7H14.86V13.91H12.67a2.19,2.19,0,0,0-1.22.37L9.14,15.82H6.27"/><line class="cls-1" x1="14.86" y1="16.77" x2="12" y2="16.77"/><polyline class="cls-1" points="14.86 16.77 14.86 1.5 6.27 1.5 8.18 4.36 6.27 7.23 14.86 7.23"/></svg>
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