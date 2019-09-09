<template>
    <div class="promo">
        <div class="promo-text">
            Эксклюзивная <span>фотосессия</span> при полете на вертолете
        </div>
        <div class="promo-sale">
            <div class="promo-sale-text">Стоимость:</div>
            <div class="promo-sale-price">1500&#8381;</div>
            <div class="promo-sale-icon"></div>
        </div>
        <div class="promo-button">
            <div class="promo-button-text">Забронировать место</div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'LandingPromo'
}
</script>

<style lang="scss" scoped>

.promo {
    position: absolute;
    width: 1920px;
    height: 840px;
    top: 100px;

    background: url('../assets/helimain.png') no-repeat;
    background-size: cover;

    &-text{
        position: absolute;
        width: 887px;
        height: 89px;
        left: 392px;
        top: 286px;

        font-family: Montserrat ;
        font-style: normal;
        font-weight: bold;
        font-size: 40px;
        line-height: 49px;

        color: #FFFFFF;

        span{
            color: #FC9B09;
        }
    }

    &-sale{
        position: absolute;
        width: 230px;
        height: 100px;
        left: 392px;
        top: 404px;

        background: url('../assets/Rectangle 6.2.png') no-repeat;
        background-size: contain;
        

        &-text{
            position: absolute;
            width: 121px;
            height: 19px;
            left: 22px;
            top: 11px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: 100;
            font-size: 20px;
            line-height: 30px;

            color: #FFFFFF;
        }

        &-price{
            position: absolute;
            width: 113px;
            height: 36px;
            left: 23px;
            top: 30px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: 800;
            font-size: 35px;
            line-height: 53px;
            color: #FFFFFF;
        }

        &-icon:before{
            content: '%';
            position: absolute;
            width: 31px;
            height: 36px;
            top: 0;
            left: 10px;
            font-family: Montserrat;
            font-style: normal;
            font-weight: 700;
            font-size: 35px;
            line-height: 53px;

            color: #FFFFFF;
        }

        &-icon{
            position: absolute;
            width: 52px;
            height: 52px;
            left: 143px;
            top: 16px;

            border: 1px solid #FFFFFF;
            border-radius: 50%;
            box-sizing: border-box;
            box-shadow: 0px 4px 4px rgba(255, 255, 255, 0.25), 0px 4px 15px rgba(255, 255, 255, 0.25);
        }

    }

    &-button{
        position: absolute;
        width: 304px;
        height: 68px;
        left: 392px;
        top: 512px;

        border: 3px solid #FFFFFF;
        box-sizing: border-box;
        box-shadow: 0px 4px 4px rgba(255, 255, 255, 0.25), 0px 4px 70px rgba(255, 255, 255, 0.7);
        border-radius: 3px;

        &-text{
            position: absolute;
            width: 230px;
            height: 21px;
            left: 37px;
            top: 21px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: 900;
            font-size: 18px;
            line-height: 22px;
            text-align: center;

            color: #FFFFFF;
        }
    }
    
}

</style>