<template>
    <div class="products-services-container">
      <div class="home-wrapper">
        <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-blue">
    <div class="container-fluid">
        <h1 class="navbar-brand">Promos</h1>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav me-auto mb-2 mb-md-0">
          <li class="nav-item">
            <a class="nav-link" href="/">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/cashchat">CashChat</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/education">Education</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/kaatchup">Kaatchup</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/about-us">About-us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
              <div class="home-content">
                  <h1 class="flashing-paragraph">Products & Services</h1>
                  <p>Please contact our customer care for more, at inquiries@pesamoni.com, support@pesamoni.com, contact@pesamoni.com </p>
              </div>
               <button class="contact-us-btn" @click="contactUs"> <i class="fa fa-envelope-o" aria-hidden="true"></i> Contact us</button>
      </div>
      
      <my-footer></my-footer>
    </div>
  </template>
  
  <script>
  import MyFooter from './footer/MyFooter.vue'
  export default {
      components:{
          MyFooter
      },
      methods:{
        contactUs(){
          this.$router.push('/contact-us')
        }
      }
  }
  </script>
  
  <style scoped>
  .products-services-container{
      background-color: #fff;
      overflow: hidden;
  }
    .navbar-dark{
        background-color: #1a84c6;
    }
      .home-wrapper{
          background-image: url(https://images.pexels.com/photos/6930549/pexels-photo-6930549.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1);
          background-size: cover;
          height: 95vh;
          color: #fff;
      }
      
        a{
        text-decoration: none;
        font-size: 1.3rem;
        color: #fff;
      }
      .home-content{
          position: absolute;
          top: 20rem;
          left: 5rem;
          color: #fff;
          width: 45%;
      }
      .contact-us-btn{
        position: fixed;
        right: 0;
        bottom: 0;
        height: 3rem;
      }
      .contact-us-btn{
            margin: 3rem;
            padding: 10px 30px;
            border: none;
            border-radius: 5px;
            background-color: #428bca;
            position: fixed;
            right: 0;
            bottom: 0;
            z-index: 9999;
            color: white;
        }
        .contact-us-btn:hover{
            cursor: pointer;
            background: rgb(241, 174, 50);
            color: #428bca;
        }
        .e-learning{
          display: grid;
          grid-template-columns: 2fr 1fr;
          margin: 2.5rem 1rem;
        }
        .e-learning img{
          width: 50rem;
          height: 30rem;
          padding: 2rem;
          margin-left: -3.0rem;
        }
        .e-learning-content{
          background-color: #1a84c6;
          color: #fff;
          padding: 2rem;
          margin: 2rem;
          height: 26rem;
          margin-left: -5.5rem;
        }
        h2{
          text-align: center;
        }
        .title-h2{
          color: #1a84c6;
        }
        /* media querries */
        /* extra small screen */
        @media screen and (max-width: 600px) {
          .home-wrapper{
            margin: 0;
            padding: 0;
            background-position: center;
            background-repeat: no-repeat; 
          }
          .home-content h1{
            font-weight: 500;
          }
          .home-content p{
            font-weight: 400;
          }
        }
  </style>