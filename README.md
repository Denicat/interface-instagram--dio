*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    text-decoration: none;
    font-family: sans-serif;
    font-size: 14px;
}

body{
    width: 100%;
    min-height: 100vh;
    background-color: rgb(243, 243, 243);
    margin: 0px;
    padding: 0px;
    display: flex;
    justify-content: center;
}

.instagram-wrapper{
    display: flex;
    align-items: center;
    justify-content: start;
    width: 60%;
    height: 100vh;
}

.instagram-telefone{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 50%;
}

.instagram-telefone img{
    height: 50rem;
}

.instagram-continue{
    display: flex;
    align-items: center; /* horizontal */
    justify-content: space-around; /* vertical */
    flex-direction: column;
    width: 50%;
    min-height: 34rem;
}

.primeiros-grupos{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    background-color: #ffffff;
    width: 100%;
    padding: 1.3rem 0;
    border: 1px solid lightgrey;
}

.primeiros-grupos:nth-child(1) {
    min-width: 19rem;
}

.instagram-logo{
    height: 3rem;
}

.foto-perfil{
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    overflow: hidden;
}

.foto-perfil img{
    height: 6rem;
}

.instagram-login{
    background-color: #0095f6;
    color: #ffffff;
    padding: 8px;
    border-radius: 4px;
}

.instagram-logout{
    color: #0095f6;
    margin-top: 1rem;
}

.nao-e-sua-conta{
    color: rgb(160, 160, 160);
}

.link-blue{
    color: #0095f6;
}

.get-the-app{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    padding: 1.3rem 0;
}

.download{
    display: flex;
    width: 100%;
    justify-content: space-evenly;
    align-items: center;
    padding: 1rem;
}

.app-download{
    height: 3rem;
    width: 10rem;
    background-size: cover;
}

.app-download:nth-child(1){
    background-image: url(./apple-button.png);
}
 
.app-download:nth-child(2){
    background-image: url(./googleplay-button.png);
}
   
/* media queries */


@media (max-width: 1024px) {
    .instagram-wrapper{
        width: 90%;
    }
}

@media (max-width: 650px){
    body{
        background-color: #ffffff;
    }
    .instagram-wrapper{
        width: 90%;
    }

    .instagram-telefone{
        display: none;
    }

    .instagram-continue{
        width: 100%;
    }

    .group{
        border: 1px solid transparent;
    }
}

    
    
    
    
    
    
    
    
     



