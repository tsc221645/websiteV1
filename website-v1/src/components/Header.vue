<template>
    <header>
        <h1>{{ title }} </h1>
        <Button text="Press me!" />
    </header>
</template>


<script>
    //imports
    import Button from './Button'

    export default{

        name: 'Header',

        //definition of props
        props:{
            title:{
                type: String,
                default: 'Hello world'
            }
        },

        //definition of components
        components:{
            Button,
        }
    }
</script>

<style scoped>
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }

</style>