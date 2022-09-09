<template>
  <div>
    <h2>Esta é uma descrição da pessoa {{ nome }}</h2>
    <Info />
    <p>Mas também sei</p>
    <ol>
      <li>Python</li>
      <li>Java</li>
      <li>Spring</li>
      <li>Bancos de dados SQL</li>
      <li>etc.</li>
    </ol>
  </div>
</template>

<script>
import Info from "./info.vue";
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Pessoa",
  components: {
    Info,
  },
  data() {
    return {
      nome: "que vos fala",
    };
  },
};
</script>
