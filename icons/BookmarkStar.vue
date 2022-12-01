
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="18.67 21.5 12 17.69 5.33 21.5 5.33 1.5 18.67 1.5 18.67 21.5"/><polygon class="cls-1" points="12 7.87 12.59 9.06 13.9 9.25 12.95 10.18 13.18 11.49 12 10.87 10.82 11.49 11.05 10.18 10.1 9.25 11.41 9.06 12 7.87"/></svg>
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