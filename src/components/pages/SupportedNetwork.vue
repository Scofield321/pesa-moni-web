<template>
  <div class="supported-network-container">
    <div class="home-wrapper">
      <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-blue">
    <div class="container-fluid">
        <h1 class="navbar-brand">Supported Networks</h1>
      <!-- <a class="navbar-brand" href="/educatiion">EDUCATION</a> -->
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
                <h1>Supported Networks</h1>
                <p>For more information about supported networks, you can contact us at:  support@pesamoni.com.</p>
            </div>
             <button class="contact-us-btn" @click="contactUs"> <i class="fa fa-envelope-o" aria-hidden="true"></i> Contact us</button>
    </div>
    <section class="supported-networks">
      <h2>These are the networks we support</h2>
      <div class="imgs-of-network">
        <img src="https://1000logos.net/wp-content/uploads/2022/08/MTN-Logo-1994-.png" alt="mtn logo">
        <img src="https://s3-ap-southeast-1.amazonaws.com/bsy/iportal/images/airtel-logo-white-text-horizontal.jpg" alt="airtel logo">
        <img src="https://ik.imagekit.io/tp/20220202-m-pesa-logo.png" alt="mpesa logo">
        <img src="https://creazilla-store.fra1.digitaloceanspaces.com/cliparts/9108/bank-clipart-md.png" alt="banks">
      </div>
    </section>
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
.supported-network-container{
    background-color: #fff;
    overflow: hidden;
}
.navbar-dark{
    background-color: #1a84c6;
}
    .home-wrapper{
        background-image: url(https://images.pexels.com/photos/12935064/pexels-photo-12935064.jpeg?auto=compress&cs=tinysrgb&w=400);
        background-size: cover;
        height: 90vh;
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
      .supported-networks{
        text-align: center;
      }
      .supported-networks img{
        height: 6rem;
        padding: 1rem;
      }
      h2{
        color: #1a84c6;
        text-align: center;
      }

       /* Extra small devices (phones, 600px and down) */
@media screen and (max-width: 600px){
  .supported-network-container{
    overflow: hidden;
}
.home-wrapper{
  margin: 0;
  padding: 0;
  background-position: center;
  background-repeat: no-repeat; 
}
.home-content{
  margin-top: -9rem;
}
.home-content h1{
  font-size: 3rem;
  font-weight: 500
}
.home-content p{
  font-weight: 400
}


  .imgs-of-network{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .imgs-of-network img{
    width: 10rem;
  }
}

</style>