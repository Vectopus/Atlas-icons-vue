
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="15.92" cy="15.92" r="6.58"/><polygon class="cls-1" points="11.63 10.91 10.91 11.63 6.62 11.63 5.91 9.48 9.48 5.91 11.63 6.62 11.63 10.91"/><line class="cls-1" x1="8.15" y1="0.5" x2="8.15" y2="3.37"/><line class="cls-1" x1="0.5" y1="8.15" x2="3.37" y2="8.15"/><line class="cls-1" x1="1.46" y1="1.46" x2="3.85" y2="3.85"/></svg>
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