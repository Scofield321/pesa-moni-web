<template>
  <div class="pesamoni-container">
    <div class="home-wrapper">
            <button class="menu-toggle" v-if="!showMenu" @click="toggleMenu"><i class="fa fa-bars" aria-hidden="true"></i>
            </button>
            <nav>
                <h1>PESAMONI</h1>
                <!-- <img width="100%" height="100%" src="https://res.cloudinary.com/african-centre-for-peace-and-human-life/image/upload/v1526376738/Pesamoni/Nav-logo.png" alt="Nav logo"> -->
                <router-link to="/">Home</router-link>
                <router-link to="/pesamoni">Pesamoni</router-link>
                <router-link to="/cashchat">CashChat</router-link>
                <router-link to="/education">Education</router-link>
                <router-link to="/kaatchup">Kaatch-Up</router-link>
                <router-link to="/about-us">About Us</router-link>
            </nav>
          <div class="home-content">
              <div class="home-card">
                <h1>PesaMoni, signup and start sending money with ease</h1>
              </div>
            <button class="contact-us-btn" @click="contactUs"> <i class="fa fa-envelope-o" aria-hidden="true"></i> Contact us</button>
            </div>           
        </div>
        <!-- section for pesa-phone-shot starts here -->
        <section class="pesa-phone-shot">
            <div class="image-container">
                <img src="https://res.cloudinary.com/african-centre-for-peace-and-human-life/image/upload/v1526375823/Pesamoni/landing-page-interface-screen.png" alt="pesamoni phone shot" class="centered-image">
            </div>
            <div class="pesamoni-phone-shot-content">
                <h3>The PesaMoni App</h3>
                <p>Make seamless transactions on spot, with the PesaMoni App.</p>
                <a href=""><img src="https://res.cloudinary.com/african-centre-for-peace-and-human-life/image/upload/v1526381204/Pesamoni/get_it.png" alt="playstore-logo"></a>
            </div>
        </section>  
        <!-- section for pesa-phone-shot ends here -->

        <!-- section for transactions ends here -->
        <section class="transactions">
            <div class="transaction-content">
                <h4>With our platform, transactions have been made easier.</h4>
                <p>Simply choose an account of your choice and enjoy the no hustle.</p>
            </div>
            <div class="cards">
                <div class="card1">
                    <h4>Personal Account</h4>
                    <div class="icon">
                        <i class="fa fa-user" aria-hidden="true"></i>
                    </div>
                    <button>Get Started</button>
                </div>
                <div class="card2">
                    <h4>Business Account</h4>
                    <div class="icon">
                        <i class="fa fa-briefcase" aria-hidden="true"></i>
                    </div>
                    <button>Get Started</button>
                </div>
            </div>
            
        </section>
        <!-- section for transactions ends here -->

        <!-- section for more-content ends here -->
        <section class="more-info">
            <div class="more-content">
                <img src="https://res.cloudinary.com/african-centre-for-peace-and-human-life/image/upload/v1526376739/Pesamoni/pesacard-full.png" alt="pesamoni card">
                <div class="more-content-wording">
                    <h4>With PesaMoni comes simplicity</h4>
                    <p>Use the PesaCard to fund your wallet anytime.</p>
                    <button>Find Out More</button>
                </div>
            </div>
            <div class="more-info-img">
                <!-- <img src="https://res.cloudinary.com/african-centre-for-peac…mage/upload/v1526380510/Pesamoni/rohit-tandon.png" alt=""> -->
            </div>
        </section>
        <!-- section for more-content ends here -->

        <!-- section for more information about -->
        <my-footer></my-footer> 
  </div>
</template>

<script>
import MyFooter from './footer/MyFooter.vue';
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
        contactUs(){
          this.$router.push('/contact-us')
        },
      toggleMenu(){
          this.showMenu = !this.showMenu
          this.showToggleButton = false;
      }
      }
}
</script>

