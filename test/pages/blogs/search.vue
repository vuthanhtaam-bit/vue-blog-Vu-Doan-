<template>
    <blog-list :isVisible="isVisible"></blog-list>
</template>

<script>
import BlogList from '~/components/BlogList/BlogList.vue';

export default {
  data:function (){ 
    return {
        isVisible:true,
    }
  },

  components: { BlogList },
};
</script>