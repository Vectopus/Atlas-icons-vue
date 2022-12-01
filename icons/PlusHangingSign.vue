
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="clinic"><rect class="cls-1" x="5.33" y="5.33" width="17.22" height="15.3"/><polyline class="cls-1" points="23.5 1.5 1.5 1.5 1.5 23.5"/><line class="cls-1" x1="9.15" y1="1.5" x2="9.15" y2="8.2"/><line class="cls-1" x1="18.72" y1="1.5" x2="18.72" y2="8.2"/><line class="cls-1" x1="10.11" y1="12.98" x2="17.76" y2="12.98"/><line class="cls-1" x1="13.93" y1="9.15" x2="13.93" y2="16.8"/></g></svg>
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