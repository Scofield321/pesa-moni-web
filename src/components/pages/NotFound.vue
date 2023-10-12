<template>
  <div class="not-found-container">
    <div class="home-wrapper">
        <div class="home-content">
                <h1>NOT FOUND</h1>
                <h3>ERROR : 404</h3>
                <button @click="BackHome">Back Home</button>
                <!-- <div class="phone">
                    <div class="screen">
                    <p>This is some text on the phone screen.</p>
                    </div>
                </div> -->
            </div>
    </div>
  </div>
</template>

<script>
export default {
    methods:{
        BackHome(){
        this.$router.push('/')
      }
    }
}
</script>

<style scoped>
    .not-found-container{
        background-color: whitesmoke;
        overflow: hidden;
    }
    .home-wrapper{
        background-color: black;
        background-size: cover;
        height: 100vh;
        color: #fff;       
    }
    .home-wrapper h1, .home-wrapper h3{
        text-align: center;
        color: red;
    }
    .home-wrapper h1{
        padding-top: 15rem;
        font-size: 5rem;
    }
    button{
        color: white;
        background-color: #1a84c6;
        padding: 10px 40px;
        border: none;
        border-radius: 4px;
        margin: 2rem 0 0 35rem ;
    }
    button:hover{
        background-color: #f3874f;
    }
    .phone {
  width: 300px; /* Adjust the width of the phone container */
  height: 600px; /* Adjust the height of the phone container */
  background-color: #333; /* Phone body color */
  border-radius: 20px; /* Rounded corners */
  margin: 50px auto; /* Center the phone on the page */
  position: relative;
}

.screen {
  background-color: #fff; /* Screen background color */
  padding: 20px;
  border-radius: 15px; /* Rounded corners for screen */
  height: 100%;
  box-sizing: border-box;
}

p {
  font-size: 18px; /* Adjust font size */
  color: #333; /* Text color */
  line-height: 1.5; /* Line height for readability */
}
</style>