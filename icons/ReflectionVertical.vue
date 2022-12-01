
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><polygon class="cls-1" points="22.55 4.34 22.55 19.69 14.87 12.02 22.55 4.34"/><polygon class="cls-1" points="1.45 19.69 1.45 4.34 9.12 12.02 1.45 19.69"/><line class="cls-1" x1="12" y1="9.14" x2="12" y2="11.06"/><line class="cls-1" x1="12" y1="12.98" x2="12" y2="14.89"/><line class="cls-1" x1="12" y1="1.47" x2="12" y2="3.39"/><line class="cls-1" x1="12" y1="5.3" x2="12" y2="7.22"/><line class="cls-1" x1="12" y1="16.81" x2="12" y2="18.73"/><line class="cls-1" x1="12" y1="20.65" x2="12" y2="22.57"/></g></svg>
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