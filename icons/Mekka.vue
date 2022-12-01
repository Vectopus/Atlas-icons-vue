
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="21.58" x2="23.5" y2="21.58"/><rect class="cls-1" x="2.42" y="2.42" width="19.17" height="19.17"/><line class="cls-1" x1="2.42" y1="6.25" x2="21.58" y2="6.25"/><rect class="cls-1" x="7.21" y="14.88" width="4.79" height="6.71"/><line class="cls-1" x1="6.25" y1="10.08" x2="8.17" y2="10.08"/><line class="cls-1" x1="15.83" y1="10.08" x2="17.75" y2="10.08"/><line class="cls-1" x1="10.08" y1="10.08" x2="13.92" y2="10.08"/><line class="cls-1" x1="2.42" y1="10.08" x2="5.29" y2="10.08"/><line class="cls-1" x1="18.71" y1="10.08" x2="21.58" y2="10.08"/></svg>
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