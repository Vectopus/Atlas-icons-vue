
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.34,8.66V20.11A2.39,2.39,0,0,0,7.73,22.5h0a2.38,2.38,0,0,0,2.38-2.39V8.66A2.39,2.39,0,0,1,12.5,6.27h0a2.39,2.39,0,0,1,2.39,2.39h0a2.38,2.38,0,0,0,2.38,2.39h0a2.39,2.39,0,0,0,2.39-2.39h0A7.17,7.17,0,0,0,12.5,1.5h0A7.17,7.17,0,0,0,5.34,8.66Z"/><line class="cls-1" x1="5.34" y1="14.86" x2="10.11" y2="19.64"/><line class="cls-1" x1="5.34" y1="7.23" x2="10.11" y2="12"/><line class="cls-1" x1="12.02" y1="1.5" x2="12.02" y2="6.27"/><line class="cls-1" x1="14.89" y1="7.23" x2="19.66" y2="7.23"/></svg>
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