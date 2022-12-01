
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.54,10.06H1.46V7.19A5.74,5.74,0,0,1,7.21,1.44H20.15a2.39,2.39,0,0,1,2.39,2.39v6.23Z"/><polygon class="cls-1" points="7.21 20.6 3.38 21.56 3.38 10.06 7.21 10.06 7.21 20.6"/><rect class="cls-1" x="14.88" y="10.06" width="5.75" height="5.75"/><line class="cls-1" x1="23.5" y1="15.81" x2="0.5" y2="15.81"/><rect class="cls-1" x="12.96" y="1.44" width="9.58" height="4.79" rx="2.4"/></svg>
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