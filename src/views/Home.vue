<template>
  <div class="body">
   <header>
    <a href="#banner" class="logo">ECOERI<span>.</span></a>
    <div class="menuToggle" onclick="toggleMenu();"></div>
    <div id="nav">
    <ul class="navigation">
        <li><a href="#banner" onclick="toggleMenu();">Home</a></li>
        <li><a href="#about" onclick="toggleMenu();">About</a></li>
        <li><a href="#products" onclick="toggleMenu();">Products</a></li>
        <li><a href="#partners" onclick="toggleMenu();">Partners</a></li>
        <li><a href="#testimonials" onclick="toggleMenu();">Testimonials</a></li>
        <li><a href="#contact" onclick="toggleMenu();">Contact</a></li>
    </ul> 
    </div>  

     <div class="social-media01">
        <a href="#" class="ico1"><i class="fab fa-facebook"></i></a>
        <a href="#" class="ico1"><i class="fab fa-twitter"></i></a>
        <a href="#" class="ico1"><i class="fab fa-whatsapp"></i></a>
        <a href="#" class="ico1"><i class="fab fa-linkedin"></i></a>
        <a href="http://maps.google.com/?q=Kings Business Park, MV6G+FQ4, Nairobi" class="ico1"><i class="fas fa-map-marker-alt"></i></a>
        </div>
