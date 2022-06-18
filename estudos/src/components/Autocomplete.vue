<template>
  <label for="nome">Nome</label>
  <input type="text" name="nome" v-model="input_name" />
  <p>input_name: {{ input_name }}</p>
  <button type="submit" v-if="input_name">Enviar</button>
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