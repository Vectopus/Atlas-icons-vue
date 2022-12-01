
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.46" y="9.15" width="21.08" height="7.67"/><rect class="cls-1" x="3.38" y="5.31" width="17.25" height="3.83"/><line class="cls-1" x1="23.5" y1="5.31" x2="0.5" y2="5.31"/><path class="cls-1" d="M15.83,13h0Z"/><path class="cls-1" d="M19.67,13h0Z"/><line class="cls-1" x1="11.04" y1="12.98" x2="5.29" y2="12.98"/><line class="cls-1" x1="4.33" y1="19.69" x2="4.33" y2="16.81"/><line class="cls-1" x1="19.67" y1="19.69" x2="19.67" y2="16.81"/></svg>
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