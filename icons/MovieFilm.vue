
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12.02" cy="12" r="10.52"/><circle class="cls-1" cx="12.02" cy="6.26" r="1.91"/><circle class="cls-1" cx="12.02" cy="17.74" r="1.91"/><circle class="cls-1" cx="12.02" cy="17.74" r="1.91"/><circle class="cls-1" cx="6.28" cy="12" r="1.91"/><circle class="cls-1" cx="17.76" cy="12" r="1.91"/><circle class="cls-1" cx="17.76" cy="12" r="1.91"/><line class="cls-1" x1="23.5" y1="22.52" x2="12.02" y2="22.52"/><line class="cls-1" x1="11.07" y1="12" x2="12.98" y2="12"/></svg>
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