
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="first_aid" data-name="first aid"><rect class="cls-1" x="1.5" y="6.27" width="21" height="15.27" rx="1.91"/><polygon class="cls-1" points="15.82 6.27 8.18 6.27 9.14 2.46 14.86 2.46 15.82 6.27"/><line class="cls-1" x1="9.14" y1="12" x2="14.86" y2="12"/><line class="cls-1" x1="12" y1="9.14" x2="12" y2="14.86"/><line class="cls-1" x1="1.5" y1="17.73" x2="22.5" y2="17.73"/></g></svg>
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