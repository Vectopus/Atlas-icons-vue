
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="7.23 10.14 1.5 10.14 1.5 15.86"/><polyline class="cls-1" points="15.82 6.32 12 2.5 8.18 6.32"/><line class="cls-1" x1="12" y1="2.5" x2="12" y2="23.5"/><path class="cls-1" d="M1.5,10.14,7.06,15.7a3.82,3.82,0,0,1,1.12,2.7v5.1"/><polyline class="cls-1" points="16.77 10.14 22.5 10.14 22.5 15.86"/><path class="cls-1" d="M22.5,10.14,16.94,15.7a3.82,3.82,0,0,0-1.12,2.7v5.1"/></svg>
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