
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.09,17.73h6.68A5.73,5.73,0,0,0,22.5,12h0a5.73,5.73,0,0,0-5.73-5.73h0"/><polyline class="cls-1" points="14.86 12.96 10.09 17.73 14.86 22.5"/><path class="cls-1" d="M13.91,6.27H7.23A5.73,5.73,0,0,0,1.5,12h0a5.73,5.73,0,0,0,5.73,5.73h0"/><polyline class="cls-1" points="9.14 11.04 13.91 6.27 9.14 1.5"/></svg>
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