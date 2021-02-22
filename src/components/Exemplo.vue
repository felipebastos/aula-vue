<template>
  <div>
    {{ mensagem }}

    <input type="text" v-model="mensagem" />
  </div>
</template>

<script>
export default {
    data: function(){
        return {
            mensagem: 'Olá, mundo!'
        }
    }
};
</script>

<style scoped>
div {
    border: 1px solid black;
}
</style>