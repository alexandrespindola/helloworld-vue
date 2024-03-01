<template>
<h1 v-show="age < 18">É menor de idade</h1>
<h1>É maior de idade</h1>
</template>

<script lang="ts" setup>
let age = 10
</script>

<style scoped>

</style>