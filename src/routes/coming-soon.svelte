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
        <h1>Coming Soon ...</h1>
    </div>

    <Footer />

</main>

<style>

main {
    /* background-image: url("/img/logos/TransparentLogo.png"); */
    background-color: #1d1d3d;
    /* height: 1000px;
    background-position: center; 
    background-repeat: no-repeat; 
    background-size: cover; */
}    

        
.title {
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    margin-top: 50px;
    padding: 200px 50px 500px 50px;
    color: aliceblue;
}

h1 {
    font-size: 4em;
}
</style>