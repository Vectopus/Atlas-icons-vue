
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.43" y="4.37" width="4.78" height="17.22" rx="2.39"/><rect class="cls-1" x="7.22" y="4.37" width="4.78" height="17.22" rx="2.39"/><rect class="cls-1" x="12" y="4.37" width="4.78" height="17.22" rx="2.39"/><rect class="cls-1" x="16.78" y="4.37" width="4.78" height="17.22" rx="2.39"/><line class="cls-1" x1="0.52" y1="8.2" x2="2.43" y2="8.2"/><line class="cls-1" x1="0.52" y1="17.76" x2="2.43" y2="17.76"/><line class="cls-1" x1="21.57" y1="8.2" x2="23.48" y2="8.2"/><line class="cls-1" x1="21.57" y1="17.76" x2="23.48" y2="17.76"/><line class="cls-1" x1="4.35" y1="21.59" x2="4.35" y2="23.5"/><line class="cls-1" x1="19.65" y1="21.59" x2="19.65" y2="23.5"/><line class="cls-1" x1="18.7" y1="1.5" x2="18.7" y2="4.37"/><line class="cls-1" x1="16.78" y1="1.5" x2="20.61" y2="1.5"/></svg>
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