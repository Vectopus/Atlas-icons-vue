
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.86,9.14V1.5H9.14V9.14L1.91,19.07a2.14,2.14,0,0,0-.41,1.27h0A2.16,2.16,0,0,0,3.66,22.5H20.34a2.16,2.16,0,0,0,2.16-2.16h0a2.14,2.14,0,0,0-.41-1.27Z"/><line class="cls-1" x1="7.23" y1="1.5" x2="16.77" y2="1.5"/><path class="cls-1" d="M10.09,13H12a3.29,3.29,0,0,1,3.29,3.29v1.91a0,0,0,0,1,0,0H13.38a3.29,3.29,0,0,1-3.29-3.29V13A0,0,0,0,1,10.09,13Z"/><line class="cls-1" x1="16.77" y1="19.64" x2="14.86" y2="17.73"/></svg>
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