<template>
    <div>
        <School></School>
        <Student/>
    </div>
</template>

<script>
    //引入组件
    import School from './School.vue'
    import Student from './Student'
    export default {
        name:'App',
        //注册组件
        comments:{
            School,
            Student
        }

    }
</script>

<style>

</style>