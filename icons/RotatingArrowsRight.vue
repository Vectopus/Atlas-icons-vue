
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="20.63 0.5 20.63 6.25 14.88 6.25"/><polyline class="cls-1" points="3.38 23.5 3.38 17.75 9.13 17.75"/><path class="cls-1" d="M1.83,14.77A10.12,10.12,0,0,1,1.46,12,10.54,10.54,0,0,1,20.62,5.94"/><path class="cls-1" d="M22.17,9.23A10.12,10.12,0,0,1,22.54,12,10.54,10.54,0,0,1,3.38,18.06"/></svg>
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