<style scoped>
    .pesamoni-container{
    background-color: #fff;
    overflow: hidden;
  }
  /* 
  ===============
  home starts here
  ===============
  */
  .home-wrapper{
        background-image: url(https://res.cloudinary.com/african-centre-for-peace-and-human-life/image/upload/v1526375765/Pesamoni/another-hero.png);
        background-size: cover;
        position: relative;
        min-height: 120vh;
        margin-top: -5rem;  
    }
    nav{
        display: flex;
        justify-content: flex-start;
        align-items: center;
        position: absolute;
        /* background-color: rgb(251, 91, 91); */
        z-index: 99999;
        height: 4rem;
        margin-top: 1rem;
        width: 100%;        
      }
      nav a{
        padding: 1rem;
        color: #fff;
      }
      nav a:hover{
        color: #1a84c6;
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
    .home-content{
      display: grid;
      grid-template-columns: 1fr 1fr;
      margin-top: 4rem;
      width: 100vw;
      position: relative;
    }
    .home-card{
        position: absolute;
        top: 20rem;
        left: 5rem;
    }
    .home-card h1{
        text-align: center;
        width: 30rem;
        color: #fff;
        font-weight: 200;
    }
    .home-card button{
        margin-left: 3rem;
        width: 10rem;
        background: #1a84c6;
        color: #fff;
    }
    .contact-us-btn{
      position: fixed;
      right: 0;
      bottom: 0;
      height: 3rem;
    }
    .home-img{
      margin: 6rem 2rem 3rem 3rem;
    }
    button{
        padding: 10px 30px;
        border: none;
        border-radius: 5px;
        background-color: #f3874f;
        position: absolute;
        z-index: 9999;
    }
    button:hover{
        cursor: pointer;
        background: #f3874f;
        color: white;
    }
  .home-page h1{
      position: fixed;
      top: 0;
      left: 0;
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
      /* 
      =====================
      home ends here
      =====================
      */

      /* 
      ================================
      pesamoni-phone-shot starts here
      ================================
      */
      .pesa-phone-shot{
          background: #fff;
          height: 75vh;
          display: grid;
          grid-template-columns:2fr 1fr;
      }
      .image-container{
          display: flex;
          justify-content: center;
          margin-bottom:3rem ;
      }
      .centered-image{
          max-width: 100%;
          margin-top: 4rem;
      }
      .pesamoni-phone-shot-content{
          margin: 10rem 10rem 10rem -10rem;
      }
      .pesamoni-phone-shot-content a{
          margin-left: -3.7rem;
      }
      /* 
      ================================
      pesamoni-phone-shot ends here
      ================================
      */

      /* 
      ===========================================
      section for transactions ends here ends here
      ==========================================
      */
      .transactions{
          background: whitesmoke;
      }
      .transaction-content{
          text-align: center;
          padding: 3rem;
      }
      .cards{
          display: grid;
          grid-template-columns: 1fr 1fr;
      }
      .card1, .card2{
          background-color:#fff;
          width: 20rem;
          height: 20rem;
          margin: 4rem;
          text-align: center; 
          box-shadow: 10px 10px 5px  rgb(209, 239, 248);
      }
      .card1 h4, .card2 h4{
          padding: 1rem;
      }
    .icon{
         font-size: 7rem; 
         color: #1a84c6;
      }
      .card1 button, .card2 button{
          margin-left: -4.5rem;
          background-color: #1a84c6;
          color: #fff;
      }
      .card1 button:hover, .card2 button:hover{
        background-color: #f3874f;
      }
      .card1{
        margin-left: 15rem;
      }
      /* 
      ===========================================
      section for transactions ends here ends here
      ===========================================
      */

      /* 
      ===========================================
      section for more info ends here ends here
      ===========================================
      */
      .more-info{
        margin-bottom: 3rem;
      }
      .more-content{
          background-color: #fff;
          display: grid;
          grid-template-columns: 1fr 1fr;
      }
      .more-content img{
          margin: 5rem 0 5rem 0;
      }
      .more-content-wording{
          margin: auto;
      }
      .more-content-wording button{
        background-color: #1a84c6;
        color: #fff;
      }
      .more-content-wording button:hover{
        background-color: #f3874f;
      }
      .more-info-img{
          background: url(https://res.cloudinary.com/african-centre-for-peace-and-human-life/image/upload/v1526380510/Pesamoni/rohit-tandon.png) center;
          background-size: cover;
          height: 60vh;
          background-color: white;
      }
      /* 
      ===========================================
      section for more info ends here ends here
      ===========================================
      */

      /* media queries*/ 
/* Extra small devices (phones, 600px and down) */
@media screen and (max-width: 600px) {
        .pesamoni-container{
            min-height: 100vh;
            width: 100%;
            overflow: hidden;
        }
        nav{
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            position: unset;
            z-index: 99999;
            height: 19rem;
            margin-top: 6rem;
            /* margin-bottom: 30rem; */
            width: 100%; 
            /* background-color: #1a84c6;       */
        }
        nav a{
            padding: .5rem;
            color: #fff;
            text-decoration: none;
            font-size: 1rem;
            width: 100%;
            text-align: center;
            float: left;
        } 
        nav a:active{
            color: #f3874f;
            border: 1px solid #fff;
        }
        nav h1{
            display: none;
        }
      
        .home-wrapper{
            min-height: 50vh;
            width: 100%;        
        }
        .home-content{
            display: grid;
            grid-template-columns: 1fr;
        }
        .home-wrapper{
        background-size: 100% auto;
        background-repeat: no-repeat;
        position: unset;
    }
        .menu-toggle {
            display: block; 
        }  
        .home-card{
            position: unset;
        }  
        .home-card h1{
            width: 100%;
        }
        .pesa-phone-shot{
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            width: 100%;
        }
        .image-container{
            margin-bottom:1rem ;
        }
        .image-container img{
            width: 12rem;
        }
        .pesamoni-phone-shot-content{
            margin: 1rem;
            text-align: center;
            width: 18rem;
        }
        .pesamoni-phone-shot-content h3{
            font-size: 1rem;
        }
        .pesamoni-phone-shot-content p{
            font-size: .7rem;
        }
        .pesamoni-phone-shot-content img{
            height: 2.5rem;
        }
        .centered-image{
            max-width: 100%;
            margin-top: 4rem;     
        }
        /* transactions */
        .transaction-content{
            text-align: center;
            padding: 1rem;
        }
        .cards{
            display: flex;
            flex-direction:column;
            justify-content: center;
            align-items:center;
        }
        .card1, .card2{
            width: 20rem;
            height: 20rem;
            margin: 1rem 2rem 4rem 2rem;
        }
        .card1 h4, .card2 h4{
            padding: 1rem;
        }
        .icon{
            font-size: 6rem; 
            margin-top: -1rem;
            margin-bottom: 2rem;
        }
        /* more info */
        .more-info{
            margin-bottom: 5rem;

        }
        .more-content{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .more-content img{
            margin: 5rem 0 5rem 0;
            width: 30rem;
        }
        .more-content-wording{
            margin: -2rem 1rem 4rem 1rem;
        }
}

      /* Small devices (portrait tablets and large phones, 600px and up) */
      @media screen and (min-width: 600px) {         
        .pesamoni-container{
            min-height: 100vh;
            width: 100%;
            overflow: hidden;
        }
        nav{
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            position: unset;
            z-index: 99999;
            height: 21rem;
            margin-top: 6rem;
            margin-bottom: -4rem;
            width: 100%; 
            /* background-color: #1a84c6;       */
        }
        nav a{
            padding: .5rem;
            font-size: 1.3rem;
            width: 100%;
            text-align: center;
        } 
        nav a:hover{
            color: #f3874f;
        }
        nav h1{
            display: none;
        }
        .home-wrapper{
        background-size: 100% auto;
        background-repeat: no-repeat;
        position: unset;
        }
        .home-wrapper{
            min-height: 60vh;
            width: 100%;        
        }
        .home-content{
            display: grid;
            grid-template-columns: 1fr;
    }
        .menu-toggle {
            display: block; 
  }  
        .home-card{
            position: unset;
    }  
        .home-card h1{
            width: 100%;
    }
        .pesa-phone-shot{
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            width: 100%;
      }
        .image-container{
            margin-bottom:1rem ;
      }
        .image-container img{
            width: 17rem;
      }
        .pesamoni-phone-shot-content{
            margin: 1rem;
            text-align: center;
            width: 18rem;
      }
        .pesamoni-phone-shot-content h3{
            font-size: 2.0rem;
      }
        .pesamoni-phone-shot-content p{
            font-size: 1.2rem;
      }
        .pesamoni-phone-shot-content img{
            height: 3.5rem;
      }
        .centered-image{
            max-width: 100%;
            margin-top: 4rem;     
      }
      /* transactions */
        .transaction-content{
            text-align: center;
            padding: 1rem;
      }
        .cards{
            display: flex;
            flex-direction:column;
            justify-content: center;
            align-items:center;
      }
        .card1, .card2{
            width: 22rem;
            height: 22rem;
            margin: 1rem 2rem 4rem 2rem;
      }
        .card1 h4, .card2 h4{
            padding: 1rem;
      }
        .icon{
            font-size: 8rem; 
            margin-top: -1rem;
            margin-bottom: 2rem;
      }
      /* more info */
        .more-info{
            margin-bottom: 5rem;
        }
        .more-content{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .more-content img{
            margin: 5rem 0 5rem 0;
            width: 35rem;
        }
        .more-content-wording{
            margin: -2rem 1rem 4rem 1rem;
        }
    }
    /* Medium devices (landscape tablets, 768px and up) */
    @media screen and (min-width: 768px) {
        .pesamoni-container{
            min-height: 100vh;
            width: 100%;
            overflow: hidden;
        }
        nav{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            position: relative;
            z-index: 99999;
            height: 6rem;
            margin-bottom: -4rem;
            width: 100%;   
            background-color:transparent ;  
            padding-top: 2rem; 
            background-color: #1a84c6;
        }
        nav a{
            padding: .5rem;
            font-size: 1.3rem;
            width: 100%;
            text-align: center;
        } 
        nav h1{
            display: none;
        }
      
        .home-wrapper{
            min-height: 100vh;
            width: 100%; 
            margin-top: -6rem;       
        }
        .home-content{
            display: grid;
            grid-template-columns: 1fr 1fr;
            /* margin-left: -6rem; */
    }
        .menu-toggle {
            display: block; 
  }  
        .home-card{
            position: absolute;
            width: 40%;
    }  
        .home-card h1{
            width: 100%;
    }
        .pesa-phone-shot{
            height: 100vh;
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            /* align-items: center; */
            width: 100%;
      }
        .image-container{
            margin-bottom:1rem ;
      }
        .image-container img{
            width: 17rem;
      }
        .pesamoni-phone-shot-content{
            margin: 1rem;
            /* text-align: center; */
            width: 25rem;
      }
        .pesamoni-phone-shot-content h3{
            font-size: 2.0rem;
      }
        .pesamoni-phone-shot-content p{
            font-size: 1.2rem;
      }
        .pesamoni-phone-shot-content img{
            height: 2.5rem;
      }
        .centered-image{
            max-width: 100%;
            margin-top: 4rem;     
      }
      /* transactions */
        .transaction-content{
            text-align: center;
            padding: 1rem;
      }
        .cards{
            display: flex;
            flex-direction:row;
            justify-content: space-around;
            align-items:center;
      }
        .card1, .card2{
            width: 20rem;
            height: 20rem;
            margin: 1rem 2rem 4rem 2rem;
      }
        .card1 h4, .card2 h4{
            padding: 1rem;
      }
        .icon{
            font-size: 6rem; 
            margin-top: -1rem;
            margin-bottom: 2rem;
      }
      /* more info */
        .more-info{
            margin-bottom: 5rem;
        }
        .more-content{
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            align-items: center;
        }
        .more-content img{
            margin: 5rem 0 5rem 0;
            width: 35rem;
        }
        .more-content-wording{
            margin: -2rem 1rem 4rem 1rem;
        }
    }
    /* Large devices (laptops/desktops, 992px and up) */
    @media screen and (min-width: 992px) {
        nav h1{
            display: block;
        }
        nav{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            position: relative;
            z-index: 99999;
            height: 6rem;
            margin-bottom: -4rem;
            width: 100%;   
            background-color:transparent ;  
            padding-top: 2rem; 
        }
    }

</style>