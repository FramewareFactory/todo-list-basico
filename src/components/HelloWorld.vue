<template>
  <div class="container">
    <div class="mb-3 contenedor-form">
      <label for="exampleFormControlInput1" class="form-label"
        >Email address
        <input
          type="email"
          class="form-control"
          id="exampleFormControlInput1"
          placeholder="name@example.com"
        />
      </label>
    </div>
    <div class="mb-3 contenedor-form-2">
      <label for="exampleFormControlTextarea1" class="form-label"
        >Example textarea
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
      </label>
    </div>
    <div class="mb-3 contenedor-form-3">
      <label for="exampleFormControlTextarea1" class="form-label"
        >Example textarea 4
        <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
      </label>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
