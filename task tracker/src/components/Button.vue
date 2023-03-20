<template>
    <button :style="{background:color}" class="btn">{{ text }}</button>
</template>

<script lang="js">
export default {
    name:"Button",
    props:{
        text:String,
        color:String
    }
}
</script>