
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="19.5 1.69 14.81 1.69 12.75 5.44 4.5 5.44 4.5 10.13 10.17 10.13 4.5 20.44 4.5 22.31 9.19 22.31 11.25 18.56 19.5 18.56 19.5 13.88 13.83 13.88 19.5 3.56 19.5 1.69"/></svg>
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