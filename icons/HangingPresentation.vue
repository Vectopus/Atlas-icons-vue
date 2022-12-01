
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="presentation"><line class="cls-1" x1="0.5" y1="1.46" x2="23.5" y2="1.46"/><line class="cls-1" x1="0.5" y1="15.83" x2="23.5" y2="15.83"/><rect class="cls-2" x="2.42" y="1.46" width="19.17" height="14.38"/><line class="cls-2" x1="12" y1="15.83" x2="12" y2="18.71"/><circle class="cls-2" cx="12" cy="20.63" r="1.92"/></g></svg>
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