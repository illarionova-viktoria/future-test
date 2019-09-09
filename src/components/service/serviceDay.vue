<template>
    <div class="avaliable-day">
        <div class="avaliable-day-h">Доступная съемка <br>в ближайшее время:</div>
        <div class="avaliable-day-box">
            <div class="avaliable-day-box-date">
                <div class="avaliable-day-box-date-day">Пятница,14 сентября</div>
                <div class="avaliable-day-box-date-icon"></div>
                <div class="avaliable-day-box-date-line"></div>
            </div>
            <div class="avaliable-day-box-time avaliable-day-box-time__1">
                <div class="avaliable-day-box-time-range">15:00 - 18:00</div>
                <div class="avaliable-day-box-time-price">1500₽</div>
                <div class="avaliable-day-box-time-avaliable">Осталось — 1 место</div>
                <div class="avaliable-day-box-time-button">Выбрать</div>
                <div class="avaliable-day-box-time-line"></div>
            </div>
            <div class="avaliable-day-box-time avaliable-day-box-time__2">
                <div class="avaliable-day-box-time-range">19:00 - 22:00</div>
                <div class="avaliable-day-box-time-price">1500₽</div>
                <div class="avaliable-day-box-time-avaliable">Осталось — 1 место</div>
                <div class="avaliable-day-box-time-button">Выбрать</div>
            </div>
            <div class="avaliable-day-box-rating">
                <div class="avaliable-day-box-rating-text">Более <span>50</span> отзывов с оценкой</div>
                <div class="avaliable-day-box-rating-stars">
                    <div class="avaliable-day-box-rating-stars-star avaliable-day-box-rating-stars-star__star1"></div>
                    <div class="avaliable-day-box-rating-stars-star avaliable-day-box-rating-stars-star__star2"></div>
                    <div class="avaliable-day-box-rating-stars-star avaliable-day-box-rating-stars-star__star3"></div>
                    <div class="avaliable-day-box-rating-stars-star avaliable-day-box-rating-stars-star__star4"></div>
                    <div class="avaliable-day-box-rating-stars-star avaliable-day-box-rating-stars-star__star5"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'serviceDay'
}
</script>

<style lang="scss" scoped>

.avaliable-day{
    position: absolute;
    top: 1800px;
    left: 392px;

    &-h{
        position: absolute;
        width: 288px;
        height: 51px;

        font-family: Montserrat;
        font-style: normal;
        font-weight: 500;
        font-size: 20px;
        line-height: 29px;

        color: #37373F;
    }

    &-box{
        position: absolute;
        width: 770px;
        height: 458px;
        top: 81px;

        border: 1px solid #C7C7C7;
        box-sizing: border-box;


        &-date{

            &-day{
                position: absolute;
                width: 205px;
                height: 24px;
                top: 30px;
                left: 30px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: normal;
                font-size: 18px;
                line-height: 26px;

                color: #37373F;
            }

            &-icon{
                position: absolute;
                width: 35px;
                height: 35px;
                top: 24px;
                left: 249px;

                border: 0.5px solid #C4C4C4;
                box-sizing: border-box;
                border-radius: 3px;
            }

            &-icon:before{
                content: '';
                position: absolute;
                width: 18px;
                height: 18px;
                top: 8px;
                left: 7px;

                background: url('../../assets/Calendar.png');
            }

            &-line{
                position: absolute;
                width: 768px;
                height: 0px;
                top: 74px;

                border: 0.5px solid #C7C7C7;
            }

        }

        &-time{

            &-range{
                position: absolute;
                width: 260px;
                height: 24px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: normal;
                font-size: 18px;
                line-height: 26px;

                color: #37373F;
            }

            &-price{
                position: absolute;
                width: 64px;
                height: 22px;
                top: 34px;


                font-family: Montserrat;
                font-style: normal;
                font-weight: 600;
                font-size: 18px;
                line-height: 22px;

                color: #37373F;
            }

            &-avaliable{
                position: absolute;
                width: 184px;
                height: 24px;
                top: 66px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: normal;
                font-size: 18px;
                line-height: 26px;

                color: #37373F;
            }

            &-button{
                position: absolute;
                width: 129px;
                height: 50px;
                top: 20px;
                left: 581px;

                border: 2px solid #FC9B09;
                box-sizing: border-box;
                border-radius: 3px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: 500;
                font-size: 14px;
                line-height: 50px;
                text-align: center;
                

                color: #FC9B09;
            }

            &-line{
                position: absolute;
                width: 768px;
                height: 0px;
                top: 110px;
                left: -30px;

                border: 0.5px solid #C7C7C7;
            }
        }

        &-time__1{
            position: absolute;
            left: 30px;
            top: 94px;
        }

        &-time__2{
            position: absolute;
            top: 224px;
            left: 30px;
        }

        &-rating{
            position: absolute;
            width: 32px;
            height: 36px;
            top: 374px;
            left: 30px;

            background: url('../../assets/Groupcup.png') no-repeat;

            &-text{
                position: absolute;
                width: 268px;
                height: 24px;
                left: 42px;
                top: 12px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: normal;
                font-size: 18px;
                line-height: 26px;

                color: #37373F;

                span{
                    font-weight: 600;
                }
            }

            &-stars{
                position: absolute;
                width: 118px;
                height: 17px;
                left: 324px;
                top: 14px;
                
                &-star{
                    position: absolute;
                    width: 18px;
                    height: 17px;
                    top: 0;

                    background: url('../../assets/smallStar.png') no-repeat;

                    &__star2{
                        left: 25px;
                    }

                    &__star3{
                        left: 50px;
                    }

                    &__star4{
                        left: 75px;
                    }

                    &__star5{
                        left: 100px;
                    }
                }
            }
        }
           
     }
}
</style>