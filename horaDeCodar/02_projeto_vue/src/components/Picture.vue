<template>
  <img :src="avatar" :alt="descricao" />
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Picture",
  data() {
    return {
      avatar: "02_projeto_vue/img/avatar.png",
      descricao: "The true avatar",
    };
  },
};
</script>
