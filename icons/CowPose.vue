
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="20.59" cy="7.22" r="1.91"/><path class="cls-1" d="M15.8,13H8.15V11a1.92,1.92,0,0,1,1.92-1.91H15.8A1.92,1.92,0,0,1,17.72,11V18.7h2.87"/><polyline class="cls-1" points="8.15 12 8.15 18.7 0.5 18.7"/></svg>
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