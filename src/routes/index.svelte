<script>
	
    import Navbar from "./comp library/Navbar.svelte";
    import Header from "./comp library/Header.svelte";
    import Footer from "./comp library/Footer.svelte";
    import "../styles/global.css";
    
</script>
    
    
    
    
    
    
    
    
    
    
    <main>
        <Header />
        <Navbar />
        <section class="sec-1">
    
            <div class="landing-page-info">
              <div>
                <h2>EDUCATION OPENS DOORS</h2>
              </div>
              <div><img id="main-logo" src="/img/icons/Wordpress Transparent.png" alt="Main-Logo"></div>
                <h3 id="descr-1">The method for successful learning</h3>
                <p id="descr-2">With Berndt Education, your company benefits from an engaging learning concept 
                    which exploits interconnectedness via media in conjunction with classic learning methods.</p>
            </div>
          <div class="first-area">
                <p>Get in contact!</p>
          </div>
    
          <div class="buttons">
            <div class="button-1"><a href="/courses">Get Started</a></div>
            <div class="button-2"><a href="/courses">Our Courses </a></div>
          </div>
          <!----------
          <div class="socials">
            <div><a href="https://www.twitter.com" class="social">
              <img id="twitter" src="src/img/icons/twitter.png" alt="Twitter">
            </a></div>
            <div><a href="https://www.facebook.com"  class="social">
              <img id="facebook" src="src/img/icons/facebook.png" alt="Facebook"> 
            </a></div>
            <div><a href="https://www.instagram.com"  class="social">
              <img id="instagram" src="src/img/icons/instagram.png" alt="Instagram">
            </a></div>
          </div> 
          ---------->
    
        </section>
    
        <section class="sub-section">
            <div class="information">
                <h2>BE ACTIVE LEARNING SYSTEM</h2>
                <h3 id="sub1">The method for successful learning</h3>
                <p>With Berndt Education, your company benefits from an engaging learning concept 
                    which exploits interconnectedness via media in conjunction with classic learning methods.</p>
            </div>
            <!----------
            <div class="headshot-container">
                <img class="headshot" src="img/be-logo.png" alt="">
            </div>
            ---------->
        </section>
    
        <section class="sub-section-alternative">
            <h2>Our Benefits</h2>
            <div class="info-container">
                <div class="info">
                    <img class="info-image" src="img/icons/3.png" alt="Adapted Content">
                    <div>
                      <h3>ADAPTED CONTENT</h3>
                      <p class="subtext">Teachers design the assignments on the online platform.</p>
                    </div>
                </div>
                <div class="info">
                  <img class="info-image" src="img/icons/4.png" alt="Individual Learning">
                  <div>
                    <h3>INDIVIDUAL LEARNING</h3>
                    <p class="subtext">Based on the student’s level and learning speed.</p>
                  </div>
                </div>
                <div class="info">
                  <img class="info-image" src="img/icons/2.png" alt="Flexible Communication">
                  <div>
                    <h3>FLEXIBLE COMMUNICATION</h3>
                    <p class="subtext">Participants and teacher use the platform to communicate even outside of lessons.</p>
                  </div>
                </div>
                <div class="info">
                  <img class="info-image" src="img/icons/1.png" alt="Regular Checks">
                  <div>
                    <h3>REGULAR CHECKS</h3>
                    <p class="subtext">Teacher corrects online and monitors use of the platform and learning success.</p>
                  </div>
                </div>
                <div class="info">
                  <img class="info-image" src="img/icons/6.png" alt="Specific Advancement">
                  <div>
                    <h3>SPECIFIC ADVANCEMENT</h3>
                    <p class="subtext">Participants learn independent of the instructor and can therefore achieve maximum learning success.</p>
                  </div>
                </div>
            </div>
        </section>
        <Footer />
    </main>
    
    
    
    
    
    
    
    
    
    
    <style>


   







    /** {
        border: 2px solid black;
    }*/
    
    main {
            font-family: 'Poppins', sans-serif;
            margin: 0;
    }
    
    /*h1 {
            color: #ff3e00;
            text-transform: uppercase;
            font-size: 4em;
            font-weight: 100;
    }*/
    
    @media (min-width: 640px) {
        main {
                max-width: none;
        }
    }
    
    
    section {
        background-color: white;
    }
    
    /*.sec1 {
        background-color: #2d3044;
        background-color: #1c1d25;
        height: 100vh;
        color: white;
        font-size: 40px;
    }
    */
    
    a {
        text-decoration: none;
        color: white;
    }
    
    /*h1 {
        font-size: 90px;
        margin: 0;
    }*/
    
    h2 {
        font-size: 50px;
    }
    
    
    p {
        margin: 0;
        font-size: 30px;
        font-weight: 300;
    }
    
    
    
    
    
    
    
    
    
    
    /*---------- Landing Page Info ------------------------------------------------------*/
    
    /*---------- Landing Page Info MQ ----------------------------------------------------------*/
    
    @media (min-width: 100px) and (max-width: 300px) {
    
        .sec-1 {
            padding: 30px 10px 0px 10px !important;
            margin-top: -17px !important;
            height: 400px !important;
        }
    
        .sec-1 > div > div {
            width: 230px !important;
        }
    
        :global(#col-list)  {
            margin-top: 5px !important;
        }
    
        :global(#col-list > li)  {
            font-size: 19px !important;
        }
    
        .sec-1 > div > div > h2 {
            font-size: 17px !important;
        }
    
        #descr-1 {
            font-size: 15px !important;
        }
        
        #descr-2 {
            font-size: 12px !important;
        }
        
        .first-area > p {
            padding: 0px 0px 0px 0px;
            font-size: 15px !important;
        }
        
        .button-1 {
            padding-top:  15px !important;
            width: 100px !important;
            height: 40px !important;
            font-size: 15px !important;
        }
    
        .button-2 {
            padding-top:  15px !important;
            width: 100px !important;
            height: 40px !important;
            font-size: 15px !important;
        }
    
        .sub-section {
            margin: 0px !important;
            padding: 15px !important;
            justify-content: center;
        }
    
        .information > h2 {
            font-size: 18px !important;
        }
    
        #sub1 {
            font-size: 15px !important;
            font-weight: 500 !important;
        }
    
        .sub-section > div > p {
            font-size: 14px !important;
            font-weight: 300 !important;
        }
    
        .sub-section-alternative > h2 {
            font-size: 20px !important;
        }
    
        .info {
            height: 360px !important;
        }
    
        section.sub-section-alternative > div > div > div > h3 {
            font-size: 18px !important;
        }
    
        section.sub-section-alternative > div > div > div > p {
            font-size: 15px !important;
        }
        
    }
    
    @media (min-width: 301px) and (max-width: 340px) {
    
        .sec-1 {
            padding: 30px 10px 0px 10px !important;
            margin-top: -17px !important;
            height: 50vh !important;
        }
    
        .sec-1 > div > div {
            width: 270px !important;
        }
    
        :global(#col-list)  {
            margin-top: 5px !important;
        }
    
        :global(#col-list > li)  {
            font-size: 21px !important;
        }
    
        .sec-1 > div > div > h2 {
            font-size: 20px !important;
        }
    
        #descr-1 {
            font-size: 15px !important;
        }
        
        #descr-2 {
            font-size: 15px !important;
        }
        
        .first-area > p {
            padding: 0px 0px 0px 0px;
            font-size: 20px !important;
        }
        
        .button-1 {
            padding-top:  15px !important;
            width: 100px !important;
            height: 40px !important;
            font-size: 15px !important;
        }
    
        .button-2 {
            padding-top:  15px !important;
            width: 100px !important;
            height: 40px !important;
            font-size: 15px !important;
        }
    
        .sub-section {
            margin: 0px !important;
            padding: 20px !important;
            justify-content: center;
        }
    
        .information > h2 {
            font-size: 22px !important;
        }
    
        #sub1 {
            font-size: 18px !important;
            font-weight: 500 !important;
        }
    
        .sub-section > div > p {
            font-size: 17px !important;
            font-weight: 300 !important;
        }
    
        .sub-section-alternative > h2 {
            font-size: 30px !important;
        }
        
    }
    
    @media (min-width: 341px) and (max-width: 440px) {
    
        .sec-1 {
            padding: 30px 10px 0px 10px !important;
            margin-top: -17px !important;
            height: 500px !important;
        }
    
        .sec-1 > div > div {
            width: 300px !important;
        }
    
        :global(#col-list)  {
            margin-top: 5px !important;
        }
    
        :global(#col-list > li)  {
            font-size: 16px !important;
        }
    
        .sec-1 > div > div > h2 {
            font-size: 25px !important;
        }
    
        #descr-1 {
            font-size: 16px !important;
        }
    
        #descr-2 {
            font-size: 15px !important;
        }
    
        .first-area > p {
            padding: 0px 0px 0px 0px;
            font-size: 20px !important;
        }
    
        .button-1 {
            width: 100px !important;
            height: 40px !important;
            font-size: 18px !important;
        }
    
        .button-2 {
            width: 100px !important;
            height: 40px !important;
            font-size: 18px !important;
        }
    
        .sub-section {
            margin: 0px !important;
            padding: 18px !important;
            justify-content: center;
        }
    
        .information > h2 {
            font-size: 20px !important;
        }
    
        #sub1 {
            font-size: 18px !important;
            font-weight: 500 !important;
        }
    
        .sub-section > div > p {
            font-size: 16px !important;
            font-weight: 300 !important;
        }
    
        .sub-section-alternative > h2 {
            font-size: 30px !important;
        }
    
    }
    
    @media (min-width: 370px) and (max-width: 420px) {
    
        .sec-1 > div > div {
            width: 340px !important;
        }
    
        .sec-1 > div > div > h2 {
            font-size: 25px !important;
        }
    }
    
    @media (min-width: 421px) and (max-width: 440px) {
    
        .sec-1 > div > div {
            width: 390px !important;
        }
    
        .sec-1 > div > div > h2 {
            font-size: 28px !important;
        }
    }
    
    @media (min-width: 441px) and (max-width: 480px) {
    
        .sec-1 > div > div {
            width: 390px !important;
        }
    
        .sec-1 > div > div > h2 {
            font-size: 28px !important;
        }
    }
    
    @media (min-width: 481px) and (max-width: 540px) {
    
        .sec-1 > div > div {
            width: 450px !important;
        }
    
        .sec-1 > div > div > h2 {
            font-size: 33px !important;
        }
    }
    
    @media (min-width: 441px) and (max-width: 540px) {
    
        .sec-1 {
            padding: 30px 10px 0px 10px !important;
            margin-top: -17px !important;
            height: 500px !important;
        }
    
        :global(#col-list)  {
            margin-top: 5px !important;
        }
    
        :global(#col-list > li)  {
            font-size: 21px !important;
        }
    
        #descr-1 {
            font-size: 18px !important;
        }
    
        #descr-2 {
            font-size: 17px !important;
        }
    
        .first-area > p {
            padding: 0px 0px 0px 0px;
            font-size: 22px !important;
        }
    
        .button-1 {
            width: 100px !important;
            height: 40px !important;
            font-size: 22px !important;
        }
    
        .button-2 {
            width: 100px !important;
            height: 40px !important;
            font-size: 22px !important;
        }
    
        .sub-section {
            margin: 0px !important;
            padding: 20px !important;
            justify-content: center;
        }
    
        .information > h2 {
            font-size: 22px !important;
        }
    
        #sub1 {
            font-size: 18px !important;
            font-weight: 500 !important;
        }
    
        .sub-section > div > p {
            font-size: 17px !important;
            font-weight: 300 !important;
        }
    
        .sub-section-alternative > h2 {
            font-size: 30px !important;
        }
    
    }
    
    @media (min-width: 450px) and (max-width: 540px) {
    
        .sec-1 {
            margin-top: 0px !important;
        }
    
    }
    
    @media (min-width: 541px) and (max-width: 640px) {
    
        .sec-1 {
            padding: 30px 10px 0px 10px !important;
            height: 500px !important;
        }
    
        .sec-1 > div > div {
            width: 515px !important;
        }
    
        .sec-1 > div > div > h2 {
            font-size: 38px !important;
        }
    
        #descr-1 {
            font-size: 22px !important;
        }
    
        #descr-2 {
            font-size: 20px !important;
        }
    
        .first-area > p {
            padding: 0px 0px 0px 0px;
            font-size: 22px !important;
        }
    
        .sub-section {
            margin: 0px !important;
            padding: 22px !important;
            justify-content: center;
        }
    
        .information > h2 {
            font-size: 22px !important;
        }
    
        #sub1 {
            font-size: 22px !important;
            font-weight: 500 !important;
        }
    
        .sub-section > div > p {
            font-size: 20px !important;
            font-weight: 300 !important;
        }
    
        .sub-section-alternative > h2 {
            font-size: 40px !important;
        }
    
    }
    
    @media (min-width: 641px) and (max-width: 920px) {
    
        .sec-1 {
            padding: 30px 10px 0px 70px !important;
            height: 600px !important;
        }
    
        .sec-1 > div > div {
            width: 515px !important;
        }
    
        .sec-1 > div > div > h2 {
            font-size: 38px !important;
        }
    
        #descr-1 {
            font-size: 22px !important;
        }
    
        #descr-2 {
            font-size: 20px !important;
        }
    
        .first-area > p {
            padding: 0px 0px 0px 0px;
            font-size: 27px !important;
        }
    
        .sub-section {
            margin: 0px !important;
            padding: 22px !important;
            justify-content: center;
        }
    
        .button-1 {
            padding-top:  17px !important;
            max-width: 250px !important;
            height: 70px !important;
        }
    
        .button-2 {
            padding-top:  17px !important;
            max-width: 250px !important;
            height: 70px !important;
        }
    
        .information > h2 {
            font-size: 22px !important;
        }
    
        #sub1 {
            font-size: 22px !important;
            font-weight: 500 !important;
        }
    
        .sub-section > div > p {
            font-size: 20px !important;
            font-weight: 300 !important;
        }
    
        .sub-section-alternative > h2 {
            font-size: 40px !important;
        }
    
    }
    
    /*---------- Landing Page Info MQ End ------------------------------------------------------*/
    
    .sec-1 {
        margin-top: 0px;
        background-color: #1c1d25;
        height: 100vh;
        color: white;
        font-size: 40px;
        padding: 100px 50px 0px 200px;
    
    }
    
    .sec-1 > div.landing-page-info > div {
        width: 700px;
    }
    
    /*--------- Main Logo ---------------*/
    
    @media (min-width: 1501px) {
    
        #main-logo {
            position: absolute;
            left: 1000px;
            top: 350px;
            z-index: 1;
            opacity: 0.5;
        }
    }
    
    @media (min-width: 1330px) and (max-width: 1550px) {
    
        #main-logo {
        position: absolute;
        scale: 0.7 !important;
        left: 800px !important;
        top: 350px;
        z-index: 1;
        opacity: 0.4;
        }
    
    }
    
    @media (min-width: 1000px) and (max-width: 1329px) {
    
        #main-logo {
        position: absolute;
        scale: 0.4 !important;
        left: 400px !important;
        top: 350px;
        z-index: 1;
        opacity: 0.3;
     }
    }
    
    @media (max-width: 999px) {
    
        #main-logo {
        display: none;
        }
    }
    
    /*--------- Main Logo End ---------------*/
    
    /*
    .socials {
        display: grid;
        justify-content: right;
        position: -webkit-sticky;
        position: sticky;
        top: 0;
        z-index: 3;
        margin: -400px 0px 0px 0px;
    }
    */
    /*
    #twitter {
        height: 70px;
        width: 70px;
        border-radius: 15px;
        background-color: #00aced;
    }
    
    #facebook {
        height: 70px;
        width: 70px;
        border-radius: 15px;
        background-color: #39569c;
    }
    
    #instagram {
        height: 70px;
        width: 70px;
        border-radius: 15px;
        background: linear-gradient(45deg, #405de6, #5851db, #833ab4, #c13584, #e1306c, #fd1d1d);
    }
    
    .socials > div > a > img:hover {
        height: 70px;
        width: 70px;
        background: #d6b18c !important;
        transition: ease-out 0.3 !important;
    }
    */
    
    .landing-page-info {
        max-width: 500px;
    }
    
    #descr-1 {
        font-size: 25px;
    }
    
    #descr-2 {
        font-size: 17px;
        color: rgba(255, 255, 255, 0.8)
    }
    
    .first-area {
        padding: 50px 0px 0px 0px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    
    .buttons {
        display: flex;
    }
    
    .button-1 {
        width: 200px;
        height: 55px;
        border-radius: 15px;
        background-color: rgba(255, 68, 0, 0.7);
        text-align: center;
        font-size: 30px;
        font-weight: 300;
        padding-top: 5px;
        margin: 10px 20px 0px 0px;
        cursor: pointer;
        z-index: 2;
    }
    
    .button-1:hover {
        background-color: #8b2c0c;
        transition: linear 0.1s;
        transform: scale(1.01);
    }
    
    .button-1:active {
        background-color: #A9A9A9;
        color: #808080;
    }
    
    .button-2 {
        width: 300px;
        height: 55px;
        border-radius: 15px;
        background-color: rgba(255, 255, 255, 0);
        box-shadow: 0px 0px 5px rgba(255, 255, 255);
        text-align: center;
        font-size: 30px;
        font-weight: 300;
        padding-top: 5px;
        margin: 10px 0px 0px 0px;
        cursor: pointer;
        z-index: 2;
    }
    
    .button-2:hover {
        background-color: rgba(111, 162, 255, 0.555);
        /*transition: cubic-bezier(0.075, 0.82, 0.165, 1) 0.5s;*/
        transition: ease-in-out 0.3s;
    }
    
    .button-2:active {
        background-color: rgb(44, 44, 44);
        color: #808080;
    }
    
    /*---------- Landing Page Info End ------------------------------------------------------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*---------- Content -----------------------------------------------------------*/
    
    /*
    .social {
        margin: 20px;
    }
    */
    
    .sub-section {
        display: flex;
        justify-content: space-around;
        padding: 80px;
    }
    
    .sub-section-alternative {
        display: flex;
        flex-direction: column;
        text-align: center;
        padding: 80px;
    }
     /*
    .headshot {
        width: 300px;
        border-radius: 150px;
        margin-left: 80px;
    }
    
    .headshot-container {
        display: flex;
        align-items: center;
    }
    
    hr {
        margin-left: 20px;
        margin-right: 20px;
    }
    */
    /*---------- Content End ------------------------------------------------------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*---------- Info Boxes ------------------------------------------------------*/
    
    .info-container {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    .info {
        width: 200px;
        height: 500px;
        padding: 30px 10px 5px 10px;
        box-shadow: 5px 5px 20px rgb(197, 195, 195);
        margin: 10px 20px 10px 20px;
        border-radius: 5px;
    }
    
    .info-image {
        width: 100px;
        height: 100px;
    }
    
    .info > div {
        border-color: black;
        padding: 10px 10px 10px 10px;
    }
    
    .info > div > p {
        font-size: 20px;
    }
    
    @media only screen and (min-width: 100px) and (max-width: 500px) {
        .info-container {
            display: grid;
            grid-template-columns: auto;
            justify-content: center;
        }
    }
    
    @media only screen and (min-width: 501px) and (max-width: 800px) {
        .info-container {
            display: grid;
            grid-template-columns: auto auto;
        }
    }
    
    @media only screen and (min-width: 801px) and (max-width: 1430px) {
        .info-container {
            display: grid;
            grid-template-columns: auto auto auto;
        }
    }
    
    /*---------- Info Boxes End ---------------------------------------------------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*-------*/
    /*---------- Footer --------------------------------------------------------*/
    
    
    
    
    
    
    
    
    
    
    
    /*---------- Footer End ----------------------------------------------------*/
    </style>
