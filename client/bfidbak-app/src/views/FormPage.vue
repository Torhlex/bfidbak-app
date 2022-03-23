<template>
  <div class="home">

      <Nav />
      <div class="content">
        <h3>New Message</h3>

        <div class="inbox-1">
            <label for="to">TO</label>
            <select name="" id="">
                <option value=""></option>
                <option value="hr">HR</option>
                <option value="tech">TECH</option>
                <option value="operations">OPERATIONS</option>
            </select>
        </div>

        <div class="inbox-2">
            <label for="subject">Subject</label>
            <input type="text">
        </div>

        <div class="comment">
            <textarea name="comp" id="" cols="30" rows="10" placeholder="Fill complaints"></textarea>
        </div>

        <hr>
        <div class="Submit">
            <input type="submit" class="send" onClick="location.href='Rating.html'">
        </div>
    </div>
  </div>
</template>

<script>
import Nav from '@/components/Nav.vue'

export default {
  name: 'HomeView',
  components: {
    Nav
  }
}
</script>
 
<style>
h3{
         color: #fff;
         margin-left: 30px; 
         margin-bottom: 30px;  
         font-family: Georgia, 'Times New Roman', Times, serif;
        }
        .inbox-1 label{
            color: #fff;
            margin: 0 40px 20px 30px;
            font-size: 10px;
            width: 100%;
        }
        .inbox-2 label{
            color: #fff;
            margin: 0 10px 20px 30px;
        }

        .inbox-1 select, input[type="text"]{
            background: #efefef;
            width: 70%;
            height: 30px;
            border-radius: 10px;
            padding: 0 15px;
            margin-bottom: 20px;
            outline: none;
        }
        .inbox-2 input[type="text"]{
            margin-bottom: 40px;
            border-style: none;
            color: black;
            font-size: 13px;
        }
        textarea{
            width: 600px;
            background: transparent;
            border: none;
            outline: none;
            border-bottom: 1px solide gray;
            color: #fff;
            font-size: 18px;
            margin-bottom: 16px;
        }
        .Submit{
            margin: 15px 20px;
            
        }
        .send{
            cursor: pointer;
            border: none;
            outline: none;
        }
        .content{
            /* background-color: rgb(71, 78, 104); */
            background-color: #016081;

            overflow: hidden;
            width: 60%;
            margin-left: 270px;    
        }

</style>