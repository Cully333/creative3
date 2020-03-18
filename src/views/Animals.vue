<template>
<div>
  <h2>This page lists all of the animals that we currently support at our various wildlife sanctuaries.</h2>
  <AnimalList :animals="animals" />
</div>
</template>

<script>
import AnimalList from "../components/AnimalList.vue"
export default {
  name: 'Animals',
  components: {
    AnimalList
  },
  data() {
    return {
    }
  },
  computed: {
    animals() {
      return this.$root.$data.animals;
    }
  },
}
</script>

<style scoped>
h2 {
  font-size: 1.6em;
  margin-top: 1%;
}
</style>
