
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><polyline class="cls-1" points="12.96 4.36 15.82 7.23 12.96 10.09"/><polyline class="cls-1" points="12.96 4.36 15.82 7.23 12.96 10.09"/><polyline class="cls-1" points="11.04 13.91 8.18 16.77 11.04 19.64"/><path class="cls-1" d="M17.73,11.05h0A5.73,5.73,0,0,1,12,16.77H8.18"/><path class="cls-1" d="M17.73,11.05h0A5.73,5.73,0,0,1,12,16.77H8.18"/><path class="cls-1" d="M6.27,13h0A5.73,5.73,0,0,1,12,7.23h3.82"/></svg>
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