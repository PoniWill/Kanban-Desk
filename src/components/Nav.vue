<template>
    <nav>
        <ul>
            <li><img src="../assets/icons/search.png" alt=""></li>
            <li><img src="../assets/icons/plus.png" alt=""></li>
            <li><img src="../assets/icons/menu.png" alt=""></li>
        </ul>
        <div class="show">
            <img src="../assets/icons/open-menu.png" alt="">
        </div>
        <div class="help">
            <img src="../assets/icons/help.png" alt="">
        </div>
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

    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
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
    .show{
        display: flex;
        align-self: flex-end;
        justify-content: center;
        align-items: center;
        width: 40px;
        height: 80px;
        border-bottom-left-radius: 40px;
        border-top-left-radius: 40px;
        background-color: rgba(255, 255, 255, 0.2);
        img{
            transform: rotate(180deg);
            transition: .5s;
            &:hover{
                transition: .5s;
                transform: rotate(0deg);
            }
        }
    }
    .help{
        width: 24px;
        height: 24px;
        padding-bottom: 24px;
        img{
            width: 100%;
            height: 100%;
        }
    }
}
</style>