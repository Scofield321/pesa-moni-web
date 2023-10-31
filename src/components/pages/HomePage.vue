<template>
  <div class="main-container">
      <!-- Home page starts here -->
      <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
    <div class="container-fluid">
        <h1 class="navbar-brand">PESAMONI</h1>
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
      <div class="home-wrapper">
          <!--Nav bar starts from here-->
          <!--Nav bar starts from here-->
                  <section class="home-content">
                    <div class="home-img">                      
                       <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
                            <div class="carousel-inner">
                              <div class="carousel-item active">
                                <img src="https://s3.us-east-1.amazonaws.com/victoria-university-elearning/website/images/intro_section_banner/487728ba-e0a1-4c7e-877f-df6e42e1ad86.jpg" class="d-block w-100" alt="...">
                              </div>
                              <div class="carousel-item">
                                <img src="https://images.pexels.com/photos/4145190/pexels-photo-4145190.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="d-block w-100" alt="...">
                              </div>
                              <div class="carousel-item">
                                <img src="https://images.pexels.com/photos/7988079/pexels-photo-7988079.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="d-block w-100" alt="...">
                              </div>
                              <div class="carousel-item">
                                <img src="https://images.pexels.com/photos/7007191/pexels-photo-7007191.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="d-block w-100" alt="...">
                              </div>
                              <div class="carousel-item">
                                <img src="https://images.pexels.com/photos/3762940/pexels-photo-3762940.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" class="d-block w-100" alt="...">
                              </div>
                            </div>
                            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
                              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                              <span class="visually-hidden">Previous</span>
                            </button>
                            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
                              <span class="carousel-control-next-icon" aria-hidden="true"></span>
                              <span class="visually-hidden">Next</span>
                            </button>
                        </div>
                    </div>

                    <div class="phone">
                        <div class="screen">
                          <div class="the-article">
                          <article>
                              <h2 class="animated-heading">Payments, Elearning Systems, Communication And Fun.</h2>
                              <img class="phone-img" src="https://images.pexels.com/photos/935835/pexels-photo-935835.jpeg?auto=compress&cs=tinysrgb&w=1000&h=700&dpr=1" alt="">
                          </article>
                          <!-- <button>Get started <span><i class="fa fa-arrow-right" aria-hidden="true"></i></span></button> -->
                      </div>
                        </div>
                      </div>

                    <!-- <div class="home-content-btn"> -->
                      
                       <!--
                          End of the carousle images at the home page
                         -->
                      <button class="contact-us-btn" @click="contactUs"> <i class="fa fa-envelope-o" aria-hidden="true"></i> Contact us</button>
                    <!-- </div> -->
                    <!-- wave animation starts here -->
                  </section>
                  <section class="wavy">
                      <div class="wave wave1"></div> 
                      <div class="wave wave2"></div> 
                      <div class="wave wave3"></div> 
                      <div class="wave wave4"></div> 
                </section>
                <!-- wave animation ends here -->
      </div>
            
      <!-- Home page stops here -->

      <!-- new and stories starts here -->
      <section class="new-stories">
        <h3>Products</h3>
        <h5>Select service of your interest:</h5>
          <router-link to="/pesamoni">PESAMONI</router-link>
          <router-link to="/education">EDUCATION</router-link>
          <router-link to="/cashchat">CASHCHAT</router-link>
          <router-link to="/kaatchup">KAATCH-UP</router-link>
      </section>
      <!-- new and stories starts here -->

      <!-- product and services starts here -->
      <section class="prdts-services">
        <h3>Products & Services</h3>
        <div class="product-service-first-content">
            <div class="product-service-content">
                <img src="https://images.pexels.com/photos/7621142/pexels-photo-7621142.jpeg?auto=compress&cs=tinysrgb&w=750&h=750&dpr=1" alt="">
                <div class="the-content">
                  <h3>Payment Systems</h3>
                  <p>Card payments using Stanbic Bank for Acquiring Card transaction over Card Not Present. Let us do the heavy lifting for you and your bank, we have all the resources to facilitae everything between you and the bank.. </p>
                </div>
            </div>
            <div class="product-service-content">
                <img src="https://images.pexels.com/photos/1181233/pexels-photo-1181233.jpeg?auto=compress&cs=tinysrgb&w=700&h=750&dpr=1" alt="">
                <div class="the-content">
                  <h3>E-learning Systems</h3>
                  <p>PESAMONI has an E-learning solution customized for any kind of school to conduct classes with live video class interaction, Audio interaction, Library for the classes, teacher’s virtual classrooms, administration virtual monitoring tools for E-learning. </p>
                </div>
            </div>
            <div class="product-service-content">
                <img src="https://images.pexels.com/photos/4144923/pexels-photo-4144923.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
                <div class="the-content">
                  <h3>Chat Systems</h3>
                  <p>We empower all those who want easy and secure communication in personal chats at free cost. All the chat have End-to-End Encryptio (E2EE),NOo one will be able to read yourr chat not even company employees </p>
                </div>
            </div>
            <div class="product-service-content">
                <img src="https://images.pexels.com/photos/6328941/pexels-photo-6328941.jpeg?auto=compress&cs=tinysrgb&w=750&h=750&dpr=1" alt="">
                <div class="the-content">
                  <h3>Fundraise From Anywhere</h3>
                  <p>We softens the process and all the hassles involved in raising funds from Friends, Family and everyone wherever in the world. You can raise funds for your business,occassions like baby shower, wedding, introduction and so many others. </p>
                </div>
            </div>
        </div>
      </section>
        <!-- products are services ends here -->
      <h1>Our Business</h1>
        <!-- our business starts from here -->
      <section class="our-business">
        <!-- <h1>Our Business</h1> -->
            <img src="https://images.pexels.com/photos/4492129/pexels-photo-4492129.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
            <div class="our-business-content">
                <h2>Our business</h2>
                <p>As a focused software company, we combine the real and the digital worlds and help customers to meet the great challenges of our time..</p>
                <p>Our businesses and other organizations like schools, and the society enjoy the freedom of our vast services from educaion, entertainment, earnings, and many more things, we customers  in the best way possible. The structure is geared toward creating value for customers, creating software with purpose.</p>
                <!-- <button>More</button> -->
            </div>
      </section>
        <!-- our business ends from here -->

        <!-- Who we are starts here -->
       
      <section class="who-we-are">
        <h1>About Us</h1>
        <!-- <h1>About Us</h1> -->
          <div class="who-we-are-content">
              <h2>Who we are</h2>
              <p>We are a software company focused on education, entertainment, payments, and communication.
              </p>
              <p>
                From more secure communication end to end encyption system, remarkable fun, proven education system of cutting edge technology and secure payments.
              </p>
              <p>
                By combining the real and the digital worlds, we empower our customers to transform their lives, helping them to transform the everyday for billions of people.
              </p>
          </div>
          <div>
              <img src="https://images.pexels.com/photos/5668887/pexels-photo-5668887.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
          </div>
      </section>
      <div class="link-to-about-us">
            <router-link to="/about-us">Show more <i class="fa fa-angle-right" aria-hidden="true"></i></router-link>
          </div>
        <!-- Who we are stops here -->
        <!-- footer starts here -->
        <my-footer></my-footer>
        <!-- footer stops here -->   

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

      }
    },
    methods:{
      contactUs(){
        this.$router.push('/contact-us')
      }
    }
  }

