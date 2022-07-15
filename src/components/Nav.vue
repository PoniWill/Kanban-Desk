<template>
    <nav>
        <ul>
            <li>
                <img src="../assets/icons/search.png" alt="">
            </li>
            <li>
                <img src="../assets/icons/plus.png" alt="">
            </li>
            <li>
                <img src="../assets/icons/menu.png" alt="">
            </li>
        </ul>
    </nav>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
nav{
    width: 80px;
    height: 100vh;
    background-color: #223a45;
    ul{
        margin: 0;
        list-style-type: none;
        display: flex;
        flex-direction:column;
        align-items: center;
        gap: 20px;
        padding: 25px 0;
        li{
            width: 20px;
            height: 20px;
            img{
                width: 100%;
                height: 100%;
            }
        }
    }
}
</style>