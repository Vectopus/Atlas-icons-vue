
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.07,13.84H5.16L1.25,18.73h0a3.91,3.91,0,0,0,3.91,3.91H18.84a3.91,3.91,0,0,0,3.91-3.91h0l-3.91-4.89H14.93"/><line class="cls-1" x1="1.25" y1="18.73" x2="22.75" y2="18.73"/><line class="cls-1" x1="12" y1="15.8" x2="12" y2="10.91"/><polygon class="cls-1" points="12 11.59 16.89 9.14 16.89 3.77 12 1.36 7.12 3.77 7.12 9.14 12 11.59"/><polyline class="cls-1" points="7.12 3.76 7.13 3.76 12 6.16 12 11.59"/><polyline class="cls-1" points="12 11.59 12 6.16 16.87 3.76 16.88 3.76"/><polyline class="cls-1" points="16.88 3.76 16.87 3.76 12 6.16 7.13 3.76 7.12 3.76"/></svg>
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