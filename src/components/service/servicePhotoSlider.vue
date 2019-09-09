<template>
    <div class="photo-gallery">
        <div class="photo-gallery-h">Фотографии пакета:</div>
        <div class="photo-gallery-smalls">
            <div class="photo-gallery-smalls-photo photo-gallery-smalls-photo__1"></div>
            <div class="photo-gallery-smalls-photo photo-gallery-smalls-photo__2"></div>
            <div class="photo-gallery-smalls-photo photo-gallery-smalls-photo__3"></div>
            <div class="photo-gallery-smalls-photo photo-gallery-smalls-photo__4"></div>
            <div class="photo-gallery-smalls-photo photo-gallery-smalls-photo__5"></div>
            <div class="photo-gallery-smalls-photo photo-gallery-smalls-photo__6"></div>
            <div class="photo-gallery-smalls-photo photo-gallery-smalls-photo__7"></div>
            <div class="photo-gallery-smalls-photo photo-gallery-smalls-photo__8"></div>
        </div>
        <div class="photo-gallery-others">
            <a class="photo-gallery-smalls-others-text">Показать все фото</a>
        </div>
        <div class="photo-gallery-big">
            <div class="photo-gallery-big-photo"></div>
            <div class="photo-gallery-big-button"></div>
        </div>
        <div class="photo-gallery-line"></div>
    </div>
</template>

<script>
export default {
    name: 'servicePhotoSlider'
}
</script>

<style lang="scss" scoped>

.photo-gallery {
    position: absolute;
    left: 392px;
    top: 600px;

    &-h{
        position: absolute;
        width: 219px;
        height: 24px;

        font-family: Montserrat;
        font-style: normal;
        font-weight: 500;
        font-size: 20px;
        line-height: 29px;

        color: #37373F;
    } 

    &-smalls{

        position: absolute;
        top: 61px;
        border-radius: 4px;

        &-photo{
            position: absolute;
            width: 277px;
            height: 185px;

            &__1{
                background: url('../../assets/photoGallery/face.png') no-repeat;
            }

            &__2{
                position: absolute;
                background: url('../../assets/photoGallery/view.png') no-repeat;
                left: 287px;
            }

            &__3{
                position: absolute;
                background: url('../../assets/photoGallery/kiss.png') no-repeat;
                background-size: contain;
                left: 574px;
            }

            &__4{
                position: absolute;
                background: url('../../assets/photoGallery/helicopter.png') no-repeat;
                left: 861px;
            }

            &__5{
                position: absolute;
                background: url('../../assets/photoGallery/kiss.png') no-repeat;
                background-size: contain;
                top: 196px;
                left: 0px;
            }

            &__6{
                position: absolute;
                background: url('../../assets/photoGallery/helicopter.png') no-repeat;
                top: 196px;
                left: 287px;
            }

            &__7{
                position: absolute;
                background: url('../../assets/photoGallery/view.png') no-repeat;
                top: 196px;
                left: 574px;
            }

            &__8{
                position: absolute;
                background: url('../../assets/photoGallery/view.png') no-repeat;
                top: 196px;
                left: 861px;
            }
        }

    }

    &-others{
        position: absolute;
        width: 166px;
        height: 19px;
        top: 472px;
        left: 479px;

        font-family: Montserrat;
        font-style: normal;
        font-weight: 500;
        font-size: 17px;
        line-height: 25px;

        color: #5286EC;
    }

    &-others:before{
        content: '';
        position: absolute;
        width: 11px;
        height: 6px;
        top: 12px;
        left: -21px; 

        background: url('../../assets/photoGallery/Arrow.png');
    }

    &-others:after{
        content: '';
        position: absolute;
        width: 11px;
        height: 6px;
        top: 12px;
        left: 176px; 

        background: url('../../assets/photoGallery/Arrow.png');
    }

    &-big{
        position: absolute;
        top: -540px;
        left: 588px;

        &-photo{
            position: absolute;
            width: 554px;
            height: 374px;
            

            background:url('../../assets/photoGallery/kiss.png') no-repeat;
            background-size: contain;
        }

        &-button{
            position: absolute;
            width: 16px;
            height: 23px;
            top: 322px;
            left: 497px;

            background:url('../../assets/play.png') no-repeat;
            background-size: contain;
        }

    }

    &-line{
        position: absolute;
        width: 1139px;
        height: 0px;
        top: 518px;

        border: 0.5px solid #C7C7C7;
    }

}
</style>