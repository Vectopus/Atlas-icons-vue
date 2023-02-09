
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="5 4 2 7 5 10"/><polyline class="cls-1" points="19 20 22 17 19 14"/><line class="cls-1" x1="12" y1="7" x2="2" y2="7"/><line class="cls-1" x1="22" y1="17" x2="12" y2="17"/><circle class="cls-1" cx="12" cy="12" r="5"/></svg>
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