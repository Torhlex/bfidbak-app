<template>
  <div class="home">
  
     
     <Nav />
       <div class="content">
            <h1 class="main-content">Welcome Henry!</h1>
            <p class="sub-content">Enjoy the opportunity for easy access to feedback in real time. <br> The Feedback App allows you to give real-time anonymous feedback to any of your colleagues, with <br> the intention to help them grow and develop.</p>
        </div>
        <div class="btn-col">
            <button class="btn-1" onClick="location.href='Form.html'">Form <i class="fa-solid fa-angle-right"></i>
                <p>Do you have a complaint, you are one step <br> away to get your problem solved. This is <br> a document to fill your complaints.</p>
            </button>
            <button class="btn-2">General <i class="fa-solid fa-angle-right"></i> 
                <p>This is an avenue to share and receive information. This platform consists of every member of the organization.</p>
            </button>
        </div>
        
    </div>
  

 
    


</template>

<script>
// @ is an alias to /src
import Nav from '@/components/Nav.vue'

export default {
  name: 'DashBoard',
  components: {
    Nav
  }
}
</script>
<style>

.home{
  background-image: url(../assets/pexels-karolina-grabowska-4194854\ 2.png);
  background-size: cover;
  text-align: center;
  width: 100%;
  height: 100vh;
  
}

.container{
    position: relative;
    width: 100%;
    height: 100%;
    text-align: center;
}
.nav-bar{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.nav-bar h3{
    background-color: dodgerblue;
    color: #fff;
    margin-top: 0;
    /* overflow: hidden; */
    font-size: 80px;
    padding:30px 5px;
    margin-left: 0;
}
.nav-bar i{
    /* color: #fff; */
    margin-right: 10px;
    font-size:20px;
    cursor: pointer;
    background-color: #00a4db;
}
.nav-bar h3{
    margin-right: 25px;
    font-size: 16px;
    /* color: #fff; */
}

.content{
    /* margin: 30px 40px;
    color:#fff ;
    font-size: 10px;
    font-weight: bold;
    line-height: 20px; */
    text-align: center;
}

.main-content{
    color: #fff;
    font-size: 40px;
}
.sub-content{
    color: #fff;
    font-size: 20px;
    text-align: center;
}
/* .logo{
    display: flex;
    align-items: center;
    justify-content: space-between;
    /* position: absolute; */
    /* margin: 0 0 10px; */
    /* background-color: white; */
    /* padding: 20px; */
/* } */ */
.btn-col{
    position: absolute;
    top: 30%;
    left: 40%;  
}
.btn-1{
    padding: 30px 5px;
   border-radius: 10px; 
   background-color: #00a4db;
   margin: 5px;
   color: #fff;
   /* box-shadow: 0 4px 10px 0 #333333, 0 2px 5px 0 #333333; */
    margin-top: 50px;
    display:inline;
    font-size: 30px;
    cursor: pointer;
    width: 300px;
    outline: none;
}
.btn-1:hover{
    background-color: #fff;
    color: #00a4db;
}
.btn-2:hover{
    background-color: #fff;
    color: #00a4db;
}
.btn-2{
    padding: 30px 5px;
   border-radius: 10px; 
   background-color: #00a4db;
   margin: 5px;
   color: #fff;
   /* box-shadow: 0 4px 10px 0 #333333, 0 2px 5px 0 #333333; */
    margin-top: 50px;
    display:inline;
    font-size: 30px;
    cursor: pointer;
    width: 300px;
    outline: none;
}

.btn-col i{
    font-size: 20px;
    margin-left: 12px;
    /* background-color: dodgerblue; */
    padding: 8px;
    border-radius: 5px;
}
.btn-col i:hover{
    background-color: #fff;
    /* color: #fff; */
}
.btn-col p{
    font-size: 12.5px;
    padding: 0 5px;
    /* text-indent: 100px; */
}
</style>
