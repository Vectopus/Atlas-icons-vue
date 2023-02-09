
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="3.89" cy="18.17" r="2.39"/><path class="cls-1" d="M23.5,20.57H10.11A1.91,1.91,0,0,1,8.2,18.65h0a1.91,1.91,0,0,1,1.91-1.91h9.56V3.35l-2.1-1.92"/></svg>
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