
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="20.11" cy="3.89" r="2.39"/><line class="cls-1" x1="1.5" y1="22.5" x2="18.2" y2="5.8"/><line class="cls-1" x1="8.18" y1="19.64" x2="4.36" y2="15.82"/><line class="cls-1" x1="11.05" y1="16.77" x2="7.23" y2="12.95"/><line class="cls-1" x1="5.32" y1="22.5" x2="1.5" y2="18.68"/></svg>
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