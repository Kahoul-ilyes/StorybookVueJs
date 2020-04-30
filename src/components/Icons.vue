<template>
    <img :style="ComponentStyles" :src="iconUrl"/>
</template>

<script>
  export default {
    props: {
      iconUrl: String,
    },

    data() {
      return {
        ComponentStyles: {
        },
      };
    },

  };
</script>
