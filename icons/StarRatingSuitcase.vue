
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="6.3" y="12.95" width="11.4" height="8.55"/><rect class="cls-1" x="10.1" y="10.1" width="3.8" height="2.85"/><polyline class="cls-1" points="6.33 15.76 11.97 17.7 17.67 15.8"/><polygon class="cls-1" points="12 2.5 12.46 3.44 13.5 3.59 12.75 4.32 12.93 5.35 12 4.86 11.07 5.35 11.25 4.32 10.5 3.59 11.54 3.44 12 2.5"/><polygon class="cls-1" points="19.6 5.35 20.06 6.29 21.1 6.44 20.35 7.17 20.53 8.2 19.6 7.71 18.67 8.2 18.85 7.17 18.1 6.44 19.14 6.29 19.6 5.35"/><polygon class="cls-1" points="4.4 5.35 4.86 6.29 5.9 6.44 5.15 7.17 5.33 8.2 4.4 7.71 3.47 8.2 3.65 7.17 2.9 6.44 3.94 6.29 4.4 5.35"/></svg>
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