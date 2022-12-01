
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 9.14 12.59 10.39 13.91 10.6 12.96 11.57 13.18 12.96 12 12.3 10.82 12.96 11.04 11.57 10.09 10.6 11.41 10.39 12 9.14"/><polygon class="cls-1" points="17.73 9.14 18.32 10.39 19.64 10.6 18.68 11.57 18.91 12.96 17.73 12.3 16.55 12.96 16.77 11.57 15.82 10.6 17.14 10.39 17.73 9.14"/><polygon class="cls-1" points="6.27 9.14 6.86 10.39 8.18 10.6 7.23 11.57 7.45 12.96 6.27 12.3 5.09 12.96 5.32 11.57 4.36 10.6 5.68 10.39 6.27 9.14"/><path class="cls-2" d="M1.5,8.18v5.73a1.91,1.91,0,0,0,1.91,1.91h6.68L12,17.73l1.91-1.91h6.68a1.91,1.91,0,0,0,1.91-1.91V8.18a1.91,1.91,0,0,0-1.91-1.91H3.41A1.91,1.91,0,0,0,1.5,8.18Z"/></svg>
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
    .cls-1{fill:currentColor;}.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>