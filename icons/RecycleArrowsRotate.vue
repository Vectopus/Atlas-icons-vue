
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M3.71,15,2.12,17.83a1.21,1.21,0,0,0,1.06,1.8H14.42"/><path class="cls-1" d="M5.48,11.87v0L9.4,4.91l1.54-2.75a1.21,1.21,0,0,1,2.12,0L14.6,4.91"/><path class="cls-1" d="M16.28,7.89l4,7.11,1.59,2.83a1.21,1.21,0,0,1-1.06,1.8H17.69"/><polyline class="cls-1" points="11.76 16.73 14.66 19.63 11.76 22.54"/><polyline class="cls-1" points="14.99 11.49 16.05 7.53 20.02 8.59"/><polyline class="cls-1" points="9.22 11.16 5.25 12.22 4.19 8.26"/></svg>
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