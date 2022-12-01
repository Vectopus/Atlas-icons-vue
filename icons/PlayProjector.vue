
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="9.14" width="15.27" height="12.41"/><polygon class="cls-1" points="16.77 17.73 21.55 21.55 22.5 21.55 22.5 9.14 21.55 9.14 16.77 12.96 16.77 17.73"/><circle class="cls-1" cx="4.84" cy="5.8" r="3.34"/><circle class="cls-1" cx="13.43" cy="5.8" r="3.34"/><polygon class="cls-1" points="7.23 16.77 7.23 13.91 10.09 15.34 7.23 16.77"/></svg>
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