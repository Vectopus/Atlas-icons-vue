
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="19 1 22 4 19 7"/><polyline class="cls-1" points="5 23 2 20 5 17"/><circle class="cls-1" cx="12" cy="12" r="3"/><path class="cls-1" d="M12,9V8a4,4,0,0,1,4-4h6"/><path class="cls-1" d="M12,15v1a4,4,0,0,1-4,4H2"/><polyline class="cls-1" points="23 19 20 22 17 19"/><polyline class="cls-1" points="1 5 4 2 7 5"/><path class="cls-1" d="M15,12h1a4,4,0,0,1,4,4v6"/><path class="cls-1" d="M9,12H8A4,4,0,0,1,4,8V2"/></svg>
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