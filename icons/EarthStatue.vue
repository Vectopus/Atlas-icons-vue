
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="8.18" r="6.68"/><ellipse class="cls-1" cx="12" cy="8.18" rx="2.86" ry="6.68" transform="translate(-2.27 10.88) rotate(-45)"/><line class="cls-1" x1="7.28" y1="12.91" x2="16.72" y2="3.46"/><polygon class="cls-1" points="12 15.82 18.68 22.5 5.32 22.5 12 15.82"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="15.82"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/></svg>
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