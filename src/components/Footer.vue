<template>
  <div class="footer">

      
    <section>
        <div class="title">
            <h2 class="titleText"><span>C</span>ontact Us</h2>
            <p>We would love to hear from you.</p>
        </div>
        <div class="container">
            <div class="contactForm left" data-aos="fade-right"  data-aos-delay="200" data-aos-duration="1500">
            <h3>Send Message</h3>
            <div class="inputBox">
                <input type="text" placeholder="Name">
            </div>
            <div class="inputBox">
                <input type="text" placeholder="Email">
            </div>
            <div class="inputBox">
                <textarea placeholder="Text area"></textarea>
            </div>
            <div class="inputBox">
                <input type="submit" value="Send">
            </div>
        </div>

        <div class="right" data-aos="fade-left"  data-aos-delay="200" data-aos-duration="1500">
            <div class="content">
              <h1>Get in Touch</h1>
              <p class="company">Ecoeri Green Company Limited</p>
                <p><i class="fa fa-map-marker"></i> Kings Business Park, next to Inland Container Depot, Mombasa Road</p><br>
                    <p><i class="fa fa-phone"></i><strong> Phone:</strong> +254 700 00 0000</p><br>
                    <p><i class="fa fa-envelope"></i><strong> Email:</strong><a href="info@eceoerigreen.co.ke" class="email">info@eceoerigreen.co.ke</a><br></p>
                    <div class="social-links">
                    <a href="#"><i class="fa fa-twitter" id="twitter"></i></a>
                    <a href="#"><i class="fa fa-facebook" id="facebook"></i></a>
                    <a href="#"><i class="fa fa-linkedin" id="linkedin"></i></a>
                    </div>
            </div>

        </div>
        </div> 
    </section>  
    
    <div class="copyrightText">
        <p>Copyright 2020 <a href="http://fineteklabs.com/">FinetekLabs</a> .All Rights Reserved.</p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

.contact{
    background-color: #CFEED1;
    background-size: cover;
}
.contactForm{
    border-radius: 10px;
    padding: 75px 50px;
    background: #fff;
    box-shadow: 0 15px 50px rgba(0,0,0,0.1);
    max-width: 500px;
    height: 500px;
    margin-top: 50px;
}
.contactForm h3{
    color: #111;
    font-size: 1.2em;
    margin-bottom: 20px;
    font-weight: 500;
}
.contactForm .inputBox{
    position: relative;
    width: 100%;
    margin-bottom: 20px;
}
.contactForm .inputBox input, .contactForm .inputBox textarea{
    width: 70%;
    border: 1px solid #555;
    padding: 10px;
    color: #111;
    outline: none;
    font-size: 16px;
    font-weight: 300;
    resize: none;
}
.contactForm .inputBox input[type="submit"]{
    font-size: 1em;
    color: #fff;
    background: #9ff21e;
    display: inline-block;
    text-transform: uppercase;
    text-decoration: none;
    letter-spacing: 2px;
    transition: 0.5s;
    max-width: 100px;
    font-weight: 500;
    border: none;
    cursor: pointer;
}
.copyrightText{
   background-color: #007481;
   padding: 8px 40px;
   border-top: 1px solid rgba(0,0,0,0.1);
   text-align: center; 
}
.copyrightText p{
    color: #fff;
}
.copyrightText a{
    color: #9ff21e;
    font-weight: 500;
    text-decoration: none;
}
.container {
    width: 90%;
    max-width: 1000px;
    margin: 50px auto;
    display: flex;
    align-items: center;
    justify-content: center;
    /* background-color: aqua; */
  }
  .left {
    width: 50%;
    height: 500px;
    border-radius: 8px;
  }
  .right {
    width: 50%;
    min-height: 400px;
    background-color: #007481;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 30px;
    border-radius: 8px;
    color: white;
    margin-left: -140px;
  }
  .right h1 {
    font-size: 41px;
    font-weight: lighter;
  }
  .right p {
    margin: 10px 0;
    font-weight: 400;
    line-height: 20px;
    color: #fff;
  }
  .right a {
    text-decoration: none;
    border: 1px solid #9ff21e;
    border-radius: 50%;
    color: #fff;
    padding: 10px 10px;
    margin-right: 5px;
    display: inline-block;
  }
  .right .email{
      background-color: inherit;
      border: none;
  }
  .right a:hover{
      color: #9ff21e;
  }
  .right a i{
      font-size: 20px;
      cursor: pointer;
  }
  .right a i:hover{
    color: #9ff21e;
}
.company {
    font-size: 23px;
    font-weight: 500;
}
  @media only screen and (max-width: 768px) {
    .container {
      flex-direction: column;
      width: 100%;
      margin: 0 20px;
    }
    .left {
      width: 100%;
      height: 400px;
    }
    .right {
      width: 90%;
      margin: 0;
      margin-top: -20px;
    }
  }  

</style>