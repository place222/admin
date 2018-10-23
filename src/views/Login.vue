<template>
    <el-form label-width="80px" class="login">
        <el-form-item label="用户名">
            <el-input></el-input>
        </el-form-item>
        <el-form-item label="密码">
            <el-input></el-input>
        </el-form-item>
        <el-form-item>
            <el-button>登入</el-button>
        </el-form-item>
    </el-form>
</template>

<script>
export default {
    name:'login'
}
</script>
<style>
.login{
    width: 230px;
    margin: 300px auto 0 auto;
}
</style>
