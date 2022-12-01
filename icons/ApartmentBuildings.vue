
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12.96 22.5 1.5 22.5 1.5 5.32 7.23 1.5 12.96 5.32 12.96 22.5"/><path class="cls-1" d="M6.27,8.18h0Z"/><path class="cls-1" d="M10.09,8.18h0Z"/><path class="cls-1" d="M6.27,12h0Z"/><path class="cls-1" d="M10.09,12h0Z"/><path class="cls-1" d="M6.27,15.82h0Z"/><path class="cls-1" d="M10.09,15.82h0Z"/><rect class="cls-1" x="6.27" y="19.64" width="1.91" height="2.86"/><polygon class="cls-1" points="22.5 22.5 12.96 22.5 12.96 9.14 17.73 6.27 22.5 9.14 22.5 22.5"/><path class="cls-1" d="M19.64,11.05h0Z"/><path class="cls-1" d="M19.64,14.86h0Z"/><path class="cls-1" d="M19.64,18.68h0Z"/></svg>
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