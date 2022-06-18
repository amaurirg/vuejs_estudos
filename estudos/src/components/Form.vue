<template>
  <form action="">
    <!-- <InputText /> -->
    <Autocomplete />
  </form>
</template>

<script>
import InputText from "./InputText.vue";
import Autocomplete from "./Autocomplete.vue";
export default {
  name: "Form",
  components: { InputText, Autocomplete },
};
</script>
