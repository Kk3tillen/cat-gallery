<template>
    <div>
        <header>
            <div>
                <img id="name" src="../imgs/name.svg" alt="" srcset="">
            </div>
            
            <nav>
                <ul>
                    <li class="conteudo-nav"><a href="sobre">Sobre</a></li>
                    <li class="conteudo-nav"><a href="http://localhost:3000">Galeria</a></li>
                    <li class="conteudo-nav"></li>
                </ul>
            </nav>  
        </header>
        <nuxt/>
        <footer>
            <p>by Kezitta :D</p>
        </footer>
    </div>
</template>


<style>
@import url('https://fonts.googleapis.com/css2?family=Concert+One&display=swap');
    header{
        height: 5rem;
        padding: 25px;
        height: 3rem;
        background-color: rgb(219, 217, 217);
        color: rgb(63, 69, 75);
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    ul{
        display: flex;
        padding: 25px;
        gap: 35px;
    }
    #name{
        width: 200px;
    }
    nav{
        font-family: "Concert One", sans-serif;
        font-weight: 400;
        font-style: normal;
    }
    a{
      text-decoration: none;
      color: rgb(126, 126, 126);
    }
    .conteudo-nav{
        list-style: none;  
    }
    footer{
        padding: 25px;
        height: 4rem;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: rgb(46, 45, 49);
        color: aliceblue;
    }
    #nome{
      width: 250px;
    }
    h1{
        font-family: "Roboto", sans-serif;
        font-weight: 900;
        font-style: normal;
    }
    #mode{
        width: 25px;
    }
    #cat{
        width: 25px;
    }
</style>