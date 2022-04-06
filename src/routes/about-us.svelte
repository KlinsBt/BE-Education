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
            <h1>Our Team</h1>
        </div>
        <div class="sub-title">
            <p>Some text about the team.</p>
        </div>
        <EmployeeCard />
        <Footer />
    </main>
    
    







    
    <style>

        .title {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            margin-top: 50px;
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
