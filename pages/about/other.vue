<template>
    <h1>Other Page</h1>
    <butonum @click = "count++"/>
    {{ count }}
</template>

<script lang="ts" setup>
    const count = ref(0)
</script>