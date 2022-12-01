
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><path class="cls-1" d="M12,11h0a3.82,3.82,0,0,1,3.82,3.82v0a1.91,1.91,0,0,1-1.91,1.91H10.09a1.91,1.91,0,0,1-1.91-1.91v0A3.82,3.82,0,0,1,12,11Z"/><ellipse class="cls-1" cx="10.09" cy="7.7" rx="0.95" ry="1.43"/><ellipse class="cls-1" cx="13.91" cy="7.7" rx="0.95" ry="1.43"/><circle class="cls-1" cx="17.25" cy="10.57" r="0.48"/><circle class="cls-1" cx="6.75" cy="10.57" r="0.48"/></svg>
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