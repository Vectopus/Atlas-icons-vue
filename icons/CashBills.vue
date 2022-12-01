
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="money_stack" data-name="money stack"><line class="cls-1" x1="4.36" y1="15.82" x2="6.27" y2="15.82"/><line class="cls-1" x1="17.73" y1="15.82" x2="19.64" y2="15.82"/><rect class="cls-2" x="1.5" y="9.14" width="21" height="13.36"/><line class="cls-2" x1="3.41" y1="5.32" x2="20.59" y2="5.32"/><line class="cls-2" x1="5.32" y1="1.5" x2="18.68" y2="1.5"/><circle class="cls-2" cx="12" cy="15.82" r="3.82"/><line class="cls-1" x1="4.36" y1="15.82" x2="6.27" y2="15.82"/><line class="cls-1" x1="17.73" y1="15.82" x2="19.64" y2="15.82"/></g></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{stroke-linecap:square;}
</style>