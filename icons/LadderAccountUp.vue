
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,23.45a4.78,4.78,0,0,1,4.77-4.77h0a4.78,4.78,0,0,1,4.78,4.77"/><circle class="cls-1" cx="6.27" cy="13.91" r="2.86"/><line class="cls-1" x1="22.5" y1="0.55" x2="22.5" y2="23.45"/><line class="cls-1" x1="14.86" y1="23.45" x2="14.86" y2="0.55"/><line class="cls-1" x1="22.5" y1="19.64" x2="14.86" y2="19.64"/><line class="cls-1" x1="14.86" y1="5.32" x2="22.5" y2="5.32"/><line class="cls-1" x1="14.86" y1="10.09" x2="22.5" y2="10.09"/><line class="cls-1" x1="22.5" y1="14.86" x2="14.86" y2="14.86"/><line class="cls-1" x1="6.27" y1="3.41" x2="6.27" y2="9.14"/><polyline class="cls-1" points="3.41 5.32 6.27 2.46 9.14 5.32"/></svg>
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