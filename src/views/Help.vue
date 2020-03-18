<template>
<div class = "helpText">
  <h2>We Can't Do This Alone</h2>
  <img src="images/sadmonkey.jpg">
  <p class="para">Helping all of these animals is expensive. With extra donations or volunteers, we can
  expand our animal sanctuaries around the world and ensure that these animals will remain
  safe well into the future. If you are interested in volunteering or donating, please don't
  hestitate to call us at (111-111-1111) or e-mail us at conservationworldwide@email.com.</p>
</div>
</template>

<script>
export default {
  name: 'Animals',
  components: {
  },
  data() {
    return {
    }
  },
}
</script>

<style scoped>
h2
{
  margin-top: 1%;
  margin-bottom: 0.7%;
}

img
{
  height: 300px;
  width: 230px;
  margin-bottom: 1.2%;
}

.para {
  margin: auto;
  align-items: center;
  box-sizing: border-box;
  font-size: 1.3em;
  margin-bottom: 2%;
  width: 60%;
}
</style>
