
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.42" y="6.25" width="3.83" height="11.5" rx="1.92"/><rect class="cls-1" x="17.75" y="6.25" width="3.83" height="11.5" rx="1.92"/><line class="cls-1" x1="0.5" y1="12" x2="2.42" y2="12"/><line class="cls-1" x1="6.25" y1="12" x2="17.75" y2="12"/><line class="cls-1" x1="21.58" y1="12" x2="23.5" y2="12"/></svg>
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