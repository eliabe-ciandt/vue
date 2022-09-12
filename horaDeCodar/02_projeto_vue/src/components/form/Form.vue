<template>
  <form action="">
    <div>
      <InputText />
    </div>
    <div>
      <InputText />
    </div>
    <div>
      <Submit />
    </div>
  </form>
</template>

<script>
import InputText from "./InputText.vue";
import Submit from "./Submit.vue";

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Form",
  components: {
    // eslint-disable-next-line vue/no-unused-components
    InputText,
    // eslint-disable-next-line vue/no-unused-components
    Submit,
  },
};
</script>
