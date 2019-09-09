<template>
    
        <div class="service-description">
            <div class="service-description-h">Фотосессия в вертолете</div>
            <div class="service-description-about">Полет на вертолете это прекрасная возможность получить новые ощущения! А наш замечательный фотограф запечатлит лучшие моменты</div>
            <div class="service-description-pluses">
                <div class="service-description-pluses-time">
                    <div class="service-description-pluses-time-text" >3 часа съемки</div>
                </div>
                <div class="service-description-pluses-photo">
                    <div class="service-description-pluses-photo-text" >Более 50 фотографий</div>
                </div>
                <div class="service-description-pluses-location">
                    <div class="service-description-pluses-location-text" >Москва</div>
                </div>
                <div class="service-description-pluses-chat">
                    <div class="service-description-pluses-chat-text" >Готовы ответить на любые вопросы</div>
                </div>
            </div>
            <div class="service-description-line1"></div>
            <div class="service-description-rating">
                <div class="service-description-rating-text">Более <span>50</span> отзывов с оценкой</div>
                <div class="service-description-rating-stars">
                    <div class="service-description-rating-stars-star service-description-rating-stars-star__star1"></div>
                    <div class="service-description-rating-stars-star service-description-rating-stars-star__star2"></div>
                    <div class="service-description-rating-stars-star service-description-rating-stars-star__star3"></div>
                    <div class="service-description-rating-stars-star service-description-rating-stars-star__star4"></div>
                    <div class="service-description-rating-stars-star service-description-rating-stars-star__star5"></div>
                </div>
            </div>
            <div class="service-description-line2"></div>
        </div>

</template>

<script>
export default {
    name: 'serviceDescription'
}
</script>

<style lang="scss" scoped>

.service-description{
    position: absolute;
    top: 70px;
    left: 392px; 

    &-h{
        position: absolute;
        width: 460px;
        height: 90px;
        left: 0;
        top: 0;

        font-family: Montserrat;
        font-style: normal;
        font-weight: 500;
        font-size: 40px;
        line-height: 49px;

        color: #37373F;
    }

    &-about{
        position: absolute;
        width: 549px;
        height: 73px;
        top: 108px;

        font-family: Montserrat;
        font-style: normal;
        font-weight: normal;
        font-size: 18px;
        line-height: 26px;

        color: #37373F;
    }

    &-pluses{
        position: absolute;
        top: 202px;

        &-time{
            position: absolute;
            width: 40px;
            height: 37px;

            background: url('../../assets/time.png') no-repeat;

            &-text{
                position: absolute;
                width: 186px;
                height: 20px;
                top: 8px;
                left: 48px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: 500;
                font-size: 14px;
                line-height: 20px;

                color: #37373F;
            }
        }

        

        &-photo{
            position: absolute;
            width: 35px;
            height: 28px;
            top: 53px;

            background: url('../../assets/photo.png') no-repeat;
            
            &-text{
                position: absolute;
                width: 186px;
                height: 20px;
                top: 8px;
                left: 43px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: 500;
                font-size: 14px;
                line-height: 20px;

                color: #37373F;
            }
        }
        

        &-location{
            position: absolute;
            width: 33px;
            height: 33px;
            top: 97px;

            background: url('../../assets/location.png') no-repeat;

            &-text{
                position: absolute;
                width: 230px;
                height: 20px;
                left: 43px;
                top: 10px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: 500;
                font-size: 14px;
                line-height: 20px;

                color: #37373F;
            }
        }

        &-chat{
            position: absolute;
            width: 31px;
            height: 31px;
            top: 145px;

            background: url('../../assets/speech-bubble.png') no-repeat;

            &-text{
                position: absolute;
                width: 270px;
                height: 20px;
                left: 43px;
                top: 5px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: 500;
                font-size: 14px;
                line-height: 20px;

                color: #37373F;
            }
        }
    }

    &-line1{
        position: absolute;
        width: 569px;
        height: 0px;
        left: 0;
        top: 413px;

        border: 0.5px solid #C7C7C7;
    }

    &-rating{
        position: absolute;
        width: 32px;
        height: 36px;
        top: 433px;

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

    &-line2{
        position: absolute;
        width: 569px;
        height: 0px;
        left: 0;
        top: 500px;

        border: 0.5px solid #C7C7C7;
    }

}

</style>