<template>
  <div>
    <H1>Hola : {{status }}</H1>
  </div>
</template>
<script>
export default {
  name: "Hola",
  data() {
    return {
      status: "Mal"
    };
  }
};
</script>