
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.61,5.32H7.2V1.5H17.7l1.91,1.91Z"/><line class="cls-1" x1="3.39" y1="5.32" x2="7.2" y2="5.32"/><path class="cls-1" d="M19.61,9.14H7.2V13H17.7l1.91-1.9Z"/><line class="cls-1" x1="3.39" y1="9.14" x2="7.2" y2="9.14"/><rect class="cls-1" x="9.11" y="5.32" width="3.82" height="3.82"/><rect class="cls-1" x="9.11" y="12.95" width="3.82" height="9.55"/></svg>
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