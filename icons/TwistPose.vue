
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="14.36" cy="3.89" r="2.39"/><path class="cls-1" d="M11,22.5h9.55v-.95l-6.68-2.87h0a18.16,18.16,0,0,0,1.91-8.09V8.18H12v1.91a14.31,14.31,0,0,1-2.87,8.59h0L4.34,22.5H3.39V14.86L1.48,13"/><polyline class="cls-1" points="15.79 8.18 16.75 8.18 21.52 19.64"/><polyline class="cls-1" points="11.98 8.18 11.02 8.18 8.64 12.48 3.39 12.48"/></svg>
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