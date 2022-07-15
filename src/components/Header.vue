<template>
    <header>
        <div class="logo">
            <img src="../assets/logo.png" alt="">
            <h1>eveli.todo</h1>
        </div>
    </header>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
header{
    width: 100%;
    height: 80px;
    background-color: #253f4b;
    .logo{
        height: 100%;
        padding-left: 10px;
        display: flex;
        gap: 10px;
        align-items: center;
        img{
            height: 50px;
        }
        h1{
            color: white;
            font-size: 18px;
            font-weight: 400;
        }
    }
}
</style>