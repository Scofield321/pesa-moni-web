<template>
  <div class="education-container">
    <!-- <button class="menu-toggle" v-if="!showMenu" @click="toggleMenu"><i class="fa fa-bars" aria-hidden="true"></i>
</button> -->
    <!-- <nav v-show="showMenu">
               <h1>EDUCATION</h1>
               <router-link to="/">Home</router-link>
               <router-link to="/cashchat">CashChat</router-link>
               <router-link to="/education">Education</router-link>
               <router-link to="/kaatchup">Kaatch-Up</router-link>
               <router-link to="/about-us">About Us</router-link>
    </nav> -->
    <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">EDUCATION</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav me-auto mb-2 mb-md-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="/">Home</a>
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
    <section class="education-page">
          <article class="education-home-content">
              <h1>Pesamoni and Education</h1>
              <h2>Inspiring every kind of mind.</h2>
              <h3>Everyone has their own way of learning and expressing creativity. As Pesamoni community and resources empower every kind of educator and every kind of student to learn, create, and define their own success. Let’s move the world forward through our education platforms.</h3>
              <button class="contact-us-btn" @click="contactUs"> <i class="fa fa-envelope-o" aria-hidden="true"></i> Contact us</button>
          </article>
    </section>
      <section class="main-content">
        <h1>Learning Management Systems</h1>
          <div class="main-content-img">
              <div>
                  <img src="https://images.pexels.com/photos/4145347/pexels-photo-4145347.jpeg?auto=compress&cs=tinysrgb&w=450&h=400&dpr=1" alt="">
                  <div class="card1">
                      <h4>Primary Schools </h4>
                      <p>Let your little kids learn from home and you can guide them better</p>
                  </div>
              </div>
              <div>
                  <img src="https://images.pexels.com/photos/4144224/pexels-photo-4144224.jpeg?auto=compress&cs=tinysrgb&w=450&h=400" alt="">
                  <div class="card2">
                      <h4>Secondary Schools </h4>
                      <p>We have a well tested Learning Management system for Secondary Schools</p>
                  </div>
              </div>
              <div>
                  <img src="https://images.pexels.com/photos/6084261/pexels-photo-6084261.jpeg?auto=compress&cs=tinysrgb&w=450&h=400&dpr=1" alt="">
                  <div class="card3">
                      <h4>Higher Education </h4>
                      <p>Our systems has been used by Victoria University for years now and it was approved by National Council for Higher Education</p>
                  </div>
              </div>
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
    data(){
    return{
        // showMenu: true,
        // showToggleButton: true
      }
    },
    methods:{
      contactUs(){
        this.$router.push('/contact-us')
      },
    //   toggleMenu(){
    //       this.showMenu = !this.showMenu
    //       this.showToggleButton = false;
    //   }
    }
  }
</script>

