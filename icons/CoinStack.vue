
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="coins_2" data-name="coins 2"><rect class="cls-1" x="4.36" y="18.68" width="13.36" height="3.82"/><rect class="cls-1" x="6.27" y="14.86" width="13.36" height="3.82"/><circle class="cls-1" cx="12" cy="8.18" r="6.68"/><circle class="cls-1" cx="12" cy="8.18" r="2.86"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>