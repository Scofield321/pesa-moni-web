<template>
  <div class="footer-container">
    <div class="the-footer">
            <div class="about-pesamoni">
                <h3>ABOUT PESAMONI</h3>
                <div class="about-links">
                  <router-link to="/about-us"> About Us</router-link>
                  <router-link to="/contact-us">Contact Us</router-link>
                  <router-link to="/news-blogs"> News and Blogs</router-link>
                  <router-link to="/careers">Careers</router-link>
                  <router-link to="/privacy-policy">Privacy Policy</router-link>
                  <router-link to="/terms-conditions">Term & conditions</router-link>
                </div>
            </div>
           <div class="services">
                <h3>HELP, SERVICES & PRODUCTS</h3>
                <div class="about-links">
                  <!-- <router-link to="/send-money">Send Money</router-link> -->
                  <router-link to="/supported-network">Supported Network</router-link>
                  <router-link to="/promos">Promos</router-link>
                  <router-link to="/products-services">Products</router-link>
                  <!-- <router-link to="/faqs">FAQs</router-link> -->
                </div>
          </div>
          <div class="development-portal">
            <h3>DEVELOPERS PORTAL</h3>
            <a href="https://documenter.getpostman.com/view/10119331/2s8Z6yWYF2">Documentation</a>
            <h3>SOCIAL MEDIA</h3>
            <div class="social-media-links">
              <a href="https://www.linkedin.com/search/results/all/?heroEntityKey=urn%3Ali%3Aorganization%3A10882190&keywords=PesaMoni&origin=ENTITY_SEARCH_HOME_HISTORY&sid=HMp" target="_blank">
                  <span class="linkedin-icon fab fa-linkedin-in"></span>
              </a>
              <!-- <a href="https://www.youtube.com/user/your_youtube_username" target="_blank">
                  <span class="youtube-icon fab fa-youtube"></span>
              </a> -->
              <a href="https://wa.me/256759566348?text=Hello%20there!" target="_blank"><i class="fa fa-whatsapp" aria-hidden="true"></i>
              </a>
              <a href="https://www.instagram.com/pesamoniug" target="_blank">
                  <span class="instagram-icon fa fa-instagram"></span>
              </a>
              <!-- <a href="https://twitter.com/your_twitter_username" target="_blank">
                  <span class="twitter-icon fa fa-twitter"></span>
              </a> -->
              <!-- <a href="https://www.facebook.com/your_facebook_page" target="_blank">
                  <span class="facebook-icon fab fa-facebook-f"></span>
              </a> -->
            </div>
          </div>
    </div>
    <p>&copy; 2016 - {{ currentYear }} Pesamoni Limited. All rights reserved.</p>
  </div>
  
</template>

<script>
export default {
  data(){
      return{
          currentYear: new Date().getFullYear()
      }
  }
}
</script>

<style scoped>
.footer-container{
  background-color: #1a84c6;
  margin-bottom:0 ;
  height: 25rem;
  width: 100%;
}
.the-footer{
  background-color: #1a84c6;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  padding: 3rem;
}

.social-media-icons{
    margin-left:30rem;
    margin-bottom: 0;
}
a{
    font-size: .8rem;
    color: white;
    text-decoration: none;
    margin-left: 2rem;
}
a:hover{
  color: #f3874f;
}
p{
    color: white;
    text-align: center;
}
h3{
  font-size: small;
  color: #fff;
  font-weight: 400;
  margin-left: 1rem;
  padding: 1rem;
}
.about-links{
  display: flex;
  flex-direction: column;
  margin-left: 1rem;
}
.social-media-links a{
  font-size: small;
  padding: .5rem;
  margin-left: 0;
}
/* media queries*/ 
/* Extra small devices (phones, 600px and down) */
@media screen and (max-width: 600px) {
  .footer-container{
  height: 25rem;
}
.the-footer{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  padding: 1.5rem;
}

.social-media-icons{
    margin-left:30rem;
    margin-bottom: 0;
}
a{
    font-size: .6rem;
    margin-left: 1.6rem;
}
a:hover{
  color: #f3874f;
}
p{
    text-align: center;
}
h3{
  font-size: small;
  margin-left: 1rem;
  padding: 1rem;
}
.about-links{
  display: flex;
  flex-direction: column;
  margin-left: 1rem;
}
.social-media-links a{
  font-size: small;
  padding: .5rem;
  margin-left: 0;
}
}
</style>