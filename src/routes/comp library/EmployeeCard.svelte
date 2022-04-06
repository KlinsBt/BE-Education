<script>

    //export let name = ""
    //export let title = ""
    //export let description = ""
    //export let src = "img/DennyProfil.jpg"

</script>

<main>

    <div class="card">
        <div class="circle">
            <div class="imgBox">
                <img src="img/DennyProfil.jpg" alt="Profile">
            </div>
        </div>
        <div class="content">
            <h3>Denny Berndt</h3>
            <div class="textIcon">
                <h4>CEO</h4>
            </div>
            <div>
                <p>I’m the founder of Berndt Education. I’m originally from Germany and have 
                    a B.A. in Technical Translation and an M.A. from Texas Tech University in 
                    German Literature & Language with a minor in Spanish Literature. I have specialized 
                    in language education, school and education program management as well as curriculum 
                    development for language and also for children with disabilities.</p>
            </div>
        </div>
    </div>

    <div class="card" id="custom1">
        <div class="circle">
            <div class="imgBox">
                <img src="img/SophieProfile.jpg" alt="Profile">
            </div>
        </div>
        <div class="content">
            <h3>Anne-Sophie</h3>
            <div class="textIcon">
                <h4>Teacher</h4>
            </div>
            <div>
                <p ><!---style="font-size: 9px !important"--->I am a trained translator who graduated from the French Institute of Translation 
                   and Cross-Cultural Management (ISIT) after 5 years of studying German and English 
                   literature, language, and culture in Paris, Vienna, and Munich. I moved to Berlin 
                   about 3 years ago, where I had the opportunity to make amazing connections in Germany 
                   and to work within German and international teams as a translator in the luxury market. 
                   Meanwhile, I started teaching German and French to expats and language enthusiasts as a 
                   freelancer. I will be happy to support you on your learning path, whether you are new to 
                   German and French or aiming for perfect fluency."</p>
            </div>
        </div>
    </div>

</main>

<style>

    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: "Poppins",sans-serif;
    }

    main {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        min-height: 100vh;
        width: 100%;
        /*background: radial-gradient(#777,#1C1D25);*/
    }

    .card {
        position: relative;
        width: 340px;
        height: 700px;
        background: #fff;
        overflow: hidden;
        border-radius: 10px;
        margin: 20px;
        box-shadow: 1px 1px 15px 1px rgb(160, 157, 157);
    }

    .circle {
        position: absolute;
        top: -190px;
        left: 50%;
        width: 500px;
        height: 500px;
        transform: translateX(-50%);
        clip-path: circle();
    }
    .circle::before {
        content: '';
        position: absolute;
        top: -8px;
        left: -16px;
        width: 100%;
        height: 100%;
        box-shadow: 0 0 0 20px rgba(214,177,140,0.7);
        border-radius: 50%;
        z-index: 2;
        pointer-events: none;
    }

    .imgBox {
        position: absolute;
        left: 50%;
        bottom: 0;
        transform: translateX(-50%);
        width: 340px;
        height: 310px;
    }

    img {
        position: absolute;
        top: 0;
        left: 0;
        object-fit: cover;
        width: 100%;
        height: 100%;
        transition: all 0.5s;
    }

    .content {
        position: absolute;
        left: 0;
        bottom: 0;
        width: 100%;
        height: 350px;
        padding: 0px 20px;
    }

    h3 {
        font-size: 1.4em;
        color: #333;
        margin-top: 7px;
        margin-bottom: 2px;
    }

    .textIcon {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
    }

    h4 {
        color: #d6b18c;
        font-weight: 400;
    }

    p {
        padding: 20px 0px 0px 0px;
        font-size: 11px;
        font-weight: 400;
    }

    @media (min-width: 250px) and (max-width: 340px) {

        #custom1 {
            height: 800px;
        }

        #custom1 > .circle > .imgBox > img {
            width: 290px !important;
        }

        #custom1 > .content {
            height: 450px;
        }

    }



    
</style>