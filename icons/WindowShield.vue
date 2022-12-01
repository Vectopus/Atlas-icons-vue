
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="11.04 19.64 1.5 19.64 1.5 1.5 20.59 1.5 20.59 9.14"/><line class="cls-1" x1="1.5" y1="7.23" x2="20.59" y2="7.23"/><line class="cls-1" x1="4.36" y1="4.36" x2="6.27" y2="4.36"/><line class="cls-1" x1="8.18" y1="4.36" x2="10.09" y2="4.36"/><path class="cls-1" d="M17.74,22.48l-.06,0h0A6.58,6.58,0,0,1,13,16.2V12.42l4.73-1.37,4.82,1.37v3.75A6.56,6.56,0,0,1,17.74,22.48Z"/></svg>
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