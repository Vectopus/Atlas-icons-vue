
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="8.15" cy="20.61" r="1.91"/><circle class="cls-1" cx="16.76" cy="20.61" r="1.91"/><path class="cls-1" d="M16.76,18.7H5.68a1.35,1.35,0,0,1-1.35-1.36h0a1.34,1.34,0,0,1,.39-.95L7.2,13.91,4.84,3.7A2.87,2.87,0,0,0,2,1.48H.5"/><polyline class="cls-1" points="22.5 3.39 22.5 5.3 20.59 13.91 7.2 13.91"/><rect class="cls-1" x="11.02" y="6.26" width="5.74" height="4.78"/><polygon class="cls-1" points="13.89 2.44 10.06 6.26 17.72 6.26 13.89 2.44"/></svg>
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