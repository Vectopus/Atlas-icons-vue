
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,22.5H1.5V1.5H16.77L22.5,7.23Z"/><rect class="cls-1" x="8.18" y="1.5" width="7.64" height="4.77"/><rect class="cls-1" x="6.27" y="17.73" width="11.45" height="4.77"/><circle class="cls-1" cx="12" cy="12" r="2.86"/></svg>
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