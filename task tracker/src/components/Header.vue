<template>
    <h1>{{ title }}</h1>
</template>

<script lang="js">
export default {
    name:"Header",
    props:{
        title:String,
    }
}
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>