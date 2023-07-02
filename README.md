index.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./main.css">
    <title>Document</title>
</head>

<body>

    <body>
        <div>
            <div class="wave"></div>
            <div class="wave"></div>
            <div class="wave"></div>
        </div>
    </body>

    <div class="container">
        <h1 class="heading text-center">Salom</h1>
        <p class="package text-center">Men Baxtiyorov Hamidulloxman</p>
        <div class="center">
            <p class="text">Men bir yildan beri veb-dizayn, front-end va back-end ishlab chiqish
                bilanshug'ullanaman.
                Sizga veb-sayt dizayni, sayt tartibi yoki ehtimol kalit taslim veb-sayt kerakmi?
                Keyin men bilan bog'laning</p>
            <h3 class="heading2 text-center">Men bilan ulanish</h3>
            <h3 class="smile text-center">👇👇👇</h3>
            <div class="center-2">
                <li class="item">
                    <a class="header_btn" href="tel:+998 94 557 35 58">+998 94 557 35 58</a>
                </li>
                <li class="insta_item">
                    <a class="insta_btn" target="_blank" href="https://www.instagram.com/_hamidull0x/">instagram</a>
                </li>
            </div>
        </div>
    </div>

</body>

</html>
_________________________________________________________________________________________________________________________________________
main.css

body {
    margin: auto;
    font-family: -apple-system, BlinkMacSystemFont, sans-serif;
    overflow: auto;
    background: linear-gradient(315deg, rgba(101, 0, 94, 1) 3%, rgba(60, 132, 206, 1) 38%, rgba(48, 238, 226, 1) 68%, rgba(255, 25, 25, 1) 98%);
    animation: gradient 15s ease infinite;
    background-size: 400% 400%;
    background-attachment: fixed;
}

@keyframes gradient {
    0% {
        background-position: 0% 0%;
    }

    50% {
        background-position: 100% 100%;
    }

    100% {
        background-position: 0% 0%;
    }
}

.wave {
    background: rgb(255 255 255 / 25%);
    border-radius: 1000% 1000% 0 0;
    position: fixed;
    width: 200%;
    height: 12em;
    animation: wave 10s -3s linear infinite;
    transform: translate3d(0, 0, 0);
    opacity: 0.8;
    bottom: 0;
    left: 0;
    z-index: -1;
}

.wave:nth-of-type(2) {
    bottom: -1.25em;
    animation: wave 18s linear reverse infinite;
    opacity: 0.8;
}

.wave:nth-of-type(3) {
    bottom: -2.5em;
    animation: wave 20s -1s reverse infinite;
    opacity: 0.9;
}

@keyframes wave {
    2% {
        transform: translateX(1);
    }

    25% {
        transform: translateX(-25%);
    }

    50% {
        transform: translateX(-50%);
    }

    75% {
        transform: translateX(-25%);
    }

    100% {
        transform: translateX(1);
    }
}

* {
    text-align: center;
    margin: 0px;
    padding: 0px;
    list-style: none;
}


.context {
    width: 100%;
    position: absolute;
    top: 50vh;

}

.context h1 {
    text-align: center;
    color: #fff;
    font-size: 50px;
}

.container {
    position: fixed;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100vw;
}

.text-center {
    text-align: center;
}

.text {
    color: aliceblue;
    max-width: 500px;
    text-align: center;
    margin: auto;
    margin-top: 20px;
}

.item {
    margin-top: 30px;
}

.header_btn {
    padding: 8px 16px;
    background: aquamarine;
    border-radius: 5px;
    text-decoration: none;
    color: white;
    font-family: sans-serif;
    margin-top: 30px;
}

.insta_btn {
    padding: 8px 16px;
    background: aquamarine;
    border-radius: 5px;
    text-decoration: none;
    color: white;
    font-family: sans-serif;
    margin-top: 50px;
}

.package {
    color: aliceblue;
    margin-top: 20px;
}

.heading {
    color: aliceblue;
    margin-top: 120px;
    text-align: center;
}

.heading2 {
    color: aliceblue;
    margin-top: 20px;
}


.smile {
    margin-top: 20px;
}

.center {
    width: 100vw;
}

.insta_item {
    margin-top: 50px;
}
