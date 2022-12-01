
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.41" y="1.5" width="17.18" height="3.82"/><path class="cls-1" d="M14.86,5.32H3.41L1.5,22.5h8.59l.85-7.64A1.07,1.07,0,0,1,12,13.91h0a1.07,1.07,0,0,1,1.06.95l.85,7.64H22.5L20.59,5.32Z"/></svg>
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