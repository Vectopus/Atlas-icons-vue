
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.83,23.5a2.87,2.87,0,0,1,2.87-2.87h0a2.88,2.88,0,0,1,2.87,2.87"/><circle class="cls-1" cx="18.7" cy="16.8" r="1.91"/><path class="cls-1" d="M2.43,23.5A2.88,2.88,0,0,1,5.3,20.63h0A2.87,2.87,0,0,1,8.17,23.5"/><circle class="cls-1" cx="5.3" cy="16.8" r="1.91"/><circle class="cls-1" cx="7.22" cy="5.33"/><circle class="cls-1" cx="12" cy="5.33"/><circle class="cls-1" cx="16.78" cy="5.33"/><polygon class="cls-1" points="1.48 1.5 1.48 9.15 5.3 9.15 5.3 11.06 8.17 9.15 15.83 9.15 18.7 11.06 18.7 9.15 22.52 9.15 22.52 1.5 1.48 1.5"/></svg>
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