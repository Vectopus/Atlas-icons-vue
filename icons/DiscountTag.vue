
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="discount"><polygon class="cls-1" points="19.55 22.38 4.45 22.38 4.45 7.27 10.11 1.61 13.89 1.61 19.55 7.27 19.55 22.38"/><line class="cls-1" x1="11.06" y1="5.38" x2="12.94" y2="5.38"/><line class="cls-1" x1="14.83" y1="10.1" x2="9.17" y2="18.6"/><circle class="cls-1" cx="8.7" cy="11.52" r="0.47"/><circle class="cls-1" cx="15.3" cy="17.19" r="0.47"/></g></svg>
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