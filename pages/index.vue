<template>
<img src="../assets/img/logo.png" alt="logo" width="200px">

    <h1>Home Page</h1>
    <butonum @click="count++" />
    {{count}}


</template>


<script lang="ts" setup>

    const count = ref(0)
</script>
