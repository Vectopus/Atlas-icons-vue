
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="suster"><rect class="cls-1" x="4.36" y="15.82" width="15.27" height="3.82"/><path class="cls-1" d="M19.64,15.82H4.36L1.5,10.09Q6.75,4.36,12,4.36t10.5,5.73Z"/><line class="cls-1" x1="9.14" y1="10.09" x2="14.86" y2="10.09"/><line class="cls-1" x1="12" y1="7.23" x2="12" y2="12.95"/></g></svg>
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