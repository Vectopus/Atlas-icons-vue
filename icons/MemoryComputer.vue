
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="0.5 2.46 2.41 2.46 2.41 22.54"/><polygon class="cls-1" points="22.5 4.37 22.5 18.72 15.8 18.72 15.8 17.76 10.06 17.76 9.11 18.72 2.41 18.72 2.41 4.37 22.5 4.37"/><rect class="cls-1" x="2.41" y="8.2" width="4.78" height="6.7"/><circle class="cls-1" cx="15.33" cy="11.54" r="3.35"/></svg>
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