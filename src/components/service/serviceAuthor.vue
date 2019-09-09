<template>
    <div class="organization">
        <div class="organization-about">
            <div class="organization-about-h">Об организаторе:</div>
            <div class="organization-about-text">
                Всем привет! Я фотограф Мария! И по мимо фотосъемки я так же являюсь членом группы экспертов туристической отрасли, 
                которые хорошо разбираются в маркетинге, операциях и услугах обслуживания клиентов, 
                специализирующихся на совместном использовании и частных турах. 
                <br>
                <br>
                Сначала мы (я и моя команда) изучаем интересы клиентов, а затем придумываем подходящее решение, которое соответствует бюджету и планам клиента. 
                Мы никогда не зависим от субпоставщиков и не свяжемся… 
            </div>
            <div class="organization-about-more">Читать еще</div>
        </div>
        <div class="organization-deal">
            <div class="organization-deal-h">Что я предоставлю:</div>
            <div class="organization-deal-text">Встречу вас на машине после длительного перелёта. 
                Качественный подбор места и локации для вашей съемки. 
                При необходимости всегда возможно прерваться на обед/ужин.
                Более 50 фотографий на выходе с обработкой и замечательные впечатления о Дубае !</div>
            <div class="organization-deal-more">Читать еще</div>
        </div>
        <div class="organization-author">
            <div class="organization-author-photo"></div>
            <div class="organization-author-heart"></div>
            <div class="organization-author-name">Марина Иванова</div>
            <div class="organization-author-profession">Фотограф</div>
            <div class="organization-author-more">Показать больше <br>  информации о фотографе</div>
        </div>
        <div class="organization-line"></div>
    </div>
</template>

<script>
export default {
    name: 'serviceAuthor'
}
</script>

<style lang="scss" scoped>

.organization{
    position: absolute;
    top: 1170px;
    left: 392px;

    &-about{
        position: absolute;

        &-h{
            position: absolute;
            width: 173px;
            height: 24px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: 500;
            font-size: 18px;
            line-height: 26px;

            color: #37373F;
        }

        &-text{
            position: absolute;
            width: 584px;
            height: 242px;
            top: 38px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: normal;
            font-size: 16px;
            line-height: 24px;

            color: #37373F;
        }

        &-more{
            position: absolute;
            width: 126px;
            height: 19px;
            top: 285px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: 500;
            font-size: 16px;
            line-height: 23px;

            color: #5286EC;
        }

        &-more:after{
            content: '';
            position: absolute;
            width: 11px;
            height: 6px;
            top: 10px;
            left: 105px;

            background: url('../../assets/photoGallery/Arrow.png') no-repeat;
        }
    }

    &-deal{
        position: absolute;
        top: 344px; 

        &-h{
            position: absolute;
            width: 254px;
            height: 24px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: 500;
            font-size: 18px;
            line-height: 26px;

            color: #37373F;
        }

        &-text{
            position: absolute;
            width: 584px;
            height: 118px;
            top: 38px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: normal;
            font-size: 16px;
            line-height: 24px;

            color: #37373F;
        }

        &-more{
            position: absolute;
            width: 126px;
            height: 19px;
            top: 156px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: 500;
            font-size: 16px;
            line-height: 23px;

            color: #5286EC;
        }

        &-more:after{
            content: '';
            position: absolute;
            width: 11px;
            height: 6px;
            top: 10px;
            left: 105px;

            background: url('../../assets/photoGallery/Arrow.png') no-repeat;
        }
    }

    &-author{
        position: absolute;
        left: 700px;

        &-photo{
            position: absolute;
            width: 139px;
            height: 139px;
            top: 43px; 
            left: 110px;

            background: url('../../assets/author/authorFace.jpeg') no-repeat;
            background-size: cover;
            background-position: center;
            border-radius: 50%;
        }

        &-heart{
            position: absolute;
            width: 31px;
            height: 27px;
            top: 30px;
            left: 296px;

            background: url('../../assets/author/Vectorheart.png') no-repeat;
            background-size: contain;
        }

        &-name{
            position: absolute;
            width: 163px;
            height: 22px;
            top: 205px;
            left: 98px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: 500;
            font-size: 18px;
            line-height: 22px;

            color: #37373F;
        }

        &-profession{
            position: absolute;
            width: 290px;
            height: 18px;
            left: 35px;
            top: 234px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: normal;
            font-size: 14px;
            line-height: 21px;
            text-align: center;

            color: #37373F;
        }

        &-more{
            position: absolute;
            width: 290px;
            height: 43px;
            left: 35px;
            top: 263px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: 500;
            font-size: 14px;
            line-height: 21px;
            text-align: center;

            color: #5286EC;
        }
    }

    &-line{
        position: absolute;
        width: 1139px;
        height: 0px;
        top: 580px;

        border: 0.5px solid #C7C7C7;
    }
}

</style>