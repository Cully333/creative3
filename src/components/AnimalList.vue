<template>
<div class="wrapper">
  <div class="animals">
    <div class="animal" v-for="animal in animals" :key="animal.id">
      <div class="info">
        <h1>{{animal.given_name}} the {{animal.animal_species}}</h1>
        <h2>Scientific name: {{animal.scientific_name}}</h2>
      </div>
      <div class="image">
        <img :src="'/images/animals/'+animal.image">
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'AnimalList',
  props: {
    animals: Array
  }
}
</script>

<style scoped>
.wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
}

.animals {
  margin-top: 20px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.animal {
  margin: 10px;
  margin-top: 50px;
  width: 200px;
}

.animal img {
  border: 2px solid #333;
  height: 250px;
  width: 200px;
  object-fit: cover;
}

.animal .image {
  display: flex;
  justify-content: center;
  margin-bottom: 5px;
}

.info {
  background: #F2921D;
  color: #000;
  padding: 10px 30px;
  height: 80px;
}

.info h1 {
  font-size: 16px;
}

.info h2 {
  font-size: 14px;
}

.info p {
  margin: 0px;
  font-size: 10px;
}

</style>
