<template>
  <div class="cashchat-container">
    <div class="home-wrapper">
        <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-blue">
    <div class="container-fluid">
        <h1 class="navbar-brand">CASHCHAT</h1>
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
            <div class="home-img">
                  <img src="https://images.pexels.com/photos/7433822/pexels-photo-7433822.jpeg?auto=compress&cs=tinysrgb&w=650&h=650&dpr=1" alt="home image">
            </div>
            <div class="phone">
                <div class="screen">
                    <div class="the-article">
                        <article>
                            <h2>Unlimited services with CASHCHAT</h2>
                            <p class="home-p">Make your dreams come true when using CASHCHAT services, we have the chat systems, financial systems, investment plan, just few clicks away</p>
                            <a href="https://play.google.com/store/apps/details?id=com.app.cashchat&pcampaignid=web_share"><img src="https://res.cloudinary.com/african-centre-for-peace-and-human-life/image/upload/v1526381204/Pesamoni/get_it.png" alt="playstore-logo"></a>
                            <img  src="https://images.pexels.com/photos/8834116/pexels-photo-8834116.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
                        </article>
                    </div>
                </div>
                    <!-- <button>Learn more</button> -->
            </div>               
            <button class="contact-us-btn" @click="contactUs"> <i class="fa fa-envelope-o" aria-hidden="true"></i> Contact us</button>
            </div>  
            <section class="wavy">
                <div class="wave wave1"></div> 
                <div class="wave wave2"></div> 
                <div class="wave wave3"></div> 
                <div class="wave wave4"></div> 
            </section>        
        </div>   
    <section class="all-the-cards">
      <!--  start of cards slider -->
      <div class="carousel-cards">
        <h2>About CachChat</h2>
                </div>
                <div id="carouselExampleControlsNoTouching" class="carousel slide" data-bs-touch="false" data-bs-interval="false">
                <div class="carousel-inner">
                <div class="carousel-item active">
                    <div class="row" >
                        <div class="col-sm-6">
                            <div class="card">
                                <div class="my-card1 d-block w-100">
                                    <h2>CashChat community.</h2>
                                    <p>
                                      Cash Chat Limited is a financial technology, Social media and 
                                      Digital Advertising Company with over 500,000 users on both web & Mobile 
                                      App in sub-Saharan region.
                                    </p>
                                </div>
                            </div>
                        </div>
                        <div class="col-sm-6">
                            <div class="card">
                                <div class="my-card2 d-block w-100">
                                    <h2>CashChat services.</h2>
                                    <p>
                                      Cash Chat started in 2018 with a vision of transforming businesses to dominate digital world with new technology tools which can help grow different 
                                      levels of business and industries.
                                    </p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                </div>
                    <div class="carousel-item">
                    <!-- <img src="..." class="d-block w-100" alt="..."> -->
                    <div class="row">
                        <div class="col-sm-6">
                            <div class="card">
                                <div class="my-card4 d-block w-100">
                                <h2>How it solves the problems?</h2>
                                <p>
                                  By engaging an audience through our platform, we 
                                  have an ability to generate awareness, widen our client’s potential reach-out 
                                  with in their target market.
                                </p>                         
                            </div>
                            </div>
                        </div>
                        <div class="col-sm-6">
                            <div class="card">
                                <div class="my-card3 d-block w-100">
                                <h2>Customer target.</h2>
                                <p>
                                  Our clients are primarily in sub-Saharan region looking to reach out to their 
                                  customers through our platform. We help our clients target.
                                </p>
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
    <section class="other-content">
        <h2>Learning made easy with e-learning</h2>
        <div class="elearning-distance-learning1">
            <img src="https://s3.us-east-1.amazonaws.com/victoria-university-elearning/website/images/intro_section_banner/487728ba-e0a1-4c7e-877f-df6e42e1ad86.jpg" alt="">
            <div class="img-text1">
                <h2 class="e-learnign-h2">E-Learning and Distance learning.</h2>
                <p>
                    CashChat has managed to scale eLearning live video streaming 
                    which can help schools, universities to teach and exchange live 
                    video with students while learning anywhere using the mobile 
                    app at a free cost.
                </p>
            </div>
        </div>
        <h2 class="gapped-h2">Make all payments and transactions with digital Wallet</h2>
        <div class="elearning-distance-learning">
            <div class="img-text">
                <h2>Digital Wallet.</h2>
                <p>
                    CashChat has wallet which can help the users make easy 
                    payments anywhere in the sub Saharan region, this has also 
                    been scaled for business payments to receive payments via 
                    Business API for payments and collections.
                </p>
            </div>
            <div class="payments-img">
                <img src="https://images.pexels.com/photos/196656/pexels-photo-196656.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
            </div>
        </div>
        <h2 class="gapped-h2">Run any business Ads via our platform</h2>
        <div class="elearning-distance-learning1">
            <div class="payments-img1">
                <img src="https://images.pexels.com/photos/5077038/pexels-photo-5077038.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
            </div>
            <div class="img-text1">
                <h2>CashChat Ads</h2>
                <p>
                    CashChat is the only digital advertising platform that serves 
                    digital Adverts across East African region in form of Text, 
                    Ad Banners, and Interactive video. CashChat connects you to 
                    more engaging audience to grow any business for customer 
                    retention, new business sales and sales growth. Business make 
                    their budgets and target content on the status for engagement 
                    at low extremely low cost.
                </p>
            </div>
        </div>
        <h2>Save more, enjoy more with our calls</h2>
        <div class="elearning-distance-learning">
            <div class="img-text">
                <h2>Video calls & Voice Calls.</h2>
                <p>
                    CashChat has also succeed and eased the way we 
                    communicate with our friends and family, any person 
                    using CashChat can make unlimited video and Voice 
                    calls in HD format.
                </p>
            </div>
            <div class="payments-img1">>
                <img src="https://images.pexels.com/photos/4491461/pexels-photo-4491461.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
            </div>
        </div>
        <h2 class="gapped-h2">Stay connected with everyone affordably</h2>
        <div class="elearning-distance-learning1">
            <div class="payments-img1">>
                <img src="https://images.pexels.com/photos/1267697/pexels-photo-1267697.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
            </div>
            <div class="img-text1">
                <h2 class="padded-h2">Unlimited group chats and Personal private messaging</h2>
                <p>
                    CashChat has also empowered all those who want easy and secure
                    communication in personal chats at free cost.
                </p>
            </div>
        </div>
        <h2 class="gapped-h2">Invest in all your stocks and bonds in few clicks</h2>
        <div class="elearning-distance-learning">
            <div class="img-text">
                <h2>Investment Plan</h2>
                <p>
                    CashChat partnered with Altx Africa to allow users invest 
                    their money to do equity and stock trading this include 
                    Exchangable Trade funds(ETFs), Bonds and shares. This will 
                    allow users to earn atleast 14-16% per annum for their 
                    investment.
                </p>
            </div>
            <div class="payments-img1">>
                <img src="https://images.pexels.com/photos/8353796/pexels-photo-8353796.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
            </div>
        </div>
    </section >
    <h2 class="testimony-h2">Testimonies</h2>
    <section class="cashchat-testimonies">
        <div class="demonstration-vid">
            <video src="./video/cashchat-video-1.mp4" width="640" height="480" controls></video>
        </div>
        <div class="testimonies-content">
            <h2>Our customer enjoying CashChat calls</h2>
            <p>
                Don't be left out with these amazing offers given by our application, make phones calls, video chats, and all other amazing things, just go download our app from the Google Play Store and start enjoying too.
            </p>
        </div>
    </section>
    <h2 class="modified-h2">Step by step guideline about our system</h2>
    <section class="cashchat-testimonies">       
        <div class="testimonies-content1">
            <h2>All what you need to know about CashChat</h2>
            <p>
                A detailed video of CashChat, from all the servces to benefits. Change the way you think of social media, it's not only for having fun but also for earning.  
            </p>
        </div>
        <div class="demonstration-vid">
            <video src="./video/caashchat-description.mp4" width="640" height="480" controls></video>
        </div>
    </section>
    <my-footer></my-footer>
  </div>
