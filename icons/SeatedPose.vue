
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="4.36" r="2.86"/><polyline class="cls-1" points="2.46 17.73 9.14 9.14 14.86 9.14 21.55 17.73"/><polyline class="cls-1" points="12.96 22.5 20.59 22.5 20.59 20.59 13.91 17.73 13.91 12"/><polyline class="cls-1" points="11.04 22.5 3.41 22.5 3.41 20.59 10.09 17.73 10.09 12"/></svg>
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