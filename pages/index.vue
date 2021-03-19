<template>
<section  >
  <h1>Colors</h1>
  <div class="container">
 <h4 class="text-danger bg-light" >This is a color class</h4>
 <h4 class="text-primary bg-dark orange" >This is a color class</h4>
 <h4 class="text-info bg-secondary " >This is a color class</h4>
 <h4 class="text-success bg-warning " >This is a color class</h4>
 <h4 class="text-warning bg-success" >This is a color class</h4>
 <h4 class="text-secondary bg-info " >This is a color class</h4>
 <h4 class="text-dark bg-primary" >This is a color class</h4>
 <h4 class="text-light bg-danger " >This is a color class</h4>
 <h4 class="text-muted" >This is a color class</h4>
 </div>

 <h1>Typography</h1>
 <br><br><br> 
 <div class="container">
<h3>default font-size 16px</h3>
<h3>default line-height 1.5</h3>
<p>all elements have margin-top: 0 and margin bottom 1rem(16px)</p>
<br><br><br> 
<h1>hello i am 40 px</h1>
<h2>hello i am 32 px</h2>
<h3>hello i am 28 px </h3>
<h4>hello i am 24 px </h4>
<h5>hello i am 20 px </h5>
<h6>hello i am 16 px </h6>
<br><br><br>
<!-- adding a class of heading gives the element that size -->
<h1 class="h5">hello i am 40 px</h1>
<p class="h1" >hello i am 40 px</p>
<!-- Display classs -->
<h1 class="display-1">Display 1</h1>
<h1 class="display-2">Display 2</h1>
<h1 class="display-3">Display 3</h1>
<h1 class="display-4">Display 4</h1>
<p class="display-4" >Display class works with any element</p>
 <br><br><br>
<h4>normal text <small>small text</small></h4>
<p>small text <small>smaller text</small></p>
<p>I can highlight with <mark>marked text</mark></p>
<p>i can highlight with  <code>code element</code></p>
<p>i can highlight with  <kbd>kbd element</kbd></p>

 <br><br><br>
<h2>Font weights</h2>
 <p class="font-weight-bold"  >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates, sunt?</p>
 <p class="font-weight-light">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Earum, repudiandae.</p>
 <p class="font-italic">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Molestias, iste?</p>
 <p class="lead" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis, necessitatibus!</p>
 <p class="text-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est, eaque!</p>
  <p class="text-right">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est, eaque!</p>
   <p class="text-left">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est, eaque!</p>
   <p class="text-uppercase">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quia, veritatis.</p>
   <p class="text-capitalize">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, blanditiis.</p>
   <p class="text-lowercase">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad, distinctio.</p>
 </div>
 <h1>Containers</h1>
 
<div class="container bg-danger text-light">i am sa simple container
</div>
<div class="container-fluid bg-primary text-ligfht">i am a simple container fluid</div><br><br><br>
 <section id="skills" class="bg-warning" >
<div class="container bg-danger text-light">i am sa simple container
</div>
 </section>
  <section id="about" class="bg-warning" >
<div class="container-fluid bg-primary text-light">i am sa simple container
</div>
 </section>
<br><br><br><br>
<h1>Media queries</h1>
<!-- 12 -->
<div class="container bg-secondary text-white">
  <div class="row">
    <div class="col bg-danger">i am single column</div>
  </div>
</div>
<div class="container-fluid bg-secondary text-white">
  <div class="row">
    <div class="col bg-primary">i am single column</div>
      <div class="col bg-dark">i am second column</div>
  </div>
</div>
<div class="container  bg-secondary text-white">
  <div class="row">
    <div class="col bg-warning">i am single column</div>
      <div class="col bg-dark">i am second column</div>
         <div class="col bg-info">i am second column</div>
  </div>
</div>

<br><br><br>
<h1>Screen sizes</h1>
<div class="container  bg-secondary text-white">
  <div class="row">
    <div class="col-sm bg-warning">i am single column</div>
      <div class="col-sm bg-dark">i am second column</div>
         <div class="col-sm bg-info">i am second column</div>
  </div>
</div>
 </section> 
</template>

<script>
export default {
  
  head(){
    return{
      title:'Boostrap '
    }
  }
}
</script>

<style>
body{
  text-transform: capitalize;
}
/* add different styles to an element by adding a class  */
 .orange{
    font-size: 3rem;
 }
 
</style>
