<template>
  <h1>{{ title }}</h1>
  <p>{{ description }}</p>
  <legend>A partir de {{ price }}€ par mois</legend>
  <button>S'ABONNER</button>
  <a href="/about">En savoir plus</a>
</template>

<script>
export default {
  props: ["title", "description", "price"],

  name: "MainJumbotron",
};
</script>

<style>
main {
  flex-grow: 1;
  display: flex;
  align-items: center;
  justify-content: space-around;
}

.jumbotron {
  padding: 16px 32px;
  color: white;
  background-color: blue;
  width: 150px;
  height: 300px;
  text-align: center;
}
</style>
