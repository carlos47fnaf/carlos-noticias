<script>
import MenuLateral from "@/components/MenuLateral.vue";
import ConstCabecalho from "@/components/ConstCabecalho.vue";
import ConstRodape from "@/components/ConstRodape.vue";
import ConstMain from "@/components/ConstMain.vue";

export default {
  components: { MenuLateral, ConstCabecalho, ConstRodape, ConstMain },
};
</script>
<template>
  <MenuLateral />
  <ConstCabecalho />
  <ConstMain />
  <ConstRodape />
</template>
<style></style>
