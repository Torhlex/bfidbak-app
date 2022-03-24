<template>
  <div class="Login">

    <Nav />
    <body>
    <div class="overallparent">
      <div class="BfreeLogo">
        <img
      src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALUAAAA4CAYAAAC7fbmvAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAU3SURBVHgB7Z3xdds2EMY/9/X/agPDEzSdoMwEiSeIMkHSCSJNEHsCyxNYmcDsBFUnCDpBtQF7F0LvqTRJ40hCBMD7vYfnZ5Iiaerj4XB3gK8qAvFhXTtQ+3Z1dVVCUTy5ilTUTSy1HbVHEriFovSQiqhPWGpbEvYOitJBaqI+saf2h1ptpY1URc1Yam9V2EqTn5AuhtozvZMGinJGyqJmDLUHKMoZqYuaKchaf4aiOFL2qc85UvtN/WuFycFSMytqX6AoyMdSM2ytb8haH6EsmlwsNcPWeg1l8Qyx1Na1ULA432AYJVnqt1CWTSVnjcBw7JnaUyXnXyiL52dEiIti3JJIn+lnIfjoij5zTZ//BwOgzw7tJY50zYPPgXQNPv8K4zmcjx9cEspAzsF3HELXKDANzXsf0zv/jx8VnZWcNS4EP8RKToGBDLzeOU+vXZ/2P1fTUDTOu6uG8xe1T1VPdraqe8+puG6ce11Nw3c+X9QDRVdHLY1mGMzHe9Sp+9TCi2wl71Df+yQWc05SiH6kGKLbVGlmOQ0yqKeJ0qc+UdW+loEMi+mxHdtX6PaPv9D972aOmx/RbRRMx3b+e7ieJtkoUtSiRt2dS/EasAmwJMybrp2uu37CS5GcBj8lXucedfcvwedl2dO9f+zaWdXjo694+WLy2GLl+ULeQvjMBQP5GwwgWlG7LlDqm9pLW0aOetC9snCeW3Yb+HGco26FZxC53vBry24DP7EGu/eh5w0m6hF+GT/kArWgpaGvEvPQ9SJZxM8e7aKeIuw4CyEtNftlBS7LFvPwe8f2qV2hEJiO7cnW0MTuU0vYBeoGV1V/bJ4F3bZ/m0hx1aeWbdY3mUR8qGS5gdJ3yQs67wYy7viZ5yTqUFb6FA2QwEs5bATHv2smJDzOX3ocZ3peyF9R96RtcWnJs1xDTul5nHRMxd9TNqLeRjRBYNcXcejgDWRp4j89jysgdwGTX4Iih9LTrdAqhoZTvt8TTGBY1LPzN0icHCw1+3TeftpAyp59bQVKhhrXU6Q0xcxQe6B7li47ITmWkYwzLAaQg6gN6tTuhr6MEH61fa1G26XEm2ExSWbOQvYF+h7LAmob8HVVxRnU8XZJ0uNjKIPSl/TqI6eBItdbIJCwe6Fr3rnM4ofGLt/MnHRg6UtnRtG5R/wiNrO2PLh8T5/bI1Fyms7FbKrpan6l2I7tvyBCnIvRNaAtkDC5iZp5cKnfSyMJyUWB60Fsyy6DhMlR1AYXnoDrXI+24qvj0Fk4MxNl7+JLSJ/6bwyjLZog5R3kVW9dcEaxL/li0N1dJ+uXCuDZPtLMaekTyz/NZBFyH0zUdNOfMRCXHh0ze4QHaNcTWcmhSy9YzFeLckn6asrHYiDHRul+uEjAPcYxZ5E7W67bhGLUlyakS3aM2afeYFyl2ByDRb5ffhlvBAVBc9MVx770NSc7d7Rxah6Zc6YQw2a/MAZyLIa5DNY1n+UGHvGydqPEePZ4GcnwEQ/fT3P80/Y38Lap3KlDy++TnPvH86/krHEhqnHT/qcaKCqJEXtIb0xoaYzroiRM7KKWlGM2UVEvlGhFTe4Dz8gwGI6FskiiFLUT9Fif2EJZJCFnk3MF2BD3YYqM4jGhkJoyMSFDeizOAvPgO91JyZAcC5qYJdRcKB3kKGqr/7t82eQo6kcoiyY3UVtqOyiLJjdRx7T+hzITOYk6+UVYlGnIRdShZmMrCZLLCk1rKIoj5XU/LAIupKKkS4qiLql94wVkoCgtxC7q0z/iKVHPzii1pkN5jf8AMghNMcNyLXcAAAAASUVORK5CYII="
          alt="bfree-logo"
          width="120"
          height="50"
        />
      </div>
      <div class="overall">
          <!-- <p><h2>Let's get you registered</h2></p> -->

          <div class="formArea">
          <p><h1>Login</h1></p>

            <form>
              <!-- <label> Bfree ID/Email address</label> -->
              <div class="form-field">
                <input type="BfreeID or Email-address" placeholder="BfreeID or Email address" required />
              </div>
              <!-- <label>  Password</label> -->
              <div class="form-field">
                <input type="Password" placeholder="Password" required />
              </div>
              <div class="passwordreset">         
              <p><h4>Forgot password? <a onClick="location.href='Forgetpass.html'">Reset password</a></h4></p>
              </div>

              <div class="form-field">
                <button class="btn" type="Login" > <a onClick="location.href='#.html'">Login</a></button>
              </div>             
            </form>
             <div class="CreateAcct">         
              <p><h4>Click to <a onClick="location.href='Reg.html'">Create an account</a></h4></p>
              </div>
          </div>
      
        <!-- <div class="sideimage">
          <img src="img/bg img1.png" alt=" home pic" height=90%" width="auto" />
        </div> -->
      </div>
    </div>
  </body>
