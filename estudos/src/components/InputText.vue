<template>
  <label for="nome">Nome</label>
  <input type="text" name="nome" v-model="input_name" />
  <p>input_name: {{ input_name }}</p>
</template>

<script>
export default {
  name: "InputText",
  data() {
    return {
      input_name: "",
    };
  },
};
</script>