
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="11.5 22.5 1.5 22.5 1.5 3.5 11.5 1.5 11.5 22.5"/><rect class="cls-1" x="11.5" y="3.5" width="4" height="19"/><path class="cls-1" d="M9.5,11.5h0Z"/><polyline class="cls-1" points="19.5 9.5 22.48 12.47 19.5 15.45"/><line class="cls-1" x1="15.5" y1="12.5" x2="22.5" y2="12.5"/></svg>
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