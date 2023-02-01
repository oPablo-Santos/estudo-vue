<template>
  <img :src="projeto" :alt="descricao" />
</template>
<script>
export default {
  name: "Picture",
  data() {
    return {
      projeto: "/img/qr-code-finalizado.png",
      descricao: "Projeto qr-code",
    };
  },
};
</script>
