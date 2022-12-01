
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><circle class="cls-1" cx="7.7" cy="7.7" r="0.48"/><circle class="cls-1" cx="13.43" cy="18.2" r="0.48"/><circle class="cls-2" cx="17.73" cy="15.82" r="0.95"/><circle class="cls-2" cx="12.95" cy="5.32" r="0.95"/><circle class="cls-1" cx="7.23" cy="13.91" r="1.91"/><circle class="cls-1" cx="10.09" cy="13.91" r="0.95"/><circle class="cls-1" cx="17.25" cy="9.61" r="2.39"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>