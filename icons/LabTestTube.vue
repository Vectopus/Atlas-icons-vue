
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M21.07,6.75,17.25,2.93,10.59,9.59a6.68,6.68,0,1,0,3.82,3.82Z"/><line class="cls-1" x1="15.82" y1="1.5" x2="22.5" y2="8.18"/><line class="cls-1" x1="1.5" y1="14.86" x2="14.86" y2="14.86"/><line class="cls-1" x1="5.32" y1="18.68" x2="7.23" y2="18.68"/><line class="cls-1" x1="10.09" y1="17.73" x2="12" y2="17.73"/></svg>
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