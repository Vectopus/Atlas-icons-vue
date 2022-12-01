
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,12.52V7.23H2.45v10.5a4.77,4.77,0,0,0,8.82,2.53"/><rect class="cls-1" x="3.41" y="1.5" width="7.64" height="5.73"/><line class="cls-1" x1="15.82" y1="12.95" x2="15.82" y2="17.73"/><line class="cls-1" x1="15.82" y1="18.68" x2="15.82" y2="20.59"/><circle class="cls-1" cx="15.82" cy="16.77" r="5.73"/><line class="cls-1" x1="5.32" y1="11.05" x2="9.14" y2="11.05"/></svg>
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