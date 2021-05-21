<template>
  <div class="align-items-center d-flex justify-content-center vh-100" style="">
    <div>
      <div class="flex-center">
        <div class="text-center">
          <h2>This Navbar is our hero section!</h2>
          <br>
          <h5>Vue is not easy.</h5>
          <p>While with John, it's possible to learn!!!</p>
          <br>
          <p>Wooohooo! John is here!</p>
          <button v-on:click='click' class="btn btn-danger">Call John!</button>

        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: "Hero",
    methods: {
        click(){
            console.log('Button in hero section clicked!');
        }
    }
}


</script>

<style>

</style>