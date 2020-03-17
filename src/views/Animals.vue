<template>
<div>
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