</template>

<script>
import Nav from "@/components/Nav.vue";

export default {
  name: "Login",
  components: {
    Nav,
  },
};
</script>

<style>
body {
  /* background-color: skyblue; */
  background-image: url(img/bggg.jpeg);
  background-blend-mode: soft-light;
  /* height: 500px; */
  background-size: cover;
  background-position: center center !important;
  background-attachment: fixed;
  color: #fff;
  font-family: Verdana, Arial, Helvetica, sans-serif;
}

.BfreeLogo {
  /* display: flexbox; */
  /* background-color: skyblue; */
  width: 10px;
  /* height: 40px; */
  padding: 20px;
}

.overall {
  /* background-color: rgb(255, 255, 255); */
  /* border-radius: 20px; */
  background-size: cover;
  background-position: center center !important;
  background-attachment: fixed;
  top: 20%;
  left: 36%;
  position: absolute;
  /* background: rgba(255, 255, 255, 0.309); */
  /* width: auto;
  height: auto;
  align-items: center; */
}

p, h4, h1 {
  /* font-family: Arial, Helvetica, sans-serif; */
  color: rgb(255, 255, 255);
  text-align: center;
}

h1 {
  /* font-family: Arial, Helvetica, sans-serif; */
  color: rgb(255, 255, 255);
  text-align: center;
  padding-bottom: 20px;
}

.formArea {
  /* font-family: Arial, Helvetica, sans-serif; */
  color: #090808;
  overflow: hidden;
  margin: 0;
  padding: 0;
}

form {
  /* font-family: Arial, Helvetica, sans-serif; */
  width: 450px;

  /* position: relative; */
}

form .form-field::before {
  font-size: 30px;
  position: absolute;
  left: 15px;
  top: 16px;
  color: #ffffff;
  content: " ";
  display: block;
  background-size: cover;
  background-repeat: no-repeat;
}

form label {
  /* font-family: "Lato", sans-serif; */
  font-size: 30px;
  color: rgb(0, 5, 10);
}

form .form-field:nth-child(1)::before {
  background-image: url(https://api.iconify.design/mdi:email-open.svg?color=%23ffffff);
  width: 23px;
  height: 23px;
  top: 12px;
  left: 10px;
}

form .form-field:nth-child(2)::before {
  background-image: url(https://api.iconify.design/uil:lock-alt.svg?color=%23ffffff);
  width: 23px;
  height: 23px;
  top: 12px;
  left: 10px;
}

form .form-field {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 25px;
  position: relative;
}

input:-webkit-autofill {
  box-shadow: 0 0 0 50px rgba(50, 95, 153, 0.974) inset; /* Change the color to your own background color */
  -webkit-text-fill-color: rgb(255, 255, 255);
}

form input {
  font-family: inherit;
  width: 100%;
  outline: none;
  border: none;
  border-radius: 8px;
  border-color: skyblue;
  /* font-family: Arial, Helvetica, sans-serif; */
  background-color: rgba(50, 95, 153, 0.974);
  display: block;
  padding: 15px 25px;
  /* box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.501); */
  font-size: 13px;
  color: #ffffff;
  text-indent: 30px;
}

::placeholder {
  /* font-family: Arial, Helvetica, sans-serif; */
  color: white;
}

form .btn {
  /* font-family: Arial, Helvetica, sans-serif; */
  outline: none;
  border: none;
  cursor: pointer;
  display: inline-block;
  margin: 0 auto;
  padding: 0.9rem 2.5rem;
  text-align: center;
  font-weight: bold;
  /* margin-top: 15px; */
  background-color: rgb(255, 255, 255);
  color: rgb(72, 147, 245);
  border-radius: 8px;
  /* box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.337); */
  font-size: 16px;
}

.passwordreset {
  /* font-family: Arial, Helvetica, sans-serif; */
  width: 350px;
  margin: 0 auto;
  color: rgb(255, 255, 255);
  text-align: center;
  padding: 0;
  font-size: 13px;
}
.passwordreset a {
  color: rgb(255, 255, 255);
  cursor: pointer;
  text-decoration: none;
  font-size: 11px;
}

.CreateAcct a {
  color: rgb(255, 255, 255);
  cursor: pointer;
  text-decoration: none;
    font-size: 14px;
}

/* a:hover{
  color: rgb(224, 30, 30);
} */
</style>