
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.33" y="15.94" width="7.42" height="4.05" transform="translate(-10.93 9.54) rotate(-45)"/><polygon class="cls-1" points="22.51 3.41 20.6 1.5 7.24 13.91 10.1 16.77 22.51 3.41"/><circle class="cls-1" cx="18.69" cy="16.77" r="1.91"/><circle class="cls-1" cx="16.78" cy="20.59" r="1.91"/><circle class="cls-1" cx="20.6" cy="20.59" r="1.91"/></svg>
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