
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="1.5 16.53 1.5 4.13 7.23 4.13 9.14 1.26 14.86 1.26 16.77 4.13 22.5 4.13 22.5 16.53"/><circle class="cls-1" cx="12" cy="11.76" r="3.82"/><line class="cls-1" x1="17.73" y1="7.94" x2="19.64" y2="7.94"/><path class="cls-1" d="M1.5,16.53c0,1.88,3.82,3.82,8.65,3.77"/><path class="cls-1" d="M13.91,20.29c4.77.06,8.59-1.88,8.59-3.76"/><polyline class="cls-1" points="7.71 17.85 10.15 20.29 7.71 22.74"/></svg>
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