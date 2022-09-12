<template>
  <img :src="avatar" :alt="descricao" />
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Picture",
  data() {
    return {
      avatar:
        "https://i.kym-cdn.com/photos/images/original/000/916/872/942.jpg",
      descricao: "The true avatar",
    };
  },
};
</script>
