
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="19.09" height="5.73"/><polyline class="cls-1" points="11.04 12.96 1.5 12.96 1.5 7.23 20.59 7.23 20.59 9.14"/><line class="cls-1" x1="4.36" y1="4.36" x2="6.27" y2="4.36"/><line class="cls-1" x1="4.36" y1="10.09" x2="6.27" y2="10.09"/><line class="cls-1" x1="8.18" y1="4.36" x2="17.73" y2="4.36"/><line class="cls-1" x1="8.18" y1="10.09" x2="11.05" y2="10.09"/><polyline class="cls-1" points="11.04 18.68 1.5 18.68 1.5 12.96 11.04 12.96"/><line class="cls-1" x1="4.36" y1="15.82" x2="6.27" y2="15.82"/><line class="cls-1" x1="11.05" y1="15.82" x2="8.18" y2="15.82"/><path class="cls-1" d="M17.74,22.48l-.06,0h0A6.58,6.58,0,0,1,13,16.2V12.42l4.73-1.37,4.82,1.37v3.75A6.56,6.56,0,0,1,17.74,22.48Z"/></svg>
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