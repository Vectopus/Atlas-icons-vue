
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="7.22 22.5 2.44 22.5 3.39 20.59 2.44 18.67 7.22 18.67 7.22 22.5"/><polygon class="cls-1" points="16.78 22.5 21.57 22.5 20.61 20.59 21.57 18.67 16.78 18.67 16.78 22.5"/><rect class="cls-1" x="7.22" y="16.76" width="9.57" height="3.83"/><circle class="cls-1" cx="12" cy="3.37" r="1.91"/><polyline class="cls-1" points="9.13 14.85 9.13 7.2 14.87 7.2 14.87 14.85"/><polyline class="cls-1" points="14.87 7.2 15.83 7.2 17.74 5.28 17.74 0.5"/><polyline class="cls-1" points="9.13 7.2 8.17 7.2 6.26 5.28 6.26 0.5"/></svg>
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