
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 6.27 12.6 7.53 13.95 7.73 12.97 8.71 13.2 10.09 12 9.44 10.8 10.09 11.03 8.71 10.05 7.73 11.4 7.53 12 6.27"/><polygon class="cls-1" points="16.77 16.77 21.55 16.77 20.59 18.68 21.55 20.59 16.77 20.59 16.77 16.77"/><polygon class="cls-1" points="7.23 16.77 2.46 16.77 3.41 18.68 2.46 20.59 7.23 20.59 7.23 16.77"/><rect class="cls-1" x="7.23" y="18.68" width="9.55" height="3.82" transform="translate(24 41.18) rotate(180)"/><path class="cls-1" d="M12,16.77h0a9.83,9.83,0,0,1-6.68-9V2.35L12,1.5l6.68.85V7.77A9.83,9.83,0,0,1,12,16.77Z"/></svg>
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