
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="3.41" cy="3.41" r="1.91"/><circle class="cls-1" cx="20.59" cy="20.59" r="1.91"/><circle class="cls-1" cx="20.59" cy="3.41" r="1.91"/><circle class="cls-1" cx="3.41" cy="20.59" r="1.91"/><path class="cls-1" d="M15.38,2.45a10.14,10.14,0,0,1,6.17,6.17"/><path class="cls-1" d="M2.45,8.62A10.14,10.14,0,0,1,8.62,2.45"/><path class="cls-1" d="M2.45,15.38a10.14,10.14,0,0,0,6.17,6.17"/><path class="cls-1" d="M15.38,21.55a10.14,10.14,0,0,0,6.17-6.17"/><circle class="cls-1" cx="12" cy="12" r="6.68"/></svg>
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