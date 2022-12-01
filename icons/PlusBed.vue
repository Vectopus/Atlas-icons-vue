
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="bed"><line class="cls-1" x1="1.5" y1="6.27" x2="1.5" y2="23.45"/><rect class="cls-1" x="1.5" y="13.91" width="10.5" height="3.82"/><line class="cls-1" x1="22.5" y1="23.45" x2="22.5" y2="13.91"/><rect class="cls-1" x="12" y="13.91" width="10.5" height="5.73"/><line class="cls-1" x1="22.5" y1="11.05" x2="22.5" y2="13.91"/><line class="cls-1" x1="12.95" y1="0.55" x2="12.95" y2="6.27"/><line class="cls-1" x1="10.09" y1="3.41" x2="15.82" y2="3.41"/><line class="cls-1" x1="3.41" y1="8.18" x2="9.14" y2="13.91"/></g></svg>
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