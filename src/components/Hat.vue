<template>
    <section>
        <div class="hat">
            <h2>Проекты</h2>
            <div class="btnPlay">
                <img src="src/assets/icons/playBtn.png">
            </div>
            <span>CRM - система/Процессы</span>
        </div>
        <div class="proc">
            <span><img src="src/assets/icons/wave.png">Процессы проекта CRM - система</span>
            <button>Knopa</button>
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    section{
        width:calc(100% - 120px);
        height: 160px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        border-bottom: 1px solid gray;
    .hat{
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: flex-start;
        margin: 10px;
        margin-left: 20px;
        .btnPlay{
            display: flex;
            justify-content: center;
            align-items: center;
            width: 20px;
            height: 20px;
            border: 2px solid #d76289;;
            border-radius: 20px;
            img{
                width: 7px;
                height: 10px;
            }
        }
    }
    .proc{
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin-left: 20px;
        span{
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 10px;
            img{
            width: 28px;
                height: 28px;
            }
        }
    }
    .btn{
        button{
        width: 160px;
        height: 30px;
        }
    }
}
</style>