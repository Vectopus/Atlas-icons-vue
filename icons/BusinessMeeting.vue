
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.14,10.09A2.86,2.86,0,0,1,12,7.23h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><circle class="cls-1" cx="20.59" cy="13.91" r="1.91"/><circle class="cls-1" cx="20.59" cy="20.59" r="1.91"/><circle class="cls-1" cx="3.41" cy="13.91" r="1.91"/><circle class="cls-1" cx="3.41" cy="20.59" r="1.91"/><rect class="cls-1" x="8.18" y="12" width="7.64" height="10.5"/></svg>
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