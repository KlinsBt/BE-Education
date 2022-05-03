<script>

	import "../styles/global.css";
    import Navbar from "./comp library/Navbar.svelte";
    import Header from "./comp library/Header.svelte";
    import Footer from "./comp library/Footer.svelte";
    import EmployeeCard from "./comp library/EmployeeCard.svelte";

    //src={"img/DennyProfil.jpg"}
    
</script>
    
    
    
    
    
    
    
    
    
    
    <main>
        <Header />
        <Navbar />
        <div class="title"> 
            <h1>The BE Team</h1>
        </div>
        <div class="sub-title">
            <p>We help you achieve your goals</p>
        </div>
        <EmployeeCard />
        <div class="logo-container">
            <div>
                <p>Collaboration with:</p>
                <a href="https://www.sada-center.org/"><img src="/img/logos/Sada.png" alt="Sada-Logo"></a>
            </div>
        </div>
        <br>
        <Footer />
    </main>
    
    







    
    <style>

        .title {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            margin-top: 150px;
            padding: 0px 50px 10px 50px;
        }

        .sub-title {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            margin-top: 20px;
            padding: 0px 50px 100px 50px;
        }

        .logo-container {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .logo-container > div {
            display: grid;
        }

        .logo-container > div > p {
            font-size: 15px !important;
            font-weight: 500 !important;
        }

        .logo-container > div > a > img {
            width: 150px;
            height: 100px;
            cursor: pointer;
            transition-duration: 0.4s;
        }

        .logo-container > div > a > img:hover {
            transform: scale(1.02);
            transition-duration: 0.4s;
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
    
    </style>
