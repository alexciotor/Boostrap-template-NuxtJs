<template>
<section>
  <div class="container bg-info">
    <h1>standard heading</h1>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Repudiandae, dolorem!</p>
    <div class="row">

    <button class=" col-6 bg-primary text-light p-2 font-weight-bold">primary button</button>
    <button class=" col-6 bg-danger text-light p-2 font-weight-bold" > danger button</button>
    </div>
  </div>
<div class="container-fluid bg-warning">
  <div class="row">
    <div class="col">
  <h1>Container Fluid</h1>
  <p class="lead px-5 text-success " >Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur iure, ullam sunt saepe excepturi enim iste corporis perferendis ducimus dolorem.
  </p>
  <button type="button" class=" btn bg-dark text-danger mt-5 ">
    btn dark
  </button>

   <button class="btn bg-danger text-light mb-5 ">
    btn danger
   </button>
   <button class=" btn bg-success text-primary disabled mt-5">
    btn success
  </button>
</div>

  </div>
</div>
<section class="bg-danger">
  <div class="container ">
  <h1>section example</h1>
  </div>
</section>
</section>


</template>

<script>
export default {
name: 'Elements,'
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>