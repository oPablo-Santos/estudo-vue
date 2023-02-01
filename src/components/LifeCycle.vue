!
<template>
  <h1>meu nome é: {{ nome }}</h1>
</template>
<script>
export default {
  name: "LifeCycle",
  data() {
    return {
      nome: "ainda não sei",
    };
  },
  created() {
    setTimeout(() => {
      this.nome = "Jorginho gameplay";
    }, 2000);
  },
  mounted() {
    setTimeout(() => {
      this.nome = "Serjão gameplay";
    }, 5000);
  },
};
</script>
