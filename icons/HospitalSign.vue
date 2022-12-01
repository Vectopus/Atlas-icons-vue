
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="hospital_sign" data-name="hospital sign"><rect class="cls-1" x="1.5" y="1.5" width="21" height="21" rx="1.91"/><line class="cls-1" x1="8.18" y1="17.73" x2="8.18" y2="6.27"/><line class="cls-1" x1="15.82" y1="6.27" x2="15.82" y2="17.73"/><line class="cls-1" x1="15.82" y1="12" x2="8.18" y2="12"/></g></svg>
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