<style scoped>
/* 
=======================
Home page starts here 
=======================
*/
    .education-container{
        background-color: whitesmoke;
        min-height: 100vh;
        overflow: hidden;
    }
    /* nav{
        display: flex;
        justify-content: flex-start;
        align-items: center;
        position: absolute;
        z-index: 99999;
        height: 4rem;
        margin-top: 1rem;
        margin-bottom: 3rem;
        width: 100%;        
      }
    nav a{
        padding: 1rem;
        color: #1a84c6;
        text-decoration: none;
        font-size: 1.3rem;
      }
    nav a:hover{
        color: #f3874f;
      }
    nav h1{
        margin: 0 6rem 0 2rem;
        color:#1a84c6;
      } */
    .education-page{
        background-color: transparent;
        height: 100vh;
}
    .education-page h1{
        font-size: 2.5rem;
        padding-top: 6rem;
}
    .education-page h2{
        font-size: 5rem;
        font-weight: 900;
}
    .education-page h3{
        font-weight: 200;
}
    .education-home-content{
        text-align: center;
        width: 70%;
        margin: 0 0 4rem 12rem;
}
    button{
        margin: 3rem;
        padding: 10px 30px;
        border: none;
        border-radius: 5px;
        background-color: #1a84c6;
        z-index: 9999;
        color: white;
    }
    button:hover{
        cursor: pointer;
        background: #f3874f;
        color: white;
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
       /* .menu-toggle{ 
         padding: 5px 1rem; 
         position: absolute;
         top: -2rem;
         left: -1rem;     
      } */
/* 
==========================
home page ends here
==========================
*/

/*
===============================
main content starts from here 
===============================
*/
.main-content{
    background-color: whitesmoke;
}
.main-content h1{
    color: #f3874f;
    text-align: center;
}
.main-content-img{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    margin: 2rem;
}
.main-content-img p{
    font-size: .5rem;
}
.main-content-img img{
    margin-top: 2rem;
    border-radius: 10px 10px 0 0;
    height: 27rem;
    width: 15rem;
}
.card1{
    background-color: #f3874f;
}
.card2{
    background-color: #1a84c6;
}
.card3{
    background-color: #662d91;
}
.card1, .card2, .card3{
    width: 335px;
    border-radius: 0 0 10px 10px;
    height: 12rem;
}
.card1 p, .card2 p, .card3 p{
    margin: 0.5rem;
    text-align: center;
    color: 3rem;
}
.card1 h4 {
    text-align: center;
    color: #1a84c6;
}
.card2 h4, .card3 h4{
   color: #f3874f;
   text-align: center
}
.card3 p{
    color: #fff;
    /* font-size: 5rem; */
    font-weight: 100;
}
/* 
===============================
main content stops from here 
===============================
*/

/* 

media queries*/
/* Extra small devices (phones, 600px and down) */
@media screen and (max-width: 600px) {
    .education-container{
        width: 100%;
    }
    .education-page h1{
        font-size: .2rem;
    } 
      .menu-toggle {
        display: block; 
  }
    /* nav{
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        position: unset;
        z-index: 99999;
        height: 19rem;
        margin-top: 1rem;
        margin-bottom: -4rem;
        width: 100%; 
        background-color: #1a84c6;      
      }
      nav a{
        padding: .5rem;
        color: #fff;
        text-decoration: none;
        font-size: 1rem;
        width: 100%;
        text-align: center;
      } 
      nav a:active{
          color: #f3874f;
          border: 1px solid #fff;
      }
      nav h1{
          display: none;
      } */
      .education-page{
        height: 100%;
        width: 100%;
        margin: 1rem 1rem 2rem -12rem;

}
    .education-page h1{
        font-size: .5rem;
        padding-top: 6rem;
        margin-left: 1rem;
}
    .education-page h2{
        font-size: 1rem;
        font-weight: 900;
}
    .education-page h3{
        font-weight: 200;
}
    .education-home-content{
        width: 100%;
        padding: 1rem;
}

    .education-home-content h1{
        font-size: 1.3rem;
}
    .education-home-content h2{
        font-size: 2.1rem;
}
    .main-content-img{
        grid-template-columns: 1fr ;
        margin: 2rem;

}
    .main-content-img img{
        margin-top: 2rem;
        border-radius: 10px 10px 0 0;
        width: 100%;
}
    .main-content h1{
        padding: 1rem;
}
    .card1, .card2, .card3{
        width: 100%;
        border-radius: 0 0 10px 10px;
        height: 12rem;
}
.card1 h4, .card2 h4, .card3 h4 {
    font-size: 2.0rem;
}
.card1 p, .card2 p, .card3 p{
    font-size: 1.2rem;
}

}
/* Small devices (portrait tablets and large phones, 600px and up) */
@media screen and (min-width: 600px) {
    .education-container{
        width: 100%;
    }
    .education-page h1{
        font-size: .4rem;
    } 
      .menu-toggle {
        display: block; 
  }
    /* nav{
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        position: unset;
        z-index: 99999;
        height: 19rem;
        margin-top: 1rem;
        margin-bottom: -4rem;
        width: 100%; 
        background-color: #1a84c6;      
      }
      nav a{
        padding: .5rem;
        color: #fff;
        text-decoration: none;
        font-size: 1rem;
        width: 100%;
        text-align: center;
      } 
      nav a:active{
          color: #f3874f;
          border: 1px solid #fff;
      }
      nav h1{
          display: none;
      } */
      .education-page{
        height: 100%;
        width: 100%;
        margin: 1rem 1rem 2rem -12rem;

}
    .education-page h1{
        font-size: .5rem;
        padding-top: 6rem;
        margin-left: 1rem;
}
    .education-page h2{
        font-size: 1rem;
        font-weight: 900;
}
    .education-page h3{
        font-weight: 200;
}
    .education-home-content{
        width: 100%;
        padding: 1rem;
}
    .education-home-content h1{
        font-size: 1.3rem;
}
    .education-home-content h2{
        font-size: 2.1rem;
}
    .main-content-img{
        grid-template-columns: 1fr ;
        margin: 2rem;

}
    .main-content-img img{
        margin-top: 2rem;
        border-radius: 10px 10px 0 0;
        width: 100%;
}
.main-content h1{
        padding: 1rem;
}
    .card1, .card2, .card3{
        width: 100%;
        border-radius: 0 0 10px 10px;
        height: 12rem;
}
.card1 h4, .card2 h4, .card3 h4 {
    font-size: 2.2rem;
}
.card1 p, .card2 p, .card3 p{
    font-size: 1.5rem;
}
}
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
    .menu-toggle {
        display: none; 
  }
  .education-container{
        width: 100%;
    }
    .education-page h1{
        font-size: .6rem;
    } 
      .menu-toggle {
        display: none; 
  }
    nav{
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
        position: unset;
        z-index: 99999;
        height: 6rem;
        margin-top: 1rem;
        margin-bottom: -4rem;
        width: 100%; 
        background-color: #1a84c6;      
      }
      nav a{
        padding: .5rem;
        color: #fff;
        text-decoration: none;
        font-size: 1.3rem;
        width: 100%;
        text-align: center;
      } 
      nav a:active{
          color: #f3874f;
          border: 1px solid #fff;
      }
      nav h1{
          display: none;
      }
      .education-page{
        height: 100%;
        width: 100%;
        margin: 1rem 1rem 2rem -12rem;

}
    .education-page h1{
        font-size: .5rem;
        padding-top: 6rem;
        margin-left: 1rem;
}
    .education-page h2{
        font-size: 1.3rem;
        font-weight: 900;
}
    .education-page h3{
        font-weight: 200;
}
    .education-home-content{
        width: 100%;
        padding: 1rem;
}

    .education-home-content h1{
        font-size: 1.5rem;
}
    .education-home-content h2{
        font-size: 2.3rem;
}
    .main-content-img{
        display: grid;
        grid-template-columns: 1fr 1fr;
        margin: 2rem;
        gap: 1rem;
}
    .main-content-img img{
        margin-top: 2rem;
        border-radius: 10px 10px 0 0;
        width: 100%;
}
    .card1, .card2, .card3{
        width: 100%;
        border-radius: 0 0 10px 10px;
        height: 13rem;
}

}
/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
    .menu-toggle {
        display: none; 
  }
  .education-container{
        width: 100%;
    }
    .education-page h1{
        font-size: 1rem;
    }

    nav{
        display: flex;
        flex-direction: row;
        justify-content: flex-start;
        position: unset;
        z-index: 99999;
        height: 4rem;
        margin-top: 1rem;
        margin-bottom: 1rem;
        width: 100%; 
        background-color: transparent;     
      }
      nav a{
        padding: .5rem;
        color: #1a84c6;
        text-decoration: none;
        font-size: 1.4rem;
        width: 100%;
        text-align: center;
      } 
      nav a:active{
          color: #f3874f;
          border: 1px solid #fff;
      }
      .education-page{
        height: 100%;
        width: 100%;
        margin: 1rem 1rem 2rem -12rem;

}
    .education-page h1{
        font-size: .8rem;
        padding-top: 6rem;
        margin-left: 1rem;
}
    .education-page h2{
        font-size: 1.6rem;
        font-weight: 900;
}
    .education-page h3{
        font-weight: 200;
}
    .education-home-content{
        width: 100%;
        padding: 1rem;
}

    .education-home-content h1{
        font-size: 1.8rem;
}
    .education-home-content h2{
        font-size: 2.8rem;
}
    .main-content-img{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        margin: 2rem;
}
    .main-content-img img{
        margin-top: 2rem;
        border-radius: 10px 10px 0 0;
        width: 100%;
}
    .card1, .card2, .card3{
        width: 100%;
        border-radius: 0 0 10px 10px;
        height: 13rem;
}
}
/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
    .menu-toggle {
        display: none; 
  }
  .education-container{
        width: 100%;
    }
    .education-page h1{
        font-size: 1rem;
    }
    nav h1{
          display: block;
      }
      nav{
            display: flex;
            justify-content: flex-start;
            align-items: center;
            flex-direction: row;
            position: absolute;
            z-index: 99999;
            height: 4rem;
            margin-top: 1rem;
            margin-bottom: 3rem;
            width: 100%;        
      }
      nav a{
            padding: 1rem;
            color: #1a84c6;
            text-decoration: none;
            font-size: 1.3rem;
      }
      nav a:hover{
            color: #f3874f;
      }
      nav h1{
            margin: 0 6rem 0 2rem;
            color:#1a84c6;
      }
      .education-page{
            height: 100%;
            width: 100%;
            margin: 1rem 1rem 2rem -12rem;
}
        .education-page h1{
            font-size: .8rem;
            padding-top: 6rem;
            margin-left: 1rem;
}
        .education-page h2{
            font-size: 1.6rem;
            font-weight: 900;
}
        .education-page h3{
            font-weight: 200;
}
        .education-home-content{
            width: 100%;
}
        .education-home-content h1{
            font-size: 2.1rem;
}
        .education-home-content h2{
            font-size: 2.8rem;
}
        .main-content-img{
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            margin: 2rem;
            gap: 1rem;
}
        .main-content-img img{
            margin-top: 2rem;
            border-radius: 10px 10px 0 0;
            width: 100%;
}
        .card1, .card2, .card3{
            width: 100%;
            border-radius: 0 0 10px 10px;
            height: 10rem;
}       .card1 p, .card2 p, .card3 p{
            font-size: 1rem;
}
}
</style>