<template>
    <div class="service">
        <serviceDescription/>
        <servicePhotoSlider/>
        <serviceAuthor/>
        <serviceDay/>
    </div>
</template>

<script>
import serviceDescription from '../components/service/serviceDescription.vue';
import servicePhotoSlider from '../components/service/servicePhotoSlider.vue';
import serviceAuthor from '../components/service/serviceAuthor.vue';
import serviceDay from '../components/service/serviceDay.vue';

export default {
  name: 'LangingService',
  components:{
      serviceDescription,
      servicePhotoSlider,
      serviceAuthor,
      serviceDay
  }
}
</script>

<style lang="scss" scoped>

.service{
    position: absolute;
    width: 1916px;

    top: 940px;
}

</style>