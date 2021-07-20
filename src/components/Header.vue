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
        <span class="dx col-6" >
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
        <div class="great">
          Great Food <br>
          <span class="deliver">
            Delivered
          </span>
        </div>
        <button>
          
        </button>
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
        width: 65%;
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
        color: #fff;
      }
    
  }
}


</style>