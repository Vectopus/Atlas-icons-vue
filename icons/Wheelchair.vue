
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="Chairwheel"><circle class="cls-1" cx="7.21" cy="16.79" r="5.75"/><circle class="cls-1" cx="17.75" cy="20.63" r="1.92"/><path class="cls-1" d="M.5,1.46H2.42A2.88,2.88,0,0,1,5.29,4.33v5.75"/><polyline class="cls-1" points="15.83 9.13 15.83 14.88 12.96 14.88"/><polyline class="cls-1" points="5.29 11.38 5.29 10.08 5.29 6.25 17.75 6.25"/><polyline class="cls-1" points="19.67 20.63 18.71 14.88 12.96 14.88"/><line class="cls-1" x1="23.5" y1="20.63" x2="19.67" y2="20.63"/></g></svg>
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