<template>
  <h2>Counert</h2>
  <p>{{ this.counter }}</p>
  <button @click="sumar">Sumar + 1</button>
  <button @click="restar">Restar - 1</button>
  <button @click="reiniciar">Reiniciar</button>
</template>

<script>
export default {
  name: 'contador',
  data() {
    return {
      counter: 0,
    };
  },
  methods: {
    sumar() {
      this.counter += 1;
    },
    restar() {
      this.counter -= 1;
    },
    reiniciar() {
      this.counter = 0;
    },
  },
};
</script>

<style></style>
