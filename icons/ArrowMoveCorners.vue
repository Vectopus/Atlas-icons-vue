
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="13.9 10.1 22.43 1.57 22.5 1.5"/><polyline class="cls-1" points="10.1 13.9 1.57 22.43 1.5 22.5"/><polyline class="cls-1" points="1.57 14.85 1.57 22.43 9.15 22.43"/><polyline class="cls-1" points="22.43 9.15 22.43 1.57 14.85 1.57"/><polyline class="cls-1" points="22.5 22.5 22.43 22.43 13.9 13.9"/><polyline class="cls-1" points="1.5 1.5 1.57 1.57 10.1 10.1"/><polyline class="cls-1" points="9.15 1.57 1.57 1.57 1.57 9.15"/><polyline class="cls-1" points="14.85 22.43 22.43 22.43 22.43 14.85"/><circle class="cls-1" cx="12" cy="12" r="2.85"/></svg>
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