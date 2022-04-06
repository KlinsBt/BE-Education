<script>
  
//import { prevent_default } from "svelte/internal";


</script>










<main>

  <div class="container">
    <h2>Write Us</h2>
    <form action="">
        <input type="email" name="email" id="email" placeholder="Enter your email">
        <input type="text" name="name" id="name" placeholder=" enter your name">
        <textarea name="message" id="message" cols="35" rows="10" placeholder="Enter your message here"></textarea>
        <input type="submit" value="Send">
    </form>
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

    h2 {
      font-size: 30px;
      padding: 20px;
    }

    .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 500px;
        margin: 15vh auto;
        padding: 15px;
        border-radius: 15px;
        border: none;
        box-shadow: 0 0 15px rgb(122, 122, 122);
        /* background-color: gray; */
    }
        
    form {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 90%;
    }
        
    input {
        width: 100%;
        margin: 10px 0px;
        height: 35px;
        font-size: 17px;
        text-align: center;
        padding: 10px;
        outline: none;
        border-radius: 15px;
        border: none;
        background: rgb(235, 228, 228);
    }
        
    textarea {
        width: 100%;
        margin: 20px 0px;
        padding: 10px 20px;
        font-size: 17px;
        text-align: center;
        outline: none;
        border-radius: 15px;
        border: none;
        background: rgb(235, 228, 228);
    }

    input[type=submit] {
        margin: 12px;
        width: 120px;
        height: 50px;
        padding-bottom: 10px;
        background: #e95217;
        color: rgb(255, 255, 255);
        cursor: pointer;
    }

    @keyframes change {
      from {background: #e95217;}
      to {background: #d6b18c;}
    }

    input[type=submit]:hover {
        /*background: #d6b18c;*/
        background: #a8380c;
        transform: rotate(2deg);
        transition: ease 0.4s;
        transform: change;
    }

    @media screen and (max-width:600px) {
        .container{
            width: 90%;
        }
    }

</style>