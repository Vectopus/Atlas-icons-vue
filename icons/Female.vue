
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="female"><circle class="cls-1" cx="14.86" cy="9.14" r="7.64"/><circle class="cls-1" cx="14.86" cy="9.14" r="3.82"/><line class="cls-1" x1="1.5" y1="22.5" x2="9.61" y2="14.39"/><line class="cls-1" x1="1.5" y1="14.86" x2="9.14" y2="22.5"/></g></svg>
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