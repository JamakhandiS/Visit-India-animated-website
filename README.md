# Visit-India-animated-website
It is css and html based project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=
    , initial-scale=1.0">
    <title></title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Gloria+Hallelujah&family=Josefin+Sans:wght@100;400&family=Lemonada&family=Merriweather&family=Reem+Kufi&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="C:\Users\jamakhandi\design.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo"> <h1 class="animated infinite pulse" > Mera Bharat</h1></div>
            <div class="menu">
                <a href="#">Home</a>
                <a href="https://www.google.com/search?q=images+of+india&oq=Images+of+In&aqs=chrome.1.69i57j0i512l9.7926j0j7&sourceid=chrome&ie=UTF-8">gallery</a>
                <a href="#">contact</a>
                <a href="https://www.google.com/search?q=about+india&oq=abouti&aqs=chrome.1.69i57j0i10i512j0i512j0i10i512j46i175i199i512j46i10i512j0i10i512l4.5211j0j7&sourceid=chrome&ie=UTF-8" target="_blank">about</a>
            </div>
        </nav>

            <main>
                <section>
                    <h2>Welcome to India </h2>
                    <h1>DO COME & VISIT <span class="change_contet">  </span> </h1>
                    <p>"India once is not enough"</p>
                    <a href="#" class="b1"> learn more </a>
                    <a href="#" class="b2"> signup here </a>
                </section>
            </main>
    </header>
</body>
</html>


#CSS code

*{
    margin: 0;padding:0; box-sizing: border-box;
    font-family: 'Merriweather', serif;
}

header{
    width: 100%; height: 100vh;
    background-image: linear-gradient(rgba(0, 0, 0, 0.3),rgba(0, 0, 0, 0.1)), url('C:/Users/jamakhandi/Downloads/travel.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}
nav{
    width: 100%; height: 15vh;
   /* background-color: rgb(122, 154, 168); */
    color: rgb(255, 255, 255); display: flex; justify-content: space-between;
    align-items: center; text-transform: uppercase;
}

nav .logo{
    width: 25%; text-align: center;
    letter-spacing: 2px;
    word-spacing: 2px;
}
nav .menu{
    width: 40%; text-align: center;
    display: flex; justify-content: space-around;
}

nav .menu a{
    width: 25%;
    text-decoration: none; color: white;
    font-weight: bold;
}
/* nav .menu a:first-child{
    color: aquamarine;
} */

main{
    width: 100%; height: 75vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: black;
}

section{
}
section h2{
    font-size: 40px; font-weight: 200; letter-spacing: 3px;
    text-shadow: 1px 1px 2px black;
}
section h1{
    margin: 30px 0 20px 0;
    font-size: 55px;
    font-weight: 700;
    text-shadow: 2px 1px 5px black;
    word-spacing: 2px;
    text-transform: uppercase;
}

section p{
    font-size: 25px;  word-spacing: 2px;
    margin-bottom: 25px;
    text-shadow: 1px 1px 1px black;
}

section a{
    padding: 12px 30px;
    border-radius: 4px;
    outline: none;
    text-transform: uppercase;
    font-size: 13px;
    font-weight: 500;
    text-decoration: none;
    letter-spacing: 1px;
    transition: all .4s ease;
}
section .b1{
    padding: 10px 15px;
    background: white;
    color: black;
}
.b1:hover{
    background:rgb(163, 160, 160);
    color: black;
}

section .b2{
    padding: 10px 15px;
    background: aquamarine;
    color: black;
}
.b2:hover{
    background: rgb(168, 189, 182);
    color: black;
}

.change_contet:after{
    content:'';
    animation: changetext 10s infinite linear;
    color: aquamarine;
}

@keyframes changetext{
    12.5%{content:"Kashimr";}
    25%{content:"Mumbai";}
    37.5%{content:"Agra";}
    50%{content:"kanyakumari";}
    62.5%{content:"Jaipur";}
    75%{content:"Aandaman-Nikobar";}
    87.5%{content:"Kerala";}
    100%{content:"Goa";}
}



