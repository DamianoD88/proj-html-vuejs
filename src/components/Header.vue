<template>
<header>
  <div class="container">
      <div class="row">
          <!-- parte sinistra -->
        <span class="sx col-6">
            <img class="logotype" src="../assets/takeout-logo.png" alt="logo takeout" >
        </span>
          <!-- end parte sinistra -->

          <!-- parte destra -->
        <span class="dx col-6 mt-3" >
            <ul class="start">
              <li><a class="first-menu" href="#">Home <i class="fas fa-chevron-down"></i></a></li>
              <li><a class="first-menu" href="#">Order Online</a></li>
              <li><a class="first-menu" href="#">About</a></li>
              <li><a class="first-menu" href="#">News</a></li>
              <li><a class="first-menu" href="#">Contact Us</a></li>
            </ul>
        </span>
        <!-- end parte destra -->
        
      </div>

      <div class="delivered">
        <div class="hungry">
          Hungry?
        </div>
        <div class="great lh-1">
          Great Food
        </div>
        <div class="deliver lh-1">
            Delivered
        </div>
        <button type="button" class="btn btn-danger rounded-pill text-uppercase p-1 px-3 mt-4 fw-bold">View Our Menu</button>
      </div>
      <div id="second-row" class="row">
        <ul class="p-3 mb-2 bg-white text-dark d-flex justify-content-center">
          <li class="options mx-5 mt-4" ><i class="far fa-clock"></i> 24/7 DELIVERY</li>
          <li class="options mx-5 mt-4"><i class="fas fa-hamburger"></i> OVER 100 DISHES</li>
          <li class="options mx-5 mt-4"><i class="fas fa-mobile-alt"></i> IN APP ORDERING</li>
          <li class="options mx-5 mt-4"><i class="fas fa-car"></i> FAST DELIVERY</li>
        </ul>
      </div>
      
  </div>
</header>
  
</template>

<script>
export default {
    name: 'Header',
  components: {},
  data() {
    return {
      
    };
  },
}
</script>


<style lang="scss" >

header {
  background-image: url('../assets/home-background-hero-scaled.jpg');
  background-size: cover;
  width: 100%;
  height: 800px;
    
    .row {
      display: flex;
      align-items: center;
      
      .sx {
        width: 35%;
        display: inline-block;
        margin-left: 110px;

        .logotype {
          width: 200px;
        }
      }

      .dx {
        width: 50%;
        display: inline-block;
      }

    }
    

    ul {
        display: flex;
        margin-top: 50px;
        list-style: none;

        li {
            display: inline-block;
            font-size: 20px;
            font-weight: bold;
            font-size: 10px;
            margin-left: 20px;
            margin-right: 20px;
            padding-bottom: 50px;

            &:hover {
                    color: #fcdc31;
                    transition: all 0.2s
                }
            
            
            a {
                text-decoration: none;
                color: white;
                font-size: 15px;
                &:hover {
                color: #fcdc31;
                    
                }
            }
        }
    }
  .delivered {
      margin-left: 237px;
      text-align: left;
      margin-top: 200px;

    .hungry {
        color: #fff;
        font-size: 30px;
        font-weight: 600;
      }

    .great {
      font-weight: 700;
      font-size: 70px;
      letter-spacing: -5px;
      color: #fcdc31;
    }
    .deliver {
      font-weight: 700;
      font-size: 70px;
      letter-spacing: -5px;
      color: #fff;
    }
    button {
      transition: all .2s;
      font-size: 10px;
    }

  }
  #second-row {
    width: 70%;
    margin-top: 172px;
    margin-left: 225px; 

    .options {
      font-size: 13px;
      color: #4a4e57;

    }

  }
}


</style>