
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="4.77"/><circle class="cls-1" cx="12" cy="2.45" r="0.95"/><circle class="cls-1" cx="12" cy="21.55" r="0.95"/><circle class="cls-1" cx="2.45" cy="12" r="0.95"/><circle class="cls-1" cx="21.55" cy="12" r="0.95"/><circle class="cls-1" cx="5.25" cy="5.25" r="0.95"/><circle class="cls-1" cx="18.75" cy="18.75" r="0.95"/><circle class="cls-1" cx="5.25" cy="18.75" r="0.95"/><circle class="cls-1" cx="18.75" cy="5.25" r="0.95"/><line class="cls-1" x1="12" y1="3.41" x2="12" y2="7.23"/><line class="cls-1" x1="12" y1="16.77" x2="12" y2="20.59"/><line class="cls-1" x1="3.41" y1="12" x2="7.23" y2="12"/><line class="cls-1" x1="16.77" y1="12" x2="20.59" y2="12"/><line class="cls-1" x1="5.93" y1="5.93" x2="8.63" y2="8.63"/><line class="cls-1" x1="15.37" y1="15.37" x2="18.07" y2="18.07"/><line class="cls-1" x1="5.93" y1="18.07" x2="8.63" y2="15.37"/><line class="cls-1" x1="15.37" y1="8.63" x2="18.07" y2="5.93"/></svg>
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