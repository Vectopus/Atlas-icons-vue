
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="7.21" y="1.48" width="4.79" height="21.08" rx="2.4"/><rect class="cls-1" x="12" y="1.48" width="4.79" height="21.08" rx="2.4"/><rect class="cls-1" x="1.46" y="1.48" width="1.92" height="6.71"/><polygon class="cls-1" points="2.42 8.19 2.42 10.1 2.42 23.52 2.42 23.52 2.42 8.19"/><line class="cls-1" x1="0.5" y1="20.65" x2="4.33" y2="20.65"/><rect class="cls-1" x="20.63" y="1.48" width="1.92" height="6.71"/><polygon class="cls-1" points="21.58 8.19 21.58 10.1 21.58 23.52 21.58 23.52 21.58 8.19"/><line class="cls-1" x1="19.67" y1="20.65" x2="23.5" y2="20.65"/><rect class="cls-1" x="7.21" y="9.15" width="4.79" height="5.75" rx="2.4"/><rect class="cls-1" x="12" y="9.15" width="4.79" height="5.75" rx="2.4"/></svg>
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