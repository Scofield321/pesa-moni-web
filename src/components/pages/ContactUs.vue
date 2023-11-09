<template>
  <div class="contact-container">
    <button class="menu-toggle" v-if="!showMenu" @click="toggleMenu"><i class="fa fa-bars" aria-hidden="true"></i>
</button>
<nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
    <div class="container-fluid">
        <h1 class="navbar-brand">CONTACT US</h1>
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
      <!-- <h5>Here you can send us an inquiry concerning general questions about Pesamoni</h5> -->
        <div class="contact-page">
          <div>
            <img src="https://images.pexels.com/photos/7035859/pexels-photo-7035859.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="customer care team">
          </div>
            <div class="contact-info">
                <h3 class="email-address">EMAIL</h3>
                <p>For email, please use the following based on your inquiry:</p>
                <p>inquiries@pesamoni.com</p>
                <p>contact@pesamoni.com</p>
                <p>support@pesamoni.com</p>
                <h3>TELEPHONE</h3>
                <p class="number">+256 39 3216308</p>
                <h3>LOCATION</h3>
                <p>Plot 146, Semawata Road, Ntinda</p>
                <p>Kampala, Uganda</p>
            </div>
            <!-- end of contact info -->
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
    data(){
    return{
        showMenu: true,
        showToggleButton: true
      }
    },
    methods:{
      toggleMenu(){
          this.showMenu = !this.showMenu
          this.showToggleButton = false;
      }
    } 
}
</script>

<style scoped>
    .contact-container{
        min-height: 100vh;
        background-color:#fff;
        overflow: hidden;
    }
    h3{
       text-align: center;
       padding-top: .5rem;
    }
    .contact-page{
        display: grid;
        grid-template-columns: 1fr 1fr;
        height: 98vh;
    }
    img{
      width: 50rem;
      height: 32.7rem;
      margin-top: 4rem;
    }
    h3, h5{
        color: black;
        margin: 6rem  20rem 2rem;
        /* text-align: center; */
    }
.contact-info{
    background-color:#f3874f;
    color: white;
    margin: 4rem 2rem 2rem 2rem;
    width: 85%;
    height: 32.7rem;
    padding-bottom: 3rem;
}
.contact-info p, .contact-info h3{
    margin-left: 3rem;
}
.contact-info h3{
    margin-top: .5rem;
    text-align: left;
    font-size: large;
}
.email-address{
    margin-top:4rem;
}
.number{
  padding-top: -1rem;
}
/* Small devices (portrait tablets and large phones, 600px and up) */
@media screen and (max-width: 600px) {
    .contact-container{
        overflow: hidden;
    }
      h3{
       text-align: center;
       margin-top: -2rem;
    }
    .contact-page{
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      margin-top: -5.2rem;
      height: 80rem;
    }
    img{
      margin-bottom: -3rem;
    }
    .contact-info{
        width: 99%;
        padding-bottom: -1rem;
        height: 35rem;
        margin-bottom: -4rem;
}
    .email-address{
    padding-top:4rem;
}
 }
 /* Small devices (portrait tablets and large phones, 600px and up) */
@media screen and (min-width: 600px) {
  .contact-page{
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      margin-top: -4.2rem;
      height: 80rem;
    }
    .contact-info{
        width: 99%;
        margin-bottom: -4rem;
        height: 35rem;
    }
    img{
        margin-bottom: -3rem;
    }
}
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .contact-page{
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      margin-top: -4.2rem;
      height: 80rem;
    }
    img{
      width: 99vw;
      margin-bottom: -3rem;
    }
    .contact-info{
        margin-bottom: -4rem;
    }
}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .contact-page{
      display: flex;
      flex-direction: row;
      align-items: center;
      justify-content: center; 
      margin-top:4rem;
      height: 90vh;
    }
    img{
      width: 50rem;
      height: 33.7rem;
      margin-top: -3rem;
    }
    .contact-info{
    margin: 1.5rem 2rem 2rem 2rem;
    width: 30rem;
    height: 33.7rem;
    padding-bottom: 3rem;
}
}
</style>