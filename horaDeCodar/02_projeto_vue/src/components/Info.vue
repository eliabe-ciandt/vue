<template>
  <div>
    <p v-if="esta_trabalhando">Atualmente trabalho no KOBOSS</p>
    <p v-else>Tô no deserto</p>
    <p>Utilizo as seguintes tecnologias:</p>
    <ul>
      <li>JavaScript</li>
      <li>Node</li>
      <li>Vue</li>
      <li>Bots</li>
    </ul>
    <p v-show="mostrar_email">Mande um email para {{ email }}</p>
    <p v-show="!mostrar_email">Fala comigo não, por favor</p>
    <p>
      Para acessar meu portifólio, clique
      <a v-bind:href="meu_link">aqui</a>
    </p>
    <Picture />
  </div>
</template>

<script>
import Picture from "./Picture.vue";
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Info",
  data() {
    return {
      esta_trabalhando: true,
      mostrar_email: true,
      email: "eliabe@ci&t.com",
      meu_link: "https://github.com/eliabe-ciandt",
    };
  },
  components: { Picture },
};
</script>
