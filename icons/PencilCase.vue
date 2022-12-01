
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.32,11H18.68a0,0,0,0,1,0,0v8.59a2.86,2.86,0,0,1-2.86,2.86H8.18a2.86,2.86,0,0,1-2.86-2.86V11A0,0,0,0,1,5.32,11Z"/><rect class="cls-1" x="7.23" y="1.5" width="3.82" height="9.55"/><line class="cls-1" x1="13.91" y1="3.41" x2="13.91" y2="11.05"/><line class="cls-1" x1="16.77" y1="1.5" x2="16.77" y2="11.05"/><rect class="cls-1" x="11.05" y="14.86" width="7.64" height="3.82"/></svg>
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