</script>

<style scoped>
/*
========================
    Home starts here
========================
    */
.main-container{  
  background-color: whitesmoke;
  overflow: hidden;
}
    .home-wrapper{
        background-image: linear-gradient(45deg, #f3874f, #662d91, #1a84c6, #f3874f, #f48e21);
        background-attachment: fixed;
        background-size: 300% 300%;
        animation: color 17s ease-in-out infinite;
        position: relative;
        height: 100vh;
        margin-top: -9rem;      
    }
    @keyframes color{
      0%{
        background-position: 0 50%;
      }
      50%{
        background-position: 100% 50%;
      }
      100%{
        background-position: 0 50%;
      }
    }
    .home-content{
      margin-top: 11rem;
      display: grid;
      grid-template-columns: 2fr 1fr;
    }
    .contact-us-btn{
      position: fixed;
      right: 0;
      bottom: -4rem;
      height: 3rem;
    }
    .home-img{
      margin-top: 3.5rem;
    }
    .home-img img {
    height: 70vh;
    width: 90%;
    margin: 4rem 3rem 3rem 1rem;   
}
    article h1{ 
        font-size: 1.5rem;
    }
    article h2{
        margin-top: 13rem;
        font-size: 2.2rem;
        font-style:arial black;
        font-weight: 600;
    }
    article{
        margin: 1rem .1rem;
        color: black;
    }
    article img{
      height: 12rem;
      width: 16.8rem;
    }
    .the-article{
      margin-top: -13rem;
    }
    /* button{
        margin: 7rem 2rem;
        padding: 10px 30px;
        border: none;
        border-radius: 5px;
        background-color: #1a84c6;
        position: absolute;
        z-index: 9999;
        color: white;
    }
    button:hover{
        cursor: pointer;
        background: #f3874f;
        color: white;
    } */
    .contact-us-btn{
          margin: 3rem;
          padding: 10px 30px;
          border: none;
          border-radius: 5px;
          background-color: #1a84c6;
          position: fixed;
          right: 0;
          bottom: 0;
          z-index: 9999;
          color: white;
      }
      .contact-us-btn:hover{
          cursor: pointer;
          background: #f3874f;
          color: white;
      }
    #carouselExampleAutoplaying button{
      display: none;
    }
    .wavy{
      margin-top: 10rem;
    }
    .wavy .wave{
        position: absolute;
        bottom: -2rem;
        left: 0;
        width: 100vw;
        height: 45px;
        background-position: center;
        background-image: linear-gradient(45deg,#f3874f ,#662d91, #1a84c6), url(../../assets/pesateam/wave.png);
        background-size: 1000px 100px;
        margin-bottom: 1rem;
    }
    .wavy .wave.wave1{
        animation: animate 10s linear infinite;
        z-index: 1000;
        opacity: 1;
        animation-delay: 0s;
        bottom: 0;
    }
    .wavy .wave.wave2{
        animation: animate2 5s linear infinite;
        z-index: 999;
        opacity: 0.5;
        animation-delay: -5s;
        bottom: 10px;
    }
    .wavy .wave.wave3{
        animation: animate 10s linear infinite;
        z-index: 998;
        opacity: 0.7 ;
        animation-delay: -2s;
        bottom: 20px;
    }
    .wavy.wave.wave4{
        animation: animate2 2s linear infinite;
        z-index: 997 ;
        opacity: 0.2 ;
        animation-delay: -2s;
        bottom: 15px;
    }
    @keyframes animate
    {
        0%{
            background-position-x: 0;
        }
        100%{
            background-position-x: 1000px;
        }
    }
    @keyframes animate2
    {
        0%{
            background-position-x: 0;
        }
        100%{
            background-position-x: -1000px;
        }
    }

    .phone {
        width: 290px; 
        height: 430px; 
        background-color: #333; 
        border-radius: 25px;
        margin: 50px auto; 
        position: relative;
        box-shadow: 10px 3px 5px rgb(195, 193, 193);
        margin-top: 7rem;
}

  .screen {
        background-color: #fff; 
        padding: 20px;
        border-radius: 15px; 
        height: 100%;
        box-sizing: border-box;
  }
  .phone-img{
    height: 10rem;
  }

p {
  font-size: 18px; 
  color: #333; 
  line-height: 1.5; 
}

@keyframes slideIn {
  from {
    transform: translateX(-10%);
    opacity: 0;
  }
  to {
    transform: translateX(0);
    opacity: 1;
  }
}

/* Apply the animation to the heading */
.animated-heading {
  animation: slideIn 1s ease forwards; 
}
    /*
    ========================
    Home stops here
    ========================
    */  
    /*
    ========================
    New stories starts here
    ========================
    */
    .new-stories{      
      background-color: white;
      height: 15rem;
    }
    .new-stories h3 , .new-stories h5{
      color:#f3874f ;
      margin: 2rem 4rem;
    }
    .new-stories h5{
      color: black;
    }
    .new-stories a{
      font-size:smaller;
      border: 1px solid #1a84c6;
      color: #1a84c6;
      padding: 8px 30px;
      margin: 1rem 1rem 1rem 4rem;
      border-radius: 20px;
    }
    .new-stories a:hover{
      color:#f3874f;
      border: 1px solid #f3874f;
    }

    /* 
    ========================
    New stories stops here
    ========================
    */

    /* 
    =========================================
    Product and services section starts here
    =========================================
    */

    .prdts-services{
      margin: 5rem 0;
      background-color:#fff;
    }
    .prdts-services h3, .prdts-services p,.prdts-services h2, .prdts-services h4 {
      color: #fff;
      margin-left: 3rem;
    }
  
    .prdts-services h3{
      text-align: center;
      padding: 2rem;
      color: #1a84c6;
    }
    .prdts-services p, .prdts-services h4{
      color: black;
    }
    .product-service-first-content{
        display: grid;
        grid-template-columns: 1fr 1fr;
        background-color: transparent;
        width: 100%;
    }
    .the-content{
      background-color: #1a84c6;
      color: #fff;
      margin: 0 1rem 2rem 1rem;
    }
    .the-content p, .the-content h3{
      color: #fff;
      font-weight: 200;
    }
    .the-content h3{
      font-weight: 500;
    }
    .the-content p{
      color: #fff;
    }
    .product-service-content{
      display: flex;
      flex-direction: column;
    }
    .product-service-content img{
        width: 95%;
        height: 50vh;
        background-color: #f3874f;
        margin-left: 1rem; 
    }
      /* 
    =========================================
    Product and services section ends here
    =========================================
    */

      /* 
    =========================================
    Our Business section starts here
    =========================================
    */
    .our-business{
        display: grid;
        grid-template-columns: 2fr 1fr;
        height: 80vh;        
    }
    .our-business img{
      width: 50rem;
    }
    .our-business-content{
        height: 28rem;
        color: white;
        background-color: #1a84c6;
        margin-left: -1.5rem;
    }

    .our-business-content h2{
      color: #fff;
      text-align: center;
      padding-top: 1rem;
      font-weight: 500;
    }
    .our-business-content p{
      color: #fff;
      padding: 0 2rem;
      font-weight: 200;
    }
      /* 
    =========================================
    Our Business section ends here
    =========================================
    */

      /* 
    =========================================
    Who we are section starts here
    =========================================
    */
    .who-we-are{
        display: grid;
        grid-template-columns: 1fr 2fr;
        gap: 2rem;
        background-color: white;
        margin-top: 7rem;
    }
    .who-we-are-content{
      color: #fff;
      background-color: #1a84c6;
      width: 28rem;
    }
    .who-we-are-content p{
      color: #fff;
      padding: 0 2rem;
      font-weight: 200;
    }
    .who-we-are-content h2{
      text-align: center;
      padding-top: 1rem;
      font-weight: 500;
    }
    .who-we-are img{
        width: 100%;
        /* background-color: none; */
    }
    a{
      text-decoration: none;
      /* padding: 4rem; */
      font-size: 1.3rem;
    }
    .link-to-about-us a{
      color: #1a84c6;
    }
    .link-to-about-us{
      margin-bottom: 3rem;
    }
    h1{
      display: none;
    }
      /* 
    =========================================
    Who we are section ends here
    =========================================
    */
/* 
media queries
*/

/* Extra small devices (phones, 600px and down) */
@media screen and (max-width: 600px){
  .main-container{
    width: 100%
  };
  .home-wrapper{
    margin-top: 2rem;
  }
  .home-content{
      margin:.1rem;
      display: flex;
      flex-direction:column;
    }
    .home-img img {
    height: 70vh;
    width: 100vh;
    margin-top: 5rem; 
    padding-right: -5rem; 
    display: flex;
    align-items: center;
    justify-content: center;
  }
    .phone{
      display: none;
    }
    /* 
    ===================
    New stories
    ===================
    */
    .new-stories{
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 33rem;
    }
    .new-stories h3 , .new-stories h5{
      text-align: center;
    }
    .product-service-first-content{
      grid-template-columns: 1fr;
    }
    .the-content{
      width: 100%;
    }
    .the-content p{
      text-align: center;
      margin: 2rem;
    }
    .the-content h3{
      text-align: center;
    }
    .product-service-content img{
      margin: 1rem;
    }
     /* 
    =========================================
    Our Business section starts here
    =========================================
    */
    .our-business{
      display: flex;
      flex-direction: column;
    }
    .our-business-content h2, .our-business-content p{
      text-align: center;
    }
     /* 
    =========================================
    Who we are section starts here
    =========================================
    */
    .who-we-are{
      display: flex;
      flex-direction: column;
      margin-top: 25rem;
    }
    .who-we-are-content p, .who-we-are-content h2{
      text-align: center;
    }
    .who-we-are-content p{
      margin-right: 4rem;
    }
    .who-we-are-content:nth-child(1){
      order: 2
    }
    .who-we-are-content:nth-child(2){
      order: 1;
    }
    h1{
      display: block;
      text-align: center;
    }
    

}
</style>