</header> 
    <!--<div class="navigation2">
    <div class="wrapper">
        <div class="button">
            <div class="icon">
                <i class="fa fa-facebook"></i>
            </div>
            <span>Facebook</span>
        </div>

           <div class="button">
            <div class="icon">
                <i class="fa fa-twitter"></i>
            </div>
            <span>Twitter</span>
        </div>

           <div class="button">
            <div class="icon">
                <i class="fa fa-linkedin"></i>
            </div>
            <span>LinkedIn</span>
        </div>
    </div>
    </div>-->
    <section class="banner" id="banner">
        <div class="content">
            <h2>Eco Friendly Products Manufacturer</h2>
            <p>Leading fabric Manufacturer in Eastern Africa and beyond</p>
            <a href="#products" class="btn">Our Products</a>
        </div>
        <div class="custom-shape-divider-bottom-1631127850">
            <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
                <path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" opacity=".25" class="shape-fill"></path>
                <path d="M0,0V15.81C13,36.92,27.64,56.86,47.69,72.05,99.41,111.27,165,111,224.58,91.58c31.15-10.15,60.09-26.07,89.67-39.8,40.92-19,84.73-46,130.83-49.67,36.26-2.85,70.9,9.42,98.6,31.56,31.77,25.39,62.32,62,103.63,73,40.44,10.79,81.35-6.69,119.13-24.28s75.16-39,116.92-43.05c59.73-5.85,113.28,22.88,168.9,38.84,30.2,8.66,59,6.17,87.09-7.5,22.43-10.89,48-26.93,60.65-49.24V0Z" opacity=".5" class="shape-fill"></path>
                <path d="M0,0V5.63C149.93,59,314.09,71.32,475.83,42.57c43-7.64,84.23-20.12,127.61-26.46,59-8.63,112.48,12.24,165.56,35.4C827.93,77.22,886,95.24,951.2,90c86.53-7,172.46-45.71,248.8-84.81V0Z" class="shape-fill"></path>
            </svg>
        </div>
    </section>

    <section class="about" id="about">
        <div class="row">
            <div class="col50">
                <div class="imgBx"  data-aos="fade-right"  data-aos-delay="200" data-aos-duration="1500">
                    <img src="https://images.pexels.com/photos/6305928/pexels-photo-6305928.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940">
                </div>
            </div>
           
            <div class="col50" id="col50" data-aos="fade-left"  data-aos-delay="200" data-aos-duration="1500">
                <h2 class="titleText"><span>A</span>bout Us</h2>
                <p>ECO-ERI GREEN COMPANY LIMITED is a renowned manufacturer of non-woven fabric. The company ventured in non-woven fabric  in January 2018 after the Kenyan government banned usage of plastic bags .The Company boasts of the state of art machinery which has facilitated fast and consistent growth of production. The company is a market leader in producing quality non-woven fabric, in East Africa.
                    <br><br>Through mastery of the extrusion process, various raw materials are converted into an eco-friendly high grade non-woven fabric that is used to manufacture various products such as non-woven bags. Notably during this COVID 19 the company has ensured consistent production of Fabric required for the manufacturing of masks, which has enabled the prevention of the spread of the pandemic.
                </p>
            </div>
        </div>
    </section>

    <section class="products" id="products">
        <div class="title">
            <h2 class="titleText">Our <span>P</span>roducts</h2>
            <p>-Non-woven Fabric Red, Yellow, Green, Blue, White-</p>
        </div>
        <div class="content">
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product01.jpg">
                </div>
                <!--<div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>-->
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product 02.jpg">
                </div>
                <!--<div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>-->
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product03.jpg">
                </div>
                <!--<div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>-->
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product04.jpg">
                </div>
                <!--<div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>-->
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product05.jpg">
                </div>
                <!--<div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>-->
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product07.jpg">
                </div>
                <!--<div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>-->
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/fabric1.jpg">
                </div>
                <!--<div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>-->
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/fabric2.jpg">
                </div>
                <!--<div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>-->
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="https://img2237.weyesimg.com/uploads/raysonchina.com/images/20160828/lim/14723500675227.jpg?imageView2/2/w/955/q/100">
                </div>
              
            </div>
            
        </div>
    </section>

    <!--<section class="products" id="products">
        <div class="title">
            <h2 class="titleText">Finished <span>P</span>roducts</h2>
        </div>
        <div class="content">
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product01.jpg">
                </div>
                <div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product 02.jpg">
                </div>
                <div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product03.jpg">
                </div>
                <div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product04.jpg">
                </div>
                <div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product05.jpg">
                </div>
                <div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/product07.jpg">
                </div>
                <div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/fabric1.jpg">
                </div>
                <div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/fabric2.jpg">
                </div>
                <div class="text">
                    <h3>Non-woven Fabric Red</h3>
                </div>
            </div>
            <div class="box" data-aos="fade-up" data-aos-delay="150" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="https://img2237.weyesimg.com/uploads/raysonchina.com/images/20160828/lim/14723500675227.jpg?imageView2/2/w/955/q/100">
                </div>
              
            </div>
            
        </div>
    </section>-->

    <section class="partners" id="partners">
        <div class="title">
            <h2 class="titleText">Our <span>P</span>artners</h2>
            <p>We conform 100% to:</p>
        </div>
         <div class="content">
             <div class="box" data-aos="zoom-in" data-aos-duration="1500">
                 <div class="imgBx">
                     <img src="../assets/kamPartners.jpg">
                 </div>
             </div>
             <div class="box" data-aos="zoom-in" data-aos-duration="1500">
                <div class="imgBx">
                    <img src="../assets/nemaPartner.jpg">
                </div>
            </div>
         </div>
    </section>


    <section class="testimonials" id="testimonials">
        <div class="title white">
            <h2 class="titleText">What <span>C</span>ustomers Say About Us</h2>
            <p>-Sample customer feedback-</p>
        </div>
        <div class="content">
            <div class="box" data-aos="flip-left" data-aos-delay="200" data-aos-duration="1500">
                <div class="text">
                   <p><strong>"</strong> Ever since we made Ecoeri-green our supplier, we have been able to make durable and quality face masks for our customers. We love and enjoy their fabrics.<strong>"</strong></p> 
                   <h3>EAKO</h3>
                </div>
            </div>
            <div class="box" data-aos="flip-left" data-aos-delay="250" data-aos-duration="1500">
                <div class="text">
                   <p><strong>"</strong> We have experienced great sales since incorporating Eco-eri green's fabrics. That is because they have provided good and quality fabrics to our target customers.<strong>"</strong></p> 
                   <h3>PROMO KINGS</h3>
                </div>
            </div>
            <div class="box" data-aos="flip-left" data-aos-delay="300" data-aos-duration="1500">
                <div class="text">
                   <p><strong>"</strong> We chose Ecoeri-green simply because they offered all the products such as variety of colors and textures we needed to do what we do effectively. We would definitely recommend.<strong>"</strong></p> 
                   <h3>CROWN HEALTH</h3>
                </div>
            </div>
        </div>
    </section>    

    <section class="contact" id="contact">
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
                <p class="map"><i class="fas fa-map-marker-alt"></i> Kings Business Park, next to Inland Container Depot, Mombasa Road</p><br>
                    <p><i class="fa fa-phone"></i><strong> Phone:</strong><a href="tel:0707389974" class="phone"> +254 707 38 9974</a></p><br>
                    <p><i class="fa fa-envelope"></i><strong> Email:</strong><a href="mailto:info@eceoerigreen.co.ke" class="email"> info@eceoerigreen.co.ke</a><br></p>
                     <div class="social-media">
                        <a href="#" class="ico"><i class="fab fa-facebook"></i></a>
                        <a href="#" class="ico"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="ico"><i class="fab fa-whatsapp"></i></a>
                        <a href="#" class="ico"><i class="fab fa-linkedin"></i></a>
                        <a href="http://maps.google.com/?q=Kings Business Park, MV6G+FQ4, Nairobi" class="ico1"><i class="fas fa-map-marker-alt"></i></a>
                    </div> 
                    <!--<div class="social-links">
                    <a href="#" class="social"><i class="fa fa-facebook" id="facebook"></i></a>
                    <a href="#" class="social"><i class="fa fa-linkedin" id="linkedin"></i></a>
                    <a href="#" class="social"><i class="fa fa-twitter" id="twitter"></i></a>
                    </div>-->
            </div>

        </div>
        </div> 
    </section>  
    
    <div class="copyrightText">
       <p>&copy; {{ new Date().getFullYear() }} — Copyright ECO-ERI GREEN COMPANY LIMITED . All Rights Reserved.
            </p>
            <p>Designed by <strong><span><a href="http://fineteklabs.com/">FinetekLabs</a></span></strong></p>
    </div>


  </div>
</template>
 

<script>

  export default {
    name: 'Home',

    components: {
    
    },
  }
</script>