</template>

<script>
import MyFooter from './footer/MyFooter.vue';
// import NavBar from './NavBar.vue';
export default {
  components:{
    MyFooter,
    // NavBar
  },
  methods:{
      contactUs(){
        this.$router.push('/contact-us')
      }
    }
}
</script>

<style scoped>
.cashchat-container{
  background-color: whitesmoke;
  overflow: hidden;
}
.navbar-dark{
  background-color: #1a84c6;
}
.home-wrapper{
        background-image: linear-gradient(45deg,#662d91, #662d91 );
        background-attachment: fixed;
        background-size: 200% 200%;
        animation: color 17s ease-in-out infinite;
        position: relative;
        height: 100vh;
        margin-top: -5rem;  
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
    a{
      text-decoration: none;
      font-size: 1.3rem;
      color: #fff;
    }
    .home-content{
      display: grid;
      grid-template-columns: 1fr 1fr;
      margin-top: 4rem;
      width: 100vw;
    }
    .home-img{
      margin: 6rem 2rem 3rem 3rem;
    }
    article h1{ 
        font-size: 1.5rem;
    }
    article h2{
        /* width: 23rem; */
        font-size: 2.0rem;
        font-style: oblique;
        padding: 1rem 2rem 0 ;
        color: #000000;
    }
    article p{
        width: 23rem;
        padding: 0 2rem;
    }
    article{
        margin: 6rem;
        color: #000000;
        background-color: #fff;     
        top: 0;
        height: 27rem;
        border-radius: 5px;
    }
    article img{
      height: 11rem;
      width: 22.95rem;
      padding-left: 2rem;
    }
    article a img{
        height: 3rem;
        width: 10rem;
        padding-bottom: 1rem;
    }
    .contact-us-btn{
        margin: 3rem;
        padding: 10px 30px;
        border: none;
        border-radius: 5px;
        background-color: #8CC63F;
        position: fixed;
        right: 0;
        bottom: 0;
        z-index: 9999;
        color: white;
    }
    .contact-us-btn:hover{
        cursor: pointer;
        background: #f3874f;
    }
    article button{
        padding: 10px 30px;
        border: none;
        border-radius: 5px;
        background-color: #f3874f;
        position: absolute;
        z-index: 9999;
    }
    article button:hover{
        cursor: pointer;
        background: #f3874f;
        color: white;
    }
    .wavy .wave{
        position: absolute;
        bottom: -2rem;
        left: 0;
        width: 100vw;
        height: 45px;
        background-position: center;
        background-image: linear-gradient(45deg,#662d91,#a46ad1, #d9c2ec ), url(../../assets/pesateam/wave.png);
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
    .forth-section{
        width: 100vw;
        height: 60vh;
        margin-top: 2rem;
        margin-bottom: 3rem;
    }
    .forth-section h2, .forth-section p {
        margin: 0  0 1rem 2rem;
    }
    .carousel-cards h2{
        text-align: center;
        color: #662d91;
        padding-top: 2rem;
    }
    .carousel-cards h2, .carousel-cards p{
        margin: 0  0 1rem 2rem;
    }
    .sliding-cards{
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 10px;
    }
    .carousel-item .my-card1, .carousel-item .my-card2, .carousel-item .my-card3, .carousel-item .my-card4 {
        width: 35rem;
        height: 15rem;
        background-color: rgb(245, 204, 211);
        padding-right: 1rem ;
        border-radius: 10px;
    }
    .carousel-item .my-card2{
        background-color: rgb(245, 245, 173);
    }
    .carousel-item .my-card3{
        background-color:rgb(141, 247, 247);
    }
    .carousel-item .my-card4{
        background-color: rgb(195, 195, 241);
    }
    .carousel-inner{
        width: 100vw;
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
    .carousel-control-prev{
        color: black;
    }
    .sliding-cards .my-card2{
        background-color: rgb(245, 245, 173);
        margin: 0 2rem 2rem 0;
        
    }
    .sliding-cards .my-card3{
        background-color:rgb(141, 247, 247);

    }
    .sliding-cards .my-card4{
        background-color: rgb(195, 195, 241);
        margin: 0 2rem 1rem 0;
    }
    .my-card1 h2, .my-card2 h2, .my-card3 h2, .my-card4 h2{
        margin-top: 1.5rem;
    }
    .sliding-cards p{
        font-size: 15px;
    }
    .card p:before{
        content:"• ";
        padding: 5px;
        font-size: 20px;
    }
    .card h2{
        color: black;
    }
/* 
===============================
other content starts here
===============================
*/
.other-content{
    margin-top: 4rem;
}
.other-content h2, .other-content p{
    color: #662d91;
}
.elearning-distance-learning, .digital-wallet, .digital-wallet1 {
    display: grid;
    grid-template-columns: 1fr 1fr;
}
.elearning-distance-learning img{
    width: 30rem;
    margin: 6rem 2rem 3rem 10rem;
}
.img-text{
    margin: 6rem 8rem ;
    /* margin-top: 8rem; */
}
.img-text1{
    margin: 4rem 8rem;
}
.elearning-distance-learning1, .elearning-distance-learning{
    display: grid;
    grid-template-columns: 1fr 2fr;
    height: 50vh;
    margin: 5rem 0 10rem -1rem;
}
.elearning-distance-learning1{
    display: grid;
    grid-template-columns: 2fr 1fr;   
}
.elearning-distance-learning1 img, .elearning-distance-learning img{
    height: 28rem;
    margin-right: 0;
    width: 48rem;
}
.elearning-distance-learning img{
    width: 50rem;
    margin-left: 1rem;
    height: 27rem;
}
.elearning-distance-learning .img1-text1{
    margin-top: 4rem;
}
.img-text1, .img-text{
    background-color: #8CC63F;
    margin-top: .5rem;
    margin-right: 0;
    height: 28rem;
    width: 30rem;
}
.img-text1{
    margin: 0 0 0 -3.4rem;
    width: 32rem;
    height: 28rem;
}
.img-text{
    margin-top: 3.4rem;
    margin-left: 1rem;
}
 .img-text h2, .img-text p, .img-text1 h2, .img-text1 p {
    color: #fff;
    padding: 2rem;
    font-weight: 400;
}
.img-text h2, .img-text1 h2{
    padding: 1rem;
    text-align: center;
    font-weight: 500;
}
.elearning-distance-learning{
    color: #fff;
    text-align: center;
}
.elearning-distance-learning img{
    margin-top: 2rem;
    height: 28rem;
}
.elearning-distance-learning1 img{
    margin-right: -3rem;
}
.modified-h2{
    padding-top: 3rem;
    color: #662d91;
}
.gapped-h2{
    padding-top:3rem;
    color:#662d91;
}
.payments-img{
    margin-top: 1.4rem;
}
/* 
===============================
other content stops here
===============================
*/
.cashchat-testimonies{
    display: grid;
    grid-template-columns: 1fr 1fr ;
}
.cashchat-testimonies video{
    margin: 3rem;
    margin-left: 0;
}

.testimonies-content, .testimonies-content1{
    color: #fff;
    margin: 6.5rem 0 0 -2rem;
    background-color: #8CC63F;
    height: 26.5rem;
}
.testimonies-content1{
    margin-left: 0;
    padding: 2rem
}
.testimonies-content h2{
    padding: 3rem;
}
.testimonies-content p{
    padding: 0 2rem;
}
h2{
    text-align: center;
}
.guildline-vid{
    margin-left: 1rem;
}

/* media queries*/ 
/* Extra small devices (phones, 600px and down) */
@media screen and (max-width: 600px) {
    .cashchat-container{
        overflow: hidden;
    }
    .home-content{
      display: flex;
      flex-direction: column;
    }
    .home-img img {
    display: none;
  }
    article{
      width: 93%;
      padding: 1rem;
      height: 35rem;
      margin: 1rem;
      margin-top: -3rem;
  }
  article h2, article p{
      margin-left: -1rem;
  }
    article img{
      width: 20rem;
      margin-left:-1rem;
  }
    article a img{
      height:5rem;
      width: 13rem;
      margin: auto;
      margin-left: 2.5rem;
  }
  /* Sliding cards starts here */
    .sliding-cards{
        display: flex;
        flex-direction: column;
        gap: 3rem;
    }
    .card{
        padding: 1rem;
        padding-right: 1rem;
    }
    .card{
        height: 21rem;
    }
    .my-card2, .my-card3{
        height: 23rem;
    }
    .elearning-distance-learning, .elearning-distance-learning1{
        display: flex;
        flex-direction: column;
        height: 35rem;
    }
    .elearning-distance-learning h2{
    margin-left: -3rem;
}
    .elearning-distance-learning1{
    background-color: transparent;
    height: 35rem;
}
     .elearning-distance-learning1 p{
    color: black;
}
    .elearning-distance-learning1 img{
    width: 25rem;
    padding-bottom: 2rem;
    height: 20rem;
    margin-right: 2rem;
}
    .img-text1, .img-text{
        width: 25rem;
        /* margin-bottom: 3rem; */
    }
    .img-text1{
        width: 30rem;
    }
    .elearning-distance-learning1 img{
        width: 26.8rem;
    }
    .elearning-distance-learning1 h2{
    margin-left: -1rem;

}
    .img-text1 p{
        margin-left: 5rem;
        margin-right: 2rem;
        color: #fff;
    }
    .img-text p{
        margin-right: 1rem;
    }
    .img-text1 h2{
        padding-left: 5rem;
    }
    .e-learnign-h2{
        margin-right: 3rem;
    }
    .home-p{
        margin-right: 2rem;
    }
    .elearning-distance-learning img{
        margin-bottom: 3rem;
    }
    .elearning-distance-learning img, .digital-wallet img{
    width: 100%;
}
    .elearning-distance-learning p, .elearning-distance-learning1 p{
    text-align: center;
}
    .img-text:nth-child(1){
        order: 2;
    }
    .img-text:nth-child(2){
        order: 1;
    }
    .payments-img img, .payments-img1 img{ 
        max-width: 100%;
        height: auto; 
        display: block;
        margin: 0 auto;
    }
    .cashchat-testimonies {
    display: flex;
    flex-direction: column;
    margin-top: -3rem;
    margin-bottom: 3rem;
}
    .demonstration-vid{
        width: 25rem;
    }
    .testimonies-content{
        margin-top: -1.5rem;
    }
    .testimonies-content1:nth-child(1){
        order: 2;
    }
    .testimonies-content1:nth-child(2){
        order: 1;
    }
    .guildline-vid{
        max-width: 100%;
        overflow: hidden;
    }
    video{
        width: 100%;
        height: auto;
    }
    .testimonies-content p{
        margin-left: 3rem;
        text-align: center;
    }
    .testimonies-content1{
        height: 15rem;
        margin-top: -1rem;
    }
    .testimonies-content1 h2{
        margin-bottom: 2rem;
    }
    .testimonies-content1 p{
        text-align: center;
    }
    .gapped-h2{
        margin-top: -8rem;
    }
    .testimony-h2{
        margin-top: 5rem;
    }
    .padded-h2{
        margin: 1rem;
    }
}

</style>