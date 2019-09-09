<template>
    <div class="footer">
        <div class="footer-logo"></div>
        <div class="footer-social">
            <div class="footer-social-vk"></div>
            <div class="footer-social-fb"></div>
            <div class="footer-social-inst"></div>
            <div class="footer-social-lang">RU</div>
        </div>
        <div class="footer-info">
            <div class="footer-info-payment">
                <div class="footer-info-payment-mastercard"></div>
                <div class="footer-info-payment-visa"></div>
            </div>
            <div class="footer-info-support">Тех. поддержка: <a href="#">8(800)700-00-00</a></div>
            <div class="footer-info-company">© 2018 HELYFLY. All Rights Reserved.</div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'LandingFooter'
}
</script>

<style lang="scss" scoped>
.footer{
    position: absolute;
    width: 1920px;
    height: 177px;
    top: 5119px;

    background: #FFFFFF;

    &-logo{
        position: absolute;
        width: 129px;
        height: 23px;
        left: 462px;
        top: 51px;

        background: url('../assets/Vector.png') no-repeat;
    }

    &-social{
        position: absolute;
        width: 137px;
        height: 25px;
        top: 45.5px;
        left: 1261px;

        &-vk{
            position: absolute;
            width: 26px;
            height: 15px;
            top: 5.5px;

            background: url('../assets/socialButton/vk.png') no-repeat;
            background-size: contain;
        }

        &-fb{
            position: absolute;
            width: 50px;
            height: 25.49px;
            left: 45px;

            background: url('../assets/socialButton/Facebook.png') no-repeat;
            background-size: contain;
        }

        &-inst{
            position: absolute;
            width: 25.49px;
            height: 25.5px;
            left: 100px;

            background: url('../assets/socialButton/Instragram.png');
        }

        &-lang{
            position: absolute;
            width: 23px;
            height: 19px;
            left: 155px;
            top: 5.5px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: normal;
            font-size: 15px;
            line-height: 18px;

            color: #37373F;
        }

        &-lang:before{
            content:'';
            position: absolute;
            width: 11px;
            height: 6px;
            left: 30px;
            top: 7px;


            background: url('../assets/photoGallery/Arrow.png');
        }
    }

    &-info{
        position: absolute;
        width: 1920px;
        height: 77px;
        top: 114px;

        background: #FAF9F8;

        &-payment{
            position: absolute;
            top: 11px;
            left:454px; 

            &-mastercard{
                position: absolute;
                width: 39px;
                height: 25px;

                background: url('../assets/socialButton/MC.png') no-repeat;
            }

            &-visa{
                position: absolute;
                width: 39px;
                height: 27px;
                left: 59px;

                background: url('../assets/socialButton/VISA.png') no-repeat;
            }
        }

        &-support{
            position: absolute;
            width: 240px;
            height: 18px;
            left: 837px;
            top: 3px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: normal;
            font-size: 14px;
            line-height: 17px;

            color: #B3B3B3;

            a{
                font-family: Montserrat;
                font-style: normal;
                font-weight: normal;
                font-size: 14px;
                line-height: 17px;
                text-decoration: none;

                color: #B3B3B3;
            }
        }

        &-company{
            position: absolute;
            width: 256px;
            height: 18px;
            left: 828px;
            top: 28px;

            font-family: Montserrat;
            font-style: normal;
            font-weight: normal;
            font-size: 14px;
            line-height: 17px;

            color: #B3B3B3;
        }
    }
}
</style>