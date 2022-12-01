
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.59,19a4.29,4.29,0,0,0-2.39-7.86h-.56a6.12,6.12,0,0,0,.09-1,5.73,5.73,0,0,0-11.46,0,4.77,4.77,0,0,0-2.86,8.59"/><line class="cls-1" x1="6.27" y1="15.91" x2="6.27" y2="18.77"/><line class="cls-1" x1="6.27" y1="20.68" x2="6.27" y2="23.55"/><line class="cls-1" x1="10.09" y1="14" x2="10.09" y2="16.86"/><line class="cls-1" x1="10.09" y1="18.77" x2="10.09" y2="21.64"/><line class="cls-1" x1="13.91" y1="15.91" x2="13.91" y2="18.77"/><line class="cls-1" x1="13.91" y1="20.68" x2="13.91" y2="23.55"/><line class="cls-1" x1="17.73" y1="14" x2="17.73" y2="16.86"/><line class="cls-1" x1="17.73" y1="18.77" x2="17.73" y2="21.64"/></svg>
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