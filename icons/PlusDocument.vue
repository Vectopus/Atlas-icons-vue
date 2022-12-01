
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="document"><polygon class="cls-1" points="20.59 8.18 20.59 22.5 3.41 22.5 3.41 1.5 15.82 1.5 20.59 6.27 20.59 7.23 20.59 8.18"/><polyline class="cls-1" points="20.59 7.23 14.86 7.23 14.86 1.5"/><line class="cls-1" x1="6.27" y1="7.23" x2="12" y2="7.23"/><line class="cls-1" x1="9.14" y1="4.36" x2="9.14" y2="10.09"/><line class="cls-1" x1="9.14" y1="13.91" x2="17.73" y2="13.91"/><line class="cls-1" x1="6.27" y1="17.73" x2="17.73" y2="17.73"/><line class="cls-1" x1="6.27" y1="13.91" x2="8.18" y2="13.91"/></g></svg>
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