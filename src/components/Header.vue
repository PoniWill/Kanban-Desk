<template>
    <header>
        <div class="logo">
            <img src="../assets/logo.png" alt="">
            <h1>eveli.todo</h1>
        </div>
        <ul class="user-menu">
            <li>Задачи</li>
            <li class="selected">Проекты</li>
            <li>Статистика</li>
            <li>Финансы</li>
            <li>План</li>
            <li>Пользователи</li>
        </ul>
        <div class="profile">
            <div class="money">
                60 000 ₽
            </div>
            <div class="notifications">
                <img src="src/assets/icons/notification.png">
            </div>
            <div class="user-profile">
                <img class="photo" src="src/assets/profile-logo/photo_2021-05-15_16-45-17.jpg">
                <span> Alexandr</span>
                <img class="img-active" src="src/assets/icons/open-menu.png">
            </div>
        </div>
    </header>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
header{
    display: flex;
    justify-content: space-between;
    align-items: center;
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
     .user-menu{
        display: flex;
        flex-direction: row;
        align-items: center;
        margin: 25px;
        padding: 25px;
        list-style-type: none;
        gap: 35px;
            li{
                font-weight: bold;
                color: #b8b8b8;
                font-size: 20px;
                &.selected{
                    color: white;
                    border-bottom: 2px solid #e96880;
                }
            }
    }
    .profile{
        display: flex;
        flex-direction: row;
        align-items: center;
        gap: 20px;
        border: 0;
        margin-right: 30px;
        border-radius: 45;
        font-weight: bold;
        color: #b8b8b8;
        .money{
            font-weight: 400;
            color: white;
            }
        .notifications{
            img{
                width: 25px;
                height: 25px;
            }
        }
        .user-profile{
            display: flex;
            flex-direction: row;
            align-items: center;
            gap: 10px;
            color: #b8b8b8;
            font-size: 20px;
            .photo{
                width: 32px;
                height: 32px;
                border-radius: 16px;
            }
                span{
                    font-weight: 300;
                    color: white;
                }
            .img-active{
                transition: 0.5s;
                &:hover{
                    transform: rotate(-90deg);
                    transition: 0.5s;
                }
            }
        }
    }
}
</style>