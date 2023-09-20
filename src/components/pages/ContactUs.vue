<template>
  <div class="contact-container">
    <button class="menu-toggle" v-if="!showMenu" @click="toggleMenu"><i class="fa fa-bars" aria-hidden="true"></i>
</button>
        <nav>
           <h1>Contact Us</h1>
                <router-link to="/">Home</router-link>
                <router-link to="/pesamoni">Pesamoni</router-link>
                <router-link to="/cashchat">CashChat</router-link>
                <router-link to="/education">Education</router-link>
                <router-link to="/kaatchup">Kaatch-Up</router-link>
                <router-link to="/about-us">About Us</router-link>
        </nav>
      <!-- <h5>Here you can send us an inquiry concerning general questions about Pesamoni</h5> -->
        <div class="contact-page">
            <div class="contact-info">
                <h3 class="email-address">EMAIL</h3>
                <p>For email, please use the following based on your inquiry:</p>
                <p>inquiries@pesamoni.com</p>
                <p>contact@pesamoni.com</p>
                <p>support@pesamoni.com</p>
                <h3>TELEPHONE</h3>
                <p>+256 39 3216308</p>
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
        background-color:black ;
        overflow: hidden;
    }
    nav{
        display: flex;
        justify-content: flex-start;
        align-items: center;
        position: absolute;
        z-index: 99999;
        height: 4rem;
        margin: -2rem 0 2rem 0;
        width: 100%;    
        padding: 4rem 0;    
      }
      nav a{
        padding: 1rem;
        color: black;
        color: #1a84c6;
      }
      nav a:hover{
        color: #f3874f;
      }
      nav h1{
        margin: 0 6rem 0 2rem;
        color: #1a84c6;
      }

      a{
      text-decoration: none;
      padding: 4rem;
      font-size: 1.3rem;
    }
    h3{
       text-align: center;
       padding-top: .5rem;
    }
    .contact-page{
        padding: 1rem 10rem 1rem 10rem;
    }
    h3, h5{
        color: black;
        margin: 6rem  20rem 2rem;
    }
.contact-info{
    background-color:#f3874f;
    color: white;
    margin: 6rem 2rem 2rem 2rem;
    width: 95%;
    padding-bottom: 3rem;
}
.contact-info p, .contact-info h3{
    margin-left: 3rem;
}
.contact-info h3{
    margin-top: 2rem;
    text-align: left;
    font-size: large;
}
.email-address{
    padding-top:4rem;
}
/* Small devices (portrait tablets and large phones, 600px and up) */
@media screen and (max-width: 600px) {
    .contact-container{
        width: 100%;
        overflow: hidden;
    }
    nav{
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: center;
        position: unset;
        z-index: 99999;
        height: 23rem;
        width: 100%;    
        background-color: #1a84c6; 
      }
      nav a{
        padding: .5rem;
        color: white;
        font-size: 1.2rem;
      }
      nav h1{
        display: none;
      }
      h3{
       text-align: center;
       padding-top: .5rem;
    }
    .contact-page{
        width: 100%;
        margin-top: -5rem;
        border-radius: 10px;
    }
    h3, h5{
        color: black;
        margin: 6rem  20rem 2rem;
    }
    .contact-info{
    /* margin: 6rem 2rem 2rem 2rem; */
        width: 95%;
        padding-bottom: 3rem;
}
.email-address{
    padding-top:4rem;
}
 }
</style>