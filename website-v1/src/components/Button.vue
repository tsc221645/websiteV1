<template>
    <button :style={background:color} class="button1">{{text}}</button>
</template>

<script>
    export default{
        name:'Button',
        props:{
            text: String,
            color: String
        }


}

</script>