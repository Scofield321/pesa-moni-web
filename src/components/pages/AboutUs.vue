<template>
  <div class="about-us-container">
    <div class="homepage">
        <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-blue">
    <div class="container-fluid">
        <h1 class="navbar-brand">About Us</h1>
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
        <article>
            <h1 class="flashing-paragraph">With Pesamoni, You Can Make It.</h1>
        </article>
        <button class="contact-us-btn" @click="contactUs"> <i class="fa fa-envelope-o" aria-hidden="true"></i> Contact us</button>
    </div>
    <section>
        <div class="about-pesamoni">
            <h1>Who we are</h1>
            <p>PESAMONNI Limited is Software Company operating in East Africa. PESAMONI 
                began in 2016 with a view of transforming advanced technology to become ordinary 
                for the normal person. We connect over 500,000 clients across East Africa. Our 
                strength is in development of all kinds of software ranging from education, Finance,
                Agriculture, Health, Telecommunications and Banking.
            </p>
        </div>
    </section>
    <section class="strategy">
        <div class="e-learning">
            <div>
                <img class="strategy-img" src="https://images.pexels.com/photos/3768894/pexels-photo-3768894.jpeg" alt="strategy Image">
            </div>
            <div class="heading-content2">
                <h3>Strategy</h3>
                <p>We combine real and the digital worlds. Our strategy is powered by the long term. addressing the biggest challenges of our generation; old fashioned schooling, backwards communication, analog payment systems</p>
            </div>
        </div>
    </section>
    <section>
        <h2>Products & Services</h2>
        <div class="business-and-services">
            <div class="e-learning">
                <div>
                    <img src="https://s3.us-east-1.amazonaws.com/victoria-university-elearning/website/images/intro_section_banner/487728ba-e0a1-4c7e-877f-df6e42e1ad86.jpg" alt="">
                </div >
                <div class="heading-content">
                    <h3>E-Learning and Distance learning</h3>
                    <p>
                        PESAMONI has an E-learning solution customized for any kind of school,
                        university, secondary school, primary school with unique features and tools
                        available to conduct classes with live video class interaction, Audio
                        interaction, Library for the classes, teacher’s virtual classrooms,
                        administration virtual monitoring tools for E-learning. We have Learnida
                        advanced e-learning software for all schools and available to install for each
                        school that suits the needs of the school.
                    </p>
                </div>
            </div>
            <div class="payments">
                <div>
                    <img src="https://images.pexels.com/photos/6995134/pexels-photo-6995134.jpeg?auto=compress&cs=tinysrgb&w=1260&h=700&dpr=1" alt="">
                </div>
                <div class="heading-content2">
                    <h3>Card Payments</h3>
                    <p>
                        Card payments using Stanbic Bank for Acquiring Card transaction over Card
                        Not Present. Let us do the heavy lifting for you and your bank, we have all the resources to facilitae everything between you and the bank.
                    </p>
                </div>
            </div>
            <div class="software-development">
                <div>
                    <img src="https://images.pexels.com/photos/3861958/pexels-photo-3861958.jpeg?auto=compress&cs=tinysrgb&w=1260&h=700&dpr=1" alt="">
                </div>
                <div class="heading-content3">
                    <h3>Software Development</h3>
                    <p>
                        PESAMONI develops any kind of software in all sectors in the economy ELearning, Payment gateway, E-commerce, Management systems, School
                        payment systems and educational systems.
                    </p>
                </div>
            </div>
        </div>
        
    </section>
    <!-- Team starts here -->

    <section class="all-the-cards">
      <!--  start of cards slider -->
      <div class="carousel-cards">
            <h2>Company Profile</h2>
        </div>
                <div id="carouselExampleControlsNoTouching" class="carousel slide" data-bs-touch="false" data-bs-interval="false">
                <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="row" >
                        <div class="col-sm-6">
                            <div class="card">
                                <div class="my-card1 d-block w-100">
                                    <img src="../../assets/pesateam/asher2.jpg" alt="Asher image ceo">
                                    <div class="img-content">
                                        <h4>Namanya Asher</h4>
                                        <p>Founder and CEO</p>
                                    </div>
                                </div>
                                <div class="my-card1 d-block w-100">
                                    <img src="../../assets/pesateam/reagan.jpg" alt="Reagan engineering ">
                                    <div class="img-content">
                                        <h4>Kizito Reagan</h4>
                                        <p>Head of Engineering</p>
                                    </div>
                                </div>
                                <div class="my-card1 d-block w-100">
                                    <img src="../../assets/pesateam/daphine2.jpg" alt="daphine sales">
                                    <div class="img-content">
                                        <h4>Kisakye Daphine</h4>
                                        <p>Customer Care</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div> 
                                  
                </div>  
                <div class="carousel-item">
                    <div class="row">
                        <div class="col-sm-6">
                            <div class="card">
                                <div class="my-card4 d-block w-100">
                                    <img src="../../assets/pesateam/allen2.jpg" alt="Allen Admnistrator">
                                    <div class="img-content">
                                        <h4>Kwagala Namuddu</h4>
                                        <p>Head of Administration</p>
                                    </div>
                                </div>
                                <div class="my-card4 d-block w-100">
                                    <img src="../../assets/pesateam/mercy.jpg" alt="Mercy Accountant">
                                    <div class="img-content">
                                        <h4>Tukei Mercy</h4>
                                        <p>Accountant</p>
                                    </div>
                                </div>
                                <div class="my-card4 d-block w-100">
                                    <img src="../../assets/pesateam/Scofieldimg.jpeg" alt="Scofield software enginner">
                                    <div class="img-content">
                                        <h4>Semujju Derick Scofield</h4>
                                        <p>Software Developer</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    </div>                     
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControlsNoTouching" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
            </div>
                <!--  end of cards slider -->
    </section>
    <!-- Team stops here -->
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
.about-us-container{
    background-color: whitesmoke;
    overflow: hidden;
}
.navbar-dark{
  background-color: #1a84c6;
}
/* 
===========================
Home page starts here
===========================
*/
.homepage{
    min-height: 100vh;
    width: 100%;
    background-image: url(https://images.pexels.com/photos/1181317/pexels-photo-1181317.jpeg?auto=compress&cs=tinysrgb&w=1000&h=750&dpr=1);
    background-size: cover;
    position: relative;
    top: -4rem;
    left: 0;
    animation: moveImage 10s infinite alternate;
    filter: brightness(50%)   
}

@keyframes moveImage{
    0%{
        background-position: 0% 0% ;
    }
    100%{
        background-position: 100% 100%;
    }
}

article{
    width: 50%;
    font-size: 1.4rem;
    font-style: italic;
    color: #fff;
    margin: 4rem;
    padding-top: 10rem;
    font-weight: 900;
}
article h1{
    font-size: 5rem;
}

@keyframes flash {
  0% {
    opacity: 1; 
  }
  50% {
    opacity: 0; 
  }
  100% {
    opacity: 1; 
  }
}

/* Apply the flashing animation to the heading */
.flashing-paragraph {
  animation: flash 2s infinite; 
}

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
/* 
===========================
Home page stops here
===========================
*/

/* 
===========================
about pesamoni starts here
===========================
*/
.about-pesamoni{
    margin: 0 4rem;
    height: 5rem;
}
.about-pesamoni h1{
    color: #000000;
}
.about-pesamoni p{
    color: #000000;
}
/* 
===========================
about stops here
===========================
*/

/* 
===========================
strategy starts here
===========================
*/
.strategy{
    display: grid;
    grid-template-columns: 2fr 1fr;
    background-color: white ;
    margin: 6rem 0;
}
.strategy-content{
    margin-left: 3rem ;
    background-color: #1a84c6;
    color: #fff;
    height: 22.5rem;
    width: 28rem;
}

.strategy h2{
    font-weight: 500;
    margin-top: 2rem;
    color: #fff;
}
.strategy p{
    font-weight: 200;
    margin-top: 1rem;
}
.strategy-content p{
    padding: 1rem 0 4rem 0;
}
.strategy img{
    height: 25rem;
    width: 40rem;
    margin: -.1rem 1rem 1rem 1rem ;
    border-radius: 5px;
}
/* 
===========================
strategy stops here
===========================
*/
/* 
=================================
products and services starts here
=================================
*/
.business-and-services{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    gap: 2rem;
    border-radius: 5px;
}
.e-learning{
    display: flex;
    flex-direction: column;
}
h2{
    color: #f3874f;
    text-align: center;
    margin-bottom: 4rem;
}
.e-learning p, .payments p, .software-development p{
    color: #fff;
    margin-left: 1.2rem;
    font-size: 1.1rem;
    font-weight: 200;
}
.e-learning img, .payments img, .software-development img{
    width: 18rem;
    margin: 0 5rem 4rem 2rem ;
}

h3{
    color: #fff;
    margin:1.3rem;
    text-align: center;
    font-weight: 500;
}
.heading-content, .heading-content2, .heading-content3{
    background-color: #1a84c6;   
    height: 30rem;
    margin: 0 0 1rem 2rem;
}
.heading-content h3{
    margin-top: .1rem;
    padding: 1rem;
}
.heading-content h3, .heading-content2 h3, .heading-content3 h3{
        padding-top: 1rem;
    }
.heading-content p, .heading-content2 p, .heading-content3 p{
    padding: 0 1rem;
    }
/* 
=================================
products and services stops here
=================================
*/
/* 
=================================
team starts starts here
=================================
*/
.img-content{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin: -1rem 0 1rem 1rem;
    background-color: #fff;
    box-shadow: 4px 3px 5px gray;
    border-radius: 10px;
    padding-bottom: 6rem;
    height: 2rem;
}
    .img-content h4{
    color: #000;
    padding: 6px 4px 0 6px;
    margin-top: 8rem;
}
    .img-content p{
    color:#000;
    padding-bottom:10px ;
}
    .carousel-cards h4{
        text-align: center;
        color: #000;
        padding: 2rem;
    }
    .carousel-cards h2, .carousel-cards p{
        margin: 0  0 1rem 2rem;
    }
    .sliding-cards .my-card1, .sliding-cards .my-card2, .sliding-cards .my-card3, .sliding-cards .my-card4 {
        height: 15rem;
        margin:0 1rem 0 2rem;
        padding-right: 1rem ;
        border-radius: 10px;
    }
    .carousel-item .my-card1, .carousel-item .my-card2, .carousel-item .my-card3, .carousel-item .my-card4 {
        height: 15rem;
        margin-left: 2rem;
        margin-right:1rem ;
        padding-right: 1rem ;
        border-radius: 10px;
    }
    .carousel-item h2, .carousel-item p {
        margin-left: 1.5rem;
    }
    .carousel-item h2{
        padding-top: 1.5rem;
    }
    .carousel button .carousel-control-prev-icon, .carousel button .carousel-control-next-icon  {
        background-color:grey
    }
    .my-card1 h2, .my-card2 h2, .my-card3 h2, .my-card4 h2{
        margin-top: 1.5rem;
    }
    .card h2{
        color: black;
    }
    .card{
        display: flex;
        flex-direction: row;
        margin-bottom: 8rem;
        margin-left:7rem;
        background-color:transparent;
        border: none;

    }
    .card img{
        height: 18rem;
        width: 17rem;
        border-radius: 50%;
        margin-left: .5rem;
        padding-left: .1rem;
    }
    .all-the-cards{
        margin: 4rem 0 4rem 0;
    }
    a{
      text-decoration: none;
      font-size: 1.3rem;
      color: #fff;
    }
    img {
            max-width: 100%;
            height: auto; 
            display: block; 
            margin: 0 auto; 
        }
/* 
=================================
team stops here
=================================
*/

/* media queries*/
/* Extra small devices (phones, 600px and down) */
@media screen and (max-width: 600px) {
    .about-us-container{
    overflow: hidden;
}
    .homepage{
    min-height: 100vh;
    width: 100%;
    background-color:black;
    background-size: cover;
    position: relative;
    top: -4rem;
    left: 0;   
    }
    article h1{
    font-size: 3rem;
    } 
    .about-pesamoni{
    height: 22rem;
    text-align: center;
    }
      /* strategy */
    .strategy{
        display: flex;
        flex-direction: column;

      }
    /* .strategy-content{
          height: 20rem;
          width: auto;
          margin:2rem .5rem 0 .9rem;
    }
    .strategy-content p{
        text-align: center;
    } */
    .e-learning img{
        max-width: 100%;
        height: auto; 
        display: block; 
        margin: 0 auto;
    }
    .business-and-services{
        display: flex;
        flex-direction: column;
    }
    .heading-content{
        height: 35rem;
        margin-right: 1rem;
        margin-left: 1rem;
    }
    .heading-content2, .heading-content3{
        height: 22rem;
        margin-right: 1rem;
        margin-left: 1rem;
    }
    .heading-content p, .heading-content2 p, .heading-content3 p{
        padding: 1.5rem;
    }
    .e-learning img, .payments img, .software-development img{
        width: 100%;
        padding-right: 2rem;
        margin-left: 1rem;
    }
     /* team */
    .card{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin: 2.9rem;
    }
    .card .my-card1{
        height: 25rem;
    }
    .card .my-card4{
        height: 25rem;
    }
    .card .img-content{
        
        width: 20rem;
        margin:auto;
        margin-left:-1rem;
    }


}
/* Small devices (portrait tablets and large phones, 600px and up) */
@media screen and (min-width: 600px) {
    .about-us-container{
    overflow: hidden;
    }
      .about-pesamoni p{
        font-size: 1.5rem;
    }
      /* strategy */
      .strategy{
          display: flex;
          flex-direction: column;
          justify-content: flex-start;
          gap: 2rem;
      }
      .strategy-content{
          margin-top:1rem ;
    }
        .strategy-content p{
        padding: 1.5rem;
        margin-top: -4rem;
        font-size: 1.5rem;
    }
        .strategy-content h2{
        margin-top: .8rem;
    }
    .strategy-img{
        padding-right: 10rem;
    }
      
    /* Products and services */
    .business-and-services{
        display: flex;
        flex-direction: column;
    }
    .heading-content{
        height: 18rem;
    }
    .heading-content2, .heading-content3{
        height: 12rem;
    }
    .e-learning img, .payments img, .software-development img{
        width: 100%;
    }
    /* team */
    .team-img{
        display: grid;
        grid-template-columns:1fr 1fr;
        gap: 1rem;
    }
    /* .strategy img{
        padding: 1.5rem;
    } */
    

}
/* Small devices (portrait tablets and large phones, 600px and up) */
@media screen and (min-width: 600px) {
    .about-us-container{
    overflow: hidden;
    }
      .about-pesamoni h1{
          text-align: center;
      }
      .about-pesamoni p{
        font-size: 1rem;
      }
      /* strategy */
      .strategy{
          display: flex;
          flex-direction: column;
          gap: 2rem;
      }
        .strategy-content p{
        padding: 1.5rem;
        margin-top: -4rem;
        font-size: 1.2rem;
    }
        .strategy-content h2{
        margin-top: .8rem;
    }
        .strategy img{
        width: 100%;
    }
}
/* Large devices (laptops/desktops, 992px and up) */
@media screen and (min-width: 992px) {
        .about-us-container{
            overflow: hidden;
    }
        /* nav h1{
            display: none;
      } */
        .about-pesamoni p{
            font-size: 1.2rem;
      }
      /* strategy */
        .strategy{
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 2rem;
      }
        .strategy-content p{
            padding: 1.5rem;
            margin-top: -4rem;
            font-size: 1.2rem;
    }
        .strategy-content h2{
            margin-top: .8rem;
    }
        .strategy img{
            width: 100%;
    }
        .business-and-services{
            display: grid;
            grid-template-columns: 1fr 1fr;
    }
        .heading-content, .heading-content2{
            height: 20rem;
    }
         .heading-content3{
            height: 12rem;
    }
        .e-learning img, .payments img, .software-development img{
            width: 100%;
    }

}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media screen and (min-width: 1200px) {
        .about-us-container{
            overflow: hidden;
    }
        .about-pesamoni p{
            font-size: 1rem;
      }
      /* strategy */
        .strategy{
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 2rem;
      }
        .strategy-content p{
            padding: 2rem;
            margin-top: -4rem;
            font-size: 1rem;
    }
        .strategy-content h2{
            margin-top: 1rem;
    }
        .strategy img{
            width: 100%;
    }
        .business-and-services{
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
    }
        .heading-content, .heading-content2, .heading-content3{
            height: 28rem;
    }
        .heading-content{
        margin-top: 1.5rem;
    }
        .heading-content h3, .heading-content2 h3, .heading-content3 h3{
        padding-top: 1rem;
    }
        .heading-content p, .heading-content2 p, .heading-content3 p{
        font-size: 1rem;
    }
        .e-learning img, .payments img, .software-development img{
            width: 100%;
    }
    .software-development img{
            height: 230px;
        }
    /* team */
        .team-img{
            display: grid;
            grid-template-columns:1fr 1fr 1fr 1fr;
            gap: 1rem;
        }
        .strategy img{
            padding: 1.2rem;
        }
}

</style>