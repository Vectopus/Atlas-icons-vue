
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="20.59" cy="6.24" r="1.91"/><polyline class="cls-1" points="19.63 16.47 19.63 18.67 21.54 18.67"/><path class="cls-1" d="M21.54,14a8.44,8.44,0,0,0,.71-1.89,1.68,1.68,0,0,0-1.66-2h-1v6.4a8.56,8.56,0,0,1-5.74,2.2H7.1a7.8,7.8,0,0,1-3.73-1h0l-2.87,1"/><path class="cls-1" d="M19.59,9.11h0a6.61,6.61,0,0,1-4.42,6.24h0a1.92,1.92,0,0,0-1.28,1.81v1.51"/></svg>
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