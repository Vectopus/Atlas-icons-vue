
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="8.18" y="13" width="7.64" height="9.55"/><rect class="cls-1" x="15.82" y="16.82" width="6.68" height="5.73"/><rect class="cls-1" x="1.5" y="18.73" width="6.68" height="3.82"/><polygon class="cls-1" points="12 3.46 12.93 5.34 15.01 5.64 13.51 7.11 13.86 9.18 12 8.2 10.14 9.18 10.49 7.11 8.99 5.64 11.07 5.34 12 3.46"/></svg>
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