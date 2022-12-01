
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="5.31" x2="23.5" y2="5.31"/><line class="cls-1" x1="2.42" y1="5.31" x2="2.42" y2="19.69"/><rect class="cls-1" x="13.92" y="10.1" width="7.67" height="4.79"/><rect class="cls-1" x="13.92" y="5.31" width="7.67" height="4.79"/><line class="cls-1" x1="21.58" y1="19.69" x2="21.58" y2="14.9"/><line class="cls-1" x1="17.75" y1="7.23" x2="17.75" y2="5.31"/><line class="cls-1" x1="17.75" y1="12.02" x2="17.75" y2="10.1"/></svg>
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