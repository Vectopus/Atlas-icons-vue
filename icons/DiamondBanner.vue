
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="16.78 16.76 21.57 16.76 20.61 18.67 21.57 20.59 16.78 20.59 16.78 16.76"/><polygon class="cls-1" points="7.22 16.76 2.44 16.76 3.39 18.67 2.44 20.59 7.22 20.59 7.22 16.76"/><rect class="cls-1" x="7.22" y="18.67" width="9.57" height="3.83" transform="translate(24 41.17) rotate(180)"/><polygon class="cls-1" points="17.74 9.11 12 15.8 6.26 9.11 8.17 6.24 15.83 6.24 17.74 9.11"/><line class="cls-1" x1="20.61" y1="11.02" x2="22.52" y2="11.02"/><line class="cls-1" x1="1.48" y1="11.02" x2="3.39" y2="11.02"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="2.41"/><line class="cls-1" x1="19.44" y1="3.58" x2="18.09" y2="4.93"/><line class="cls-1" x1="4.56" y1="3.58" x2="5.91" y2="4.93"/></svg>
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