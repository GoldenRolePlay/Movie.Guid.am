@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;600;700&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body{
    height: 100vh;
    background: linear-gradient(#1c1917 50%, #ffb92a 50%);
}

.container{
    font-size: 16px;
    width: 90vw;
    max-width: 37.5em;
    padding: 3em 1.8em;
    background-color: #1e293b;
    position: absolute;
    transform: translate(-50%, -50%);
    top: 50%;
    left: 50%;
    border-radius: 0.6em;
    box-shadow: 1.2em 2em 3em rgba(0, 0, 0, 0.2);
}

.search-container{
    display: grid;
    grid-template-columns: 9fr 3fr;
    gap: 1.2em;
}

.search-container input, .search-container button{
    font-size: 0.9em;
    outline: none;
    border-radius: 0.3em;
}

.search-container input{
    background-color: transparent;
    border: 1px solid #a0a0a0;
    color: #fff;
    padding: 0.7em;
}

.search-container input:focus{
    border-color: #fff;
}

.search-container button{
    background-color: #ffb92a;
    border: none;
    cursor: pointer;
}

#result{
    color: #fff;
}

.info{
    position: relative;
    display: grid;
    grid-template-columns: 4fr 8fr;
    margin-top: 1.2em;
}

.poster{
    width: 100%;
}

h2{
    text-align: center;
    font-size: 1.5em;
    font-weight: 600;
    letter-spacing: 0.06em;
}

.rating{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 0.6em;
    margin: 0.6em 0 0.9em 0;
}

.rating img{
    width: 1.2em;
}

.rating h4{
    display: inline-block;
    font-size: 1.1em;
    font-weight: 500;
}

.details{
    display: flex;
    font-size: 0.95em;
    gap: 1em;
    justify-content: center;
    color: #a0a0a0;
    margin: 0.6em 0;
    font-weight: 300;
}

.genre{
    display: flex;
    justify-content: space-around;
}

.genre div{
    border: 1px solid #a0a0a0;
    font-size: 0.75em;
    padding: 0.4em 1.6em;
    border-radius: 0.4em;
    font-weight: 300;
}

h3{
    font-weight: 500;
    margin-top: 1.2em;
}

p{
    font-size: 0.9em;
    font-weight: 300;
    line-height: 1.8em;
    text-align: justify;
    color: #a0a0a0;
}

.msg{
    text-align: center;
}

@media screen and (max-width: 600px) {
    .container{
        font-size: 14px;
    }
    .poster{
        margin: auto;
        width: auto;
        max-height: 10.8em;
    }

    .info{
        grid-template-columns: 1fr;
    }

}
