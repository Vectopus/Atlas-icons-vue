
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.45" y="1.5" width="19.09" height="11.45"/><line class="cls-1" x1="0.55" y1="1.5" x2="23.45" y2="1.5"/><line class="cls-1" x1="0.55" y1="12.95" x2="23.45" y2="12.95"/><rect class="cls-1" x="10.09" y="12.95" width="3.82" height="9.55"/><line class="cls-1" x1="18.68" y1="22.5" x2="5.32" y2="22.5"/><circle class="cls-1" cx="8.18" cy="7.23" r="1.91"/><line class="cls-1" x1="12.95" y1="5.32" x2="18.68" y2="5.32"/><line class="cls-1" x1="12.95" y1="9.14" x2="18.68" y2="9.14"/></svg>
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