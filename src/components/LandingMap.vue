<template>
    <div class="map">
        <div class="map-yandex"></div>
        <div class="map-window">
            <div class="map-window-block map-window-block__1">
                <div class="map-window-block-icon"><span>1</span></div>
                <div class="map-window-block-h">Где встречаемся?</div>
                <div class="map-window-block-text">Москва</div>
            </div>
            <div class="map-window-block map-window-block__2">
                <div class="map-window-block-icon"><span>2</span></div>
                <div class="map-window-block-h">Время съемки</div>
                <div class="map-window-block-text">3 часа</div>
            </div>
            <div class="map-window-block map-window-block__3">
                <div class="map-window-block-icon"><span>3</span></div>
                <div class="map-window-block-h">Мест осталось:</div>
                <div class="map-window-block-text">2 места</div>
            </div>
            <div class="map-window-block map-window-block__4">
                <div class="map-window-block-icon map-window-block__4-icon"></div>
                <div class="map-window-block-h map-window-block__4-h">Мария Иванова</div>
                <div class="map-window-block-text map-window-block__4-text">Фотограф</div>
                <div class="map-window-block-more map-window-block__4-more">Показать больше информации</div>
            </div>
        </div>
        <div class="map-baloon">
            <div class="map-baloon-text"></div>
            <div class="map-baloon-close"></div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'LandingMap'
}
</script>

<style lang="scss" scoped>

.map{
    position: absolute;
    left: 0px;
    top: 3361px;

    &-yandex {
        position: absolute;
        width: 1916px;
        height: 509px;
    
        background: url('../assets/mapScreen.png') no-repeat;
    }

    &-window{
        position: absolute;
        width: 420px;
        height: 469px;
        left: 392px;
        top: 20px;

        background: #FFFFFF;
        border: 1px solid #C7C7C7;
        box-sizing: border-box;

        &-block{
            position: absolute;
            left: 30px;
            top: 34px;

            &-icon{
                position: absolute;
                width: 61px;
                height: 61px;

                background: url('../assets/Ellipse 2.png') no-repeat;

                span{
                    position: absolute;
                    width: 27px;
                    height: 42px;
                    left: 17px;
                    top: 5px;

                    font-family: Montserrat;
                    font-style: normal;
                    font-weight: bold;
                    font-size: 35px;
                    line-height: 51px;
                    text-align: center;

                    color: #FFFFFF;
                    z-index: 100;
                }
            }

            &-h{
                position: absolute;
                width: 170px;
                height: 21px;
                left: 79px;
                top: 7px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: 500;
                font-size: 18px;
                line-height: 27px;

                color: #37373F;
            }

            &-text{
                position: absolute;
                width: 116px;
                height: 21px;
                left: 79px;
                top: 40px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: normal;
                font-size: 18px;
                line-height: 26px;

                color: #37373F;
            }
        }

        &-block{
            &__1{
                    position: absolute;
                    top: 51px;
            }

            &__2{
                    position: absolute;
                    top: 146px;
            }

           &__3{
                position: absolute;
                top: 241px;
            }

           &__4{
                position: absolute;
                top: 344px;

            &-icon{
                position: absolute;
                width: 67px;
                height: 67px;

                background: url('../assets/author/authorFace.jpeg') no-repeat;
                background-size: cover;
                background-position: center;
                border-radius: 50%;
            }

                &-h{
                    position: absolute;
                    width: 151px;
                    height: 22px;
                    top: 0px;
                }

                &-text{
                    position: absolute;
                    width: 85px;
                    height: 17px;
                    top: 27px;

                    font-family: Montserrat;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 16px;
                    line-height: 24px;

                    color: #37373F;
                }

                &-more{
                    position: absolute;
                    width: 279px;
                    height: 22px;
                    top: 49px;
                    left: 79px;

                    font-family: Montserrat;
                    font-style: normal;
                    font-weight: 500;
                    font-size: 14px;
                    line-height: 21px;

                    color: #5286EC;
                }

            }
        }

    }
}

</style>