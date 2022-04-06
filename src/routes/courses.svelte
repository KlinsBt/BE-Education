<script>
	
    import Navbar from "./comp library/Navbar.svelte";
    import Header from "./comp library/Header.svelte";
    import Footer from "./comp library/Footer.svelte";
    import Course from "./comp library/Course3.svelte";
    import "../styles/global.css";
    
</script>
    
    
    
    
    
    
    
    
    
    
    <main>
        <Header />
        <Navbar />
        <div class="title"> 
            <h1>Our Courses</h1>
        </div>

        <div class="sub-title">
            <p>Here you can see our course catalog.</p>
                </div>
        <div class="boxes">
            <Course />
        </div>
        <Footer />
    </main>
    
    







    
    <style>

    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: "Poppins",sans-serif;
    }

    .boxes {
        margin: 100px 0px 50px 0px;
        display: flex;
        justify-content: center;
        /*display: grid;
        grid-template-columns: auto auto auto;*/
    }
    
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
    
    </style>