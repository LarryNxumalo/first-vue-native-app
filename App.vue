<template>
    <text-input
        :style="{height: 40, width: 100, borderColor: 'gray', borderWidth: 1}"
        v-model="text"
      />
</template>
<script>
    export default {
        data: function() {
            return {
                text: ''
            };
        }
    }
</script>
