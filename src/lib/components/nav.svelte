<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">    
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200"/>
</svelte:head>

<nav class="barra">
    <img id="logo" src="./logo.jpg" alt="logo">

    <h1 class="nav_titolo">Il mio triennio nell'istituto Agnelli</h1>

    <ul>
        <div class="bottone" id="icona"><a href="./"><li><span class="material-symbols-outlined">home</span></li></a></div>
        <div class="bottone"><a href="./anno1"><li>2021/2022</li></a></div>
        <div class="bottone"><a href="./anno2"><li>2022/2023</li></a></div>
        <div class="bottone"><a href="./anno3"><li>2023/2024</li></a></div>
    </ul>
</nav>

<style>
    nav {
        display: flex;
        justify-content:space-between;
        border-radius: 15px;
        width: 100%;
        height: 104px;
        background-color:aliceblue;
        border: 1px solid black;
    }

    #logo {
        width: 226px;
        height: 104px;
        border-radius: 15px;
        margin-top: 0%; 
    }

    a {
        text-decoration: none;
    }

    .nav_titolo {
        font-size: 1.9vw;
        font-family: 'Dancing Script', cursive;
        margin-left: 3%;
        color: red;
    }
        
    nav ul {
        list-style-type: none;
        width: 55%;
        display: flex;
        justify-content: right;
        font-size: 1.2vw;
    }

    .bottone {
        background-color: rgb(215, 62, 62);
        border-radius: 10px;
        text-align: center;
        line-height: 250%;
        width: 10rem;
        font-weight: bold;
        margin-right: 2.4%;
    }

    .bottone a {
        color: white;
        font-size: 1vw;
    }

    #icona {
        width: 5rem;
    }

    .material-symbols-outlined{
        vertical-align: -30%;
    }

    .bottone:hover {
        background-color: white;
        transition: all 0.8s ease 0s;
        border: 1px solid red;
        cursor: pointer;
    }

    .bottone:hover a {
        color: red;
        transition: all 0.5s ease 0s;
    }
</style>