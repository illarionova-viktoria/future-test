<template>
    <div class="comments">
        <div class="comments-h">Отзывы:</div>
        <div class="comments-blocks">
            <div class="comments-blocks-block comments-blocks-block__1">
                <div class="comments-blocks-block-icon comments-blocks-block__1-icon"></div>
                <div class="comments-blocks-block-name comments-blocks-block__1-name">Валерия Антонова</div>
                <div class="comments-blocks-block-prof comments-blocks-block__1-prof">Арт-директор</div>
                <div class="comments-blocks-block-stars comments-blocks-block__1-stars">
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star1"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star2"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star3"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star4"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star5"></div>
                </div>
                <div class="comments-blocks-block-answer comments-blocks-block__1-answer">Супер! Я бы заказала съемку снова!</div>
                <div class="comments-blocks-block-text comments-blocks-block__1-text">Хотим выразить огромную благодарность вашей компании! 
                    Получили море ощущений, все прошло просто замечательно. 
                    Фотки получились великолепные, отдельное спасибо фотографу!
                    <div class="comments-blocks-block-text-date comments-blocks-block__1-date">27 Апреля, 2019г.</div>
                    <div class="comments-blocks-block-text-line comments-blocks-block__1-line"></div>
                </div>
                
            </div>
            <div class="comments-blocks-block comments-blocks-block__2">
                <div class="comments-blocks-block-icon comments-blocks-block__2-icon"></div>
                <div class="comments-blocks-block-name comments-blocks-block__2-name">Виталий Петров</div>
                <div class="comments-blocks-block-prof comments-blocks-block__2-prof">Фотограф</div>
                <div class="comments-blocks-block-stars comments-blocks-block__2-stars">
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star1"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star2"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star3"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star4"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star5"></div>
                </div>
                <div class="comments-blocks-block-answer comments-blocks-block__2-answer">Супер! Я бы заказал съемку снова!</div>
                <div class="comments-blocks-block-text comments-blocks-block__2-text">Восторг! :) Очень понравилось :) 
                    Захватили последний теплый, солнечный октябрьский день :) 
                    Впечатлило всё: сам вертолет, взлет, полёт, приземление. Организация полёта отличная. Спасибо!
                    <div class="comments-blocks-block-text-date comments-blocks-block__2-date">19 Апреля, 2019г.</div>
                    <div class="comments-blocks-block-line-line comments-blocks-block__2-line"></div>
                </div>
                
            </div>
            <div class="comments-blocks-block comments-blocks-block__3">
                <div class="comments-blocks-block-icon comments-blocks-block__3-icon"></div>
                <div class="comments-blocks-block-name comments-blocks-block__3-name">Джим Керри</div>
                <div class="comments-blocks-block-prof comments-blocks-block__3-prof"></div>
                <div class="comments-blocks-block-stars comments-blocks-block__3-stars">
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star1"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star2"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star3"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star4"></div>
                    <div class="comments-blocks-block-stars-star comments-blocks-block-stars-star__star5"></div>
                </div>
                <div class="comments-blocks-block-answer comments-blocks-block__3-answer">Супер! Я бы заказал съемку снова!</div>
                <div class="comments-blocks-block-text comments-blocks-block__3-text">Круто-круто-круто!!! Отмечали мой ДэРэ. 
                    Отлично провели время!!! Кстати закуски были вкусными и сытными))Мы с собой ничего не брали. 
                    Сами много фоткались,поэтому воспоминания обалденные!!!)) 
                    А еще нам всем напечатали по сертификату воздухоплавателя, правда некоторые ленятся за ним съездить))) 
                    Но все равно приятно. Короче, Презентстар – проверено. Оценка: пять!
                    <div class="comments-blocks-block-text-date comments-blocks-block__3-date">11 Апреля, 2019г.</div>
                    <div class="comments-blocks-block-text-line comments-blocks-block__3-line"></div>
                </div>  
            </div>
        </div>
        <div class="comments-more">Показать Все (134)</div>
    </div>
</template>

<script>
export default {
    name: 'LandingComments'
}
</script>

<style lang="scss" scoped>

.comments{
    position: absolute;
    top: 4001px;
    left: 392px; 

    &-h{
        position: absolute;
        width: 121px;
        height: 24px;

        font-family: Montserrat;
        font-style: normal;
        font-weight: 500;
        font-size: 20px;
        line-height: 29px;

        color: #37373F;
    }

    &-blocks{
        position: absolute;
        top: 74px;

        &-block{

            position: absolute;

            &-icon{
                position: absolute;
                width: 101px;
                height: 101px;

                
                
                border-radius: 50%;
            }

            &-name{
                position: absolute;
                width: 179px;
                height: 22px;
                left: 121px;
                top: 10px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: 500;
                font-size: 18px;
                line-height: 22px;

                color: #37373F;
            }

            &-prof{
                position: absolute;
                width: 128px;
                height: 22px;
                left: 121px;
                top: 42px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 21px;

                color: #37373F;
            }

            &-stars{
                position: absolute;
                width: 118px;
                height: 17px;
                left: 121px;
                top: 74px;

                    &-star{
                    position: absolute;
                    width: 18px;
                    height: 17px;


                    background: url('../assets/smallStar.png') no-repeat;

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

            &-answer{
                position: absolute;
                width: 285px;
                height: 22px;
                left: 308px;
                top: 74px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 21px;

                color: #B3B3B3;
            }

            &-answer:before{
                content: '';
                position: absolute;
                width: 15px;
                height: 11.5px;
                top: 2px;
                left: -20px;

                background: url('../assets/done.png') no-repeat;
                background-size: contain;
            }

            &-text{
                position: absolute;
                width: 510px;
                height: 88px;
                left: 121px;
                top: 116px;

                font-family: Montserrat;
                font-style: normal;
                font-weight: normal;
                font-size: 16px;
                line-height: 24px;

                color: #37373F;

                &-date{

                    width: 534px;
                    height: 15px;
                    margin-top: 14px;

                    font-family: Montserrat;
                    font-style: normal;
                    font-weight: normal;
                    font-size: 14px;
                    line-height: 21px;

                    color: #B3B3B3;
                }

                &-line{
                    width: 510px;
                    height: 0px;
                    margin-top: 24px;

                    border: 0.5px solid #C7C7C7;
                }

            }

            &__1{
                
                &-icon{
                    background:url('../assets/commentAvatar/va.png') no-repeat;
                    background-size: cover;
                    background-position: center;
                }
            }

            &__2{
                top: 307px;

                &-icon{
                    background: url('../assets/commentAvatar/vp.png') no-repeat;
                    background-size: cover;
                    background-position: center;
                }

            }

            &__3{
                top: 614px;

                &-icon{
                    background: url('../assets/commentAvatar/dc.jpeg') no-repeat;
                    background-size: cover;
                    background-position: center;
                }
            }


            
        }

    }

    &-more{
        position: absolute;
        width: 165px;
        height: 19px;
        left: 490px;
        top: 1071px;

        font-family: Montserrat;
        font-style: normal;
        font-weight: 500;
        font-size: 17px;
        line-height: 25px;

        color: #5286EC;
    }

    &-more:before{
        content: '';
        position: absolute;
        width: 11px;
        height: 6px;
        top: 12px;
        left: -21px; 

        background: url('../assets/photoGallery/Arrow.png');
    }

    &-more:after{
        content: '';
        position: absolute;
        width: 11px;
        height: 6px;
        top: 12px;
        left: 176px; 

        background: url('../assets/photoGallery/Arrow.png');
    }
}
</style>