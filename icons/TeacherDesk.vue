
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.41" y="8.18" width="17.18" height="11.45"/><rect class="cls-1" x="7.23" y="12" width="9.55" height="3.82"/><line class="cls-1" x1="0.55" y1="8.18" x2="23.45" y2="8.18"/><line class="cls-1" x1="3.41" y1="22.5" x2="3.41" y2="19.64"/><line class="cls-1" x1="20.59" y1="22.5" x2="20.59" y2="19.64"/><line class="cls-1" x1="5.32" y1="1.5" x2="5.32" y2="8.18"/><line class="cls-1" x1="8.18" y1="4.36" x2="8.18" y2="8.18"/><line class="cls-1" x1="2.45" y1="2.45" x2="2.45" y2="8.18"/></svg>
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