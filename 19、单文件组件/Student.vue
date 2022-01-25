<template>
    <!--组件的结构-->
    <div class="demo">
        <h2>学生姓名：{{name}}</h2>
        <h2>学生年龄：{{age}}</h2>
    </div>
</template>>
    

<script>
    //组件交互相关的代码(数据、方法等等)
    const Student=Vue.extend({
        name:'Student',
        data(){
            return{
                name:'尚硅谷',
                age:30
            }
        }
    })
    export default Student
</script>

<style>
    /*组件的样式*/
    .demo{
        background-color: orange;
    }
</style>