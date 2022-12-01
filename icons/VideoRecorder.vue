
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="9.14" width="15.27" height="11.45"/><polygon class="cls-1" points="16.77 16.77 21.55 20.59 22.5 20.59 22.5 9.14 21.55 9.14 16.77 12.96 16.77 16.77"/><circle class="cls-1" cx="4.36" cy="6.27" r="2.86"/><circle class="cls-1" cx="13.91" cy="6.27" r="2.86"/></svg>
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