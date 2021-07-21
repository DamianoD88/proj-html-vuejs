<template>
  <div class="main" >
    <div class="container mt-5">
      <h3 class="title fw-bold fs-1">
          Our Most Popular Dishes
      </h3>
      <div class="row row-cols-1 row-cols-md-3 g-1 mt-5 ms-5">
        
        <div class="col">

          <div class="card border-0">
            <img src="../assets/skin-on-fries-210x300.jpg" class="card-img-top " alt="...">
            <div class="card-body">
              <h5 class="card-title"><a class="subtitle fw-bold fs-4 text-decoration-none" href="#">Skin On Fries</a></h5>
              <p class="card-text"> $3.00 – $6.00 </p>
            </div>
          </div>

        </div>

        <div class="col">

          <div class="card border-0">
            <img src="../assets/choco-cookie-frappe-210x300.jpg" class="card-img-top " alt="...">
            <div class="card-body">
              <h5 class="card-title"><a class="subtitle fw-bold fs-4 text-decoration-none" href="#">Choco Cookie Frappe</a></h5>
              <p class="card-text"> $4.99 </p>
            </div>
          </div>

        </div>

        <div class="col">

          <div class="card border-0">
            <img src="../assets/donut-burger-210x300.jpg" class="card-img-top " alt="...">
            <div class="card-body">
              <h5 class="card-title"><a class="subtitle fw-bold fs-4 text-decoration-none" href="#">The Donut Burger</a></h5>
              <p class="card-text"> $6.99 </p>
            </div>
          </div>

        </div>

      </div>
      
      
    </div>
      
  </div>
</template>

<script>
export default {
name: 'Main',
}
</script>

<style lang="scss">

.main {
  margin-top: 100px;

  .title {
    letter-spacing: -3px;
    color: #000000;
  }

  .row {

    .card {
      width: 70%;
      .subtitle {
        color: black;
        &:hover {
          color: red;
          transition: all 0.2s
        }
        
      }
      .card-text {
        color: red;
      }
      
    } 
  }

  

}


</style>