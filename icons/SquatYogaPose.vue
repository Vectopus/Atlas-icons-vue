
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="4.36" r="2.86"/><polyline class="cls-1" points="12.96 13.91 17.73 13.91 17.73 12.96 15.82 9.14 8.18 9.14 6.27 12.96 6.27 13.91 11.04 13.91"/><polyline class="cls-1" points="18.68 22.5 15.82 22.5 15.82 21.55 19.64 17.73 19.64 16.77 12.96 16.77 11.04 16.77 4.36 16.77 4.36 17.73 8.18 21.55 8.18 22.5 5.32 22.5"/></svg>
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