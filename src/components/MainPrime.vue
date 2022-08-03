<template>
  <h3>Nos formules d'abonnement</h3>
  <main>
    <p>...</p>

    <div class="jumbotron">
      <MainJumbotron
        title="SOLO"
        :description="'1 ECRAN VIDEO HD'"
        :price="'9,99'"
      />
    </div>
    <div class="jumbotron">
      <MainJumbotron
        title="FAMILY"
        :description="'4 ECRANS VIDEO HD'"
        :price="'12,99'"
      />
    </div>
    <div class="jumbotron">
      <MainJumbotron
        title="FAMILY 4K"
        :description="'4 ECRANS VIDEO 4K'"
        :price="'15,99'"
      />
    </div>
  </main>
</template>

<script>
import MainJumbotron from "./Jumbotron.vue";

export default {
  name: "MainPrime",
  components: {
    MainJumbotron,
  },
};
</script>

<style>
main {
  flex-grow: 1;
}

.jumbotron {
  padding: 16px 32px;
  color: white;
  background-color: blue;
}
</style>
