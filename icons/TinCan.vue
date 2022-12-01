
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="4.36" y="1.5" width="15.27" height="21"/><ellipse class="cls-1" cx="12" cy="12" rx="3.82" ry="1.91"/><line class="cls-1" x1="2.45" y1="1.5" x2="21.55" y2="1.5"/><line class="cls-1" x1="2.45" y1="22.5" x2="21.55" y2="22.5"/><rect class="cls-1" x="4.36" y="6.27" width="15.27" height="11.45"/></svg>
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