
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="7.23" y1="18.66" x2="9.14" y2="18.66"/><line class="cls-1" x1="11.05" y1="18.66" x2="12.95" y2="18.66"/><line class="cls-1" x1="14.86" y1="18.66" x2="16.77" y2="18.66"/><path class="cls-1" d="M17.73,13.89l-1,.95H8.18l-.95-.95H1.5v4.77a3.82,3.82,0,0,1,3.82,3.82h8.59a8.6,8.6,0,0,0,8.59-8.59H17.73Z"/><line class="cls-1" x1="12" y1="0.52" x2="12" y2="14.84"/><path class="cls-1" d="M12,1.48h0a7.64,7.64,0,0,1,7.64,7.63v1L12,12Z"/><polygon class="cls-1" points="12 5.29 7.23 5.29 8.18 3.39 7.23 1.48 12 1.48 12 5.29"/></svg>
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