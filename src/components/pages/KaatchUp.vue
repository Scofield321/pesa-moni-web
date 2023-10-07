<template>
    <div class="kaatch-container">
        <div class="home-wrapper">
        <nav>
           <h1>KAATCH-UP</h1>
                <router-link to="/">Home</router-link>
                <!-- <router-link to="/pesamoni">Pesamoni</router-link> -->
                <router-link to="/cashchat">CashChat</router-link>
                <router-link to="/education">Education</router-link>
                <router-link to="/kaatchup">Kaatch-Up</router-link>
                <router-link to="/about-us">About Us</router-link>
        </nav>
          <div class="home-content">
            <div class="home-img">
                  <img src="https://images.pexels.com/photos/3727464/pexels-photo-3727464.jpeg?auto=compress&cs=tinysrgb&w=620&h=750&dpr=1" alt="">
            </div>
            <div>
                <article>
                    <!-- <img src="https://play-lh.googleusercontent.com/Y8skkGEOTjgsRmb1fWavoBNavrPv5hXmoQe1Xg0z0LegJVc6GDoetFg_vji5V5rBaA=w240-h480-rw" alt=""> -->
                    <h2 class="colored-h2">Fundraise.Socialize</h2>
                    <p>Kaatch-Up has solved all the hassles of fundraising, entertainment, commucation and the way we make money, make money by status views.</p>
                    <img src="https://images.pexels.com/photos/2608517/pexels-photo-2608517.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
                    <!-- <button>Get started <span><i class="fa fa-arrow-right" aria-hidden="true"></i></span></button> -->
                </article>
                    <!-- <button>Learn more</button> -->
            </div>               
            <button class="contact-us-btn" @click="contactUs"> <i class="fa fa-envelope-o" aria-hidden="true"></i> Contact us</button>
            </div>
            <!-- wave animation starts here -->
            <section class="wavy">
              <div class="wave wave1"></div> 
              <div class="wave wave2"></div> 
              <div class="wave wave3"></div> 
              <div class="wave wave4"></div> 
            </section>
            <!-- wave aniamtion ends here -->
            
        </div>   
        <!-- other content starts from here -->
      <section class="other-content">
        <h2>Fundraise from anywhere in the World, with just few clicks</h2>
          <div class="elearning-distance-learning">
              <img class="fund-rasing-img" src="https://i.ytimg.com/vi/77fzoKmfoR4/maxresdefault.jpg" alt="">
              <div class="img-text">
                  <h2>Kaatc-Up fundraising</h2>
                  <p>
                      Kaatch-Up softens the process and all the hassels involved in raising funds from Friends, Family and everyone wherever in the world. You can raise funds for your business,occassions like baby shower, wedding, introduction and so many others.
                  </p>
              </div>
          </div>
          <h2>Keep in touch with all your folks and family.</h2>
          <div class="digital-wallet">
              <div class="img-text1">
                  <h2>Kaatch-Up we Catch up</h2>
                  <p>
                      Kaatch-Up enables you to connect with all the friends, family, and stranger, just don't be bored when you have internet, just download our KaatchUp app from the playstore and the appstore, start socialising with ease, have some fun with buddies. .
                  </p>
              </div>
              <img src="https://images.pexels.com/photos/697244/pexels-photo-697244.jpeg?auto=compress&cs=tinysrgb&w=500&h=400&dpr=1" alt="">
          </div>
          <h2>Keep the smile on your face with all the vibes and have fun.</h2>
          <div class="elearning-distance-learning">
              <img src="https://images.pexels.com/photos/7148443/pexels-photo-7148443.jpeg?auto=compress&cs=tinysrgb&w=500&h=400&dpr=1" alt="">
              <div class="img-text">
                  <h2>Vibes avenue</h2>
                  <p>
                    Create Vibes with Kaatch-Up in form of Video, Text, Images and much more, then you can browse through all the vibes your friends and everyone has posted, have fun with the Vibe avenue as you in touch with your favorite people.
                  </p>
              </div>
          </div>
          <h2>Communcate with everyone via video calls and audio from anywhre</h2>
          <div class="digital-wallet">
              <div class="img-text1">
                  <h2>Chat, Video call & Voice Call</h2>
                  <p>
                      We have the most encrypted and secure communication platform, we have the End to End Encryption (E2EE), all your data is secure, just have fun and communicate all over the world with anyone at an Instant messaging.
                  </p>
              </div>
              <img src="https://images.pexels.com/photos/5956949/pexels-photo-5956949.jpeg?auto=compress&cs=tinysrgb&w=500&h=400&dpr=1" alt="">
          </div>
      </section >
      <h2>All you need to know about Kaatch in one place</h2>
      <section class="kaatchup-testimonies">
          <div class="testimonies-content">
              <h2>Features of Kaatch-Up</h2>
              <p>
                  Most features explained in just one video, you can see all the amazing features which are in the system. Make all the fundraising, chatting, calling in just few steps, it's and end-to-end system all your data is protected and your direct messages are just between you and the person you're chatting with. 
              </p>
          </div>
          <div>
              <video src="./video/kaatchup-video.mp4" width="640" height="480" controls></video>
          </div>
      </section>
      <my-footer></my-footer>
    </div>
  </template>
  
  <script>
  import MyFooter from './footer/MyFooter.vue';
  export default {
    components:{
      MyFooter,
    },
    methods:{
        contactUs(){
          this.$router.push('/contact-us')
        }
      }
  }
  </script>
  
  <style scoped>
  .kaatch-container{
    background-color: #428bca;
    overflow-x: hidden;
  }
  .home-wrapper{
        background-image: linear-gradient(45deg,#1a84c6,#1a84c6);
        background-attachment: fixed;
        background-size: 300% 300%;
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
    nav{
        display: flex;
        justify-content: flex-start;
        align-items: center;
        position: absolute;
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
        color: #f3874f;
      }
      nav h1{
        margin: 0 6rem 0 2rem;
        color: #fff;
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
    .home-img{
      margin: 6rem 2rem 3rem 3rem;
    }
    article h1{ 
        font-size: 1.5rem;
    }
    article h2{
        width: 23rem;
        font-size: 2.0rem;
        font-style: oblique;
        padding: 1rem 1rem 0 1rem;
    }
    article p{
        width: 23rem;
        padding: 0 2rem;
    }
    article{
        margin: 6rem  8rem;
        padding-bottom: 2rem;
        color: #000; 
        background-color: #fff;    
        top: 0;
        height: 25rem;
    }
    .colored-h2{
      color: #000;
    }
    article img{
      height: 14rem;
      width: 22.95rem;
      padding: 2rem 0 0 2rem;
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
    .wavy{
      margin-top: 25rem;
    }
    .wavy .wave{
        position: absolute;
        bottom: -2rem;
        left: 0;
        width: 100vw;
        height: 45px;
        background-position: center;
        background-image: linear-gradient(45deg, #1a84c6, #56b4ee, #acd8f3), url(../../assets/pesateam/wave.png);
        background-size: 1000px 100px;
        margin-bottom: 1rem;
        padding-top: 2rem;
    }
    .wavy .wave.wave1{
        animation: animate 10s linear infinite;
        z-index: 1000;
        opacity: 1;
        animation-delay: 0s;
        /* bottom: 0; */
    }
    .wavy .wave.wave2{
        animation: animate2 5s linear infinite;
        z-index: 999;
        opacity: 0.5;
        animation-delay: -5s;
        bottom: 5px;
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
  .home-page h1{
      position: fixed;
      top: 0;
      left: 0;
  }

  .other-content h2, .other-content p{
      color: white;
  }
  .other-content h2{
    margin-top: 1rem;
  }
  .elearning-distance-learning{
      background-color: whitesmoke;
  }
  .elearning-distance-learning p, .elearning-distance-learning h2  {
    color: black;
  }
  .elearning-distance-learning, .digital-wallet{
      display: grid;
      grid-template-columns: 1fr 2fr;
  }
  .elearning-distance-learning{
    display: grid;
    grid-template-columns: 2fr 1fr;
  }
  .elearning-distance-learning img, .digital-wallet img{     
      margin: 6rem 2rem 3rem 10rem;
  }
  .elearning-distance-learning img{
    width: 50rem;
    margin-left: 0;
    height: 25rem;
  }
  .kaatchup-connection{
      height: 25rem;
      width: 20rem;
  }
  .img-text{
      margin: 6rem 0 0 -2.0rem;
      background-color: #1a84c6;
      color: #fff;
      height: 25rem;
  }

  .testimonies-content h2, .testimonies-content p{
    color: #fff;
  }
  .img-text p{
    padding: 2rem;
    color: #fff;
  }
  .img-text h2{
    text-align: center;
    margin-top: 1rem;
    color: #fff;
  }
  .digital-wallet img{
      margin: 6rem  3rem 3rem 0;
      width: 50rem;
      margin-left: 0;
      height: 25rem;

  }
  .img-text1{
      margin: 6rem 1rem 0 2rem;
      background-color: #fff;
      color: #000;
      height: 25rem;
      width: 29rem;
  }
  .img-text1 p, .img-text1 h2{
    color: #000;
  }
  .img-text1 h2{
    padding: 2rem;
  }
  .img-text1 p{
    padding: 0 1rem;
  }
  /* 
  ===============================
  other content stops here
  ===============================
  */
  .testimonies-content{
    margin: 7rem -2.0rem 0 2rem;
    background-color: #1a84c6;
    color: #fff;
    height: 26rem;
  }
  .testimonies-content h2{
    text-align: center;
    padding-top: 4rem;
  }
  .testimonies-content p{
    padding: 2rem;
  }
  .kaatchup-testimonies{
      display: grid;
      grid-template-columns: 1fr 1fr ;
      background-color: whitesmoke;
  }
  .kaatchup-testimonies video{
      margin: 3rem;
  }
  h2{
    text-align: center;
    color: #fff;
    padding-top: 2rem;
    font-weight: 500;
  }
  /* 
  ===============================
  cashcaht-testimonies stops here
  ===============================
  */
  
  </style>