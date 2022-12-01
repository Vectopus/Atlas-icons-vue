
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><polygon class="cls-1" points="4.32 1.47 19.66 1.47 11.99 9.14 4.32 1.47"/><polygon class="cls-1" points="19.66 22.57 4.32 22.57 11.99 14.89 19.66 22.57"/><line class="cls-1" x1="9.11" y1="12.02" x2="11.03" y2="12.02"/><line class="cls-1" x1="12.95" y1="12.02" x2="14.87" y2="12.02"/><line class="cls-1" x1="1.44" y1="12.02" x2="3.36" y2="12.02"/><line class="cls-1" x1="5.28" y1="12.02" x2="7.19" y2="12.02"/><line class="cls-1" x1="16.78" y1="12.02" x2="18.7" y2="12.02"/><line class="cls-1" x1="20.62" y1="12.02" x2="22.54" y2="12.02"/></g></svg>
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