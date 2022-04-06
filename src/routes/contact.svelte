<script>
	
    import Navbar from "./comp library/Navbar.svelte";
    import Header from "./comp library/Header.svelte";
    import Footer from "./comp library/Footer.svelte";
    import Form from "./comp library/Form.svelte";
    import "../styles/global.css";
    
</script>
    
    
    
    
    
    
    
    
    
    
    <main>
        <Header />
        <Navbar />
        <div class="title"> 
            <h1>Send us a Message</h1>
        </div>

        <div class="sub-title">
            <p>Please do get in touch for a free 15 minute consultation meeting.
            <br/>We are happy to help you.</p>
        </div>
        <div class="add-form">
            <div class="address-container">
                <address>
                    <span>
                        Pl. de Uncibay, nº3
                        <br/>
                        1ª Planta Oficinas 2 y 3
                        <br/>
                        Málaga, Andalucia 29008
                        <br/>
                        Spain
                        <div class="info">
                            <p><a itemprop="email" href="mailto:info@berndteducation.com">info@berndteducation.com</a></p>
                            <p><a href="tel:+34631896435">+34 631896435</a></p>
                            <p><a href="tel:+447922489668">+447922489668</a></p>
                        </div>
                    </span>
                </address>
            </div>
            <Form />
        </div>
        <Footer />
    </main>
    
    







    
    <style>
    
    .title {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            margin-top: 150px;
            padding: 0px 50px 0px 50px;
    }

    .sub-title {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            margin-top: 20px;
            padding: 0px 50px 0px 50px;
    }

    @media (min-width: 50px) and (max-width: 300px) {
        h1 {
            font-size: 30px;
        }

        p {
            font-size: 15px;
        }
    }

    @media (min-width: 301px) and (max-width: 370px) {

        h1 {
            font-size: 40px;
        }

        p {
            font-size: 20px;
        }
    }

    @media (min-width: 371px) and (max-width: 449px) {

        h1 {
            font-size: 50px;
        }

        p {
            font-size: 20px;
        }
    }

    @media (min-width: 450px) and (max-width: 570px) {

        h1 {
            font-size: 70px;
        }

        p {
            font-size: 25px;
        }
    }

    @media (min-width: 1300px) {

        .add-form {
            display: flex;
            justify-content: center;
        }

        .address-container {
            display: flex !important;
            justify-content: center !important;
            margin: 150px 0px 0px 100px !important;
        }

        .info {
            margin: 0px;
            padding: 10px 0px 0px 0px !important;
        }

        .info > p {
            padding: 0px !important;
        }
        
    }

    .address-container {
        display: flex;
        justify-content: center;
        margin: 100px 0px 0px 0px;
    }

    address {
        text-align: left;
        margin-top: 150px;
    }

    address > span {
        text-align: left; 
        display: grid;
    }

    .info > p > a {
        margin: 0px;
        color: rgb(90, 90, 90);
        font-size: 13px;
        font-weight: 400;
    }

    .info > p {
        margin: 0px;
        font-size: 13px !important;
    }

    .info {
        padding: 10px 0px 0px 0px;
    }

    .info > p > a:hover  {
        color: #d6b18c;
    }
    
    </style>
