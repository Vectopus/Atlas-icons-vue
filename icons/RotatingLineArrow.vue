
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="0.5" x2="12" y2="13.92"/><path class="cls-1" d="M14.88,8.31c4.42.45,7.66,1.94,7.66,3.69,0,2.12-4.71,3.83-10.54,3.83S1.46,14.12,1.46,12c0-1.75,3.24-3.24,7.66-3.69"/><line class="cls-1" x1="12" y1="17.75" x2="12" y2="23.5"/><polyline class="cls-1" points="5.72 6.08 9.12 8.32 6.89 11.71"/></svg>
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