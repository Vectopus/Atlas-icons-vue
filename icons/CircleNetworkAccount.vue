
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><circle class="cls-1" cx="12" cy="20.59" r="1.91"/><circle class="cls-1" cx="4.36" cy="7.23" r="1.91"/><circle class="cls-1" cx="19.64" cy="16.77" r="1.91"/><circle class="cls-1" cx="4.36" cy="16.77" r="1.91"/><circle class="cls-1" cx="19.64" cy="7.23" r="1.91"/><path class="cls-1" d="M9.14,16.77A2.86,2.86,0,0,1,12,13.91h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="12" cy="10.09" r="1.91"/><line class="cls-1" x1="10.29" y1="19.74" x2="6.06" y2="17.62"/><line class="cls-1" x1="19.64" y1="14.86" x2="19.64" y2="9.14"/><line class="cls-1" x1="10.29" y1="4.26" x2="6.06" y2="6.38"/><line class="cls-1" x1="4.36" y1="14.86" x2="4.36" y2="9.14"/><line class="cls-1" x1="17.94" y1="6.38" x2="13.71" y2="4.26"/><line class="cls-1" x1="17.94" y1="17.62" x2="13.71" y2="19.74"/></svg>
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