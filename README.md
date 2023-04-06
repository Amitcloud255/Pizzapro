<!DOCTYPE html>
<html>

<head>
    <title> Amit Food Point </title>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: o;
            backgrund: grey;
        }

        nav {
            background: #3f0303;
            width: 100%;
            overflow: auto;
        }

        ul {
            margin: 0;
            padding: 0;
            list-style: none;
        }

        li {
            float: left;
        }

        nav a {
            width: 120px;
            display: block;
            text-decoration: none;
            text-align: center;
            background: 594848;
            font-size: 17px;
            color: white;
            padding: 20px 10px;
            font-family: Arial;
        }

        .search-form {
            margin-top: 15px;
            float: right;
            margin-right: 100px;
        }

        input[type=text] {
            padding: 7px;
            border: none;
            font-size: 16px;
            font-family: sans-serif;
        }

        button {
            float: right;
            background: orange;
            color: white;
            border-radius: 0 5px 5px 0;
            cursor: pointer;
            position: relative;
            padding: 7px;
            font-family: sans-serif;
            border: none;
            font-size: 16px;
        }

        body {
            width: 100%;
            height: 100vh;
            background: black;
            overflow: hidden;
            cursor: url(cursor.png), auto;
        }

        img {
            position: absolute;
            bottom: 0;
            right: 0;
            width: 56%;
            animation: 2s animate ease-in-out;
        }

        @keyframes animate {
            0% {
                opacity: 0;
                transform: scale(.5);
            }

            100% {
                opacity: 1;
                transform: scale(1);
            }
        }

        ul {
            list-style: none;
            display: inline;
        }

        ul li {
            display: inline-block;
            padding: 30px;
            font-size: 20px;
            cursor: pointer;
        }

        .content {
            position: absolute;
            top: 27vh;
            left: 10%;
            width: 33%;
        }

        .content h1 {
            font-size: 60px;
        }

        hr {
            margin-top: 30px;
            width: 20%;
            height: 6px;
            background: rgb(250, 4, 4);
        }

        .content p {
            margin-top: 30px;
            font-size: 16px;
        }

        nav a:hover {
            background: rgb(38, 186, 245);
            color: rgb(179, 11, 11);
        }

        .search-form {
            margin-top: 15px;
            float: right;
            margin-right: 100px;
        }

        button {
            float: right;
            background: rgba(49, 238, 43, 0.712);
            color: white;
            border-radius: 0 5px 5px 0;
            cursor: pointer;
            position: relative;
            padding: 7px;
            font-family: sans-serif;
            border: none;
            font-size: 16px;
        }
    </style>
</head>

<body>
    <nav>
        <ul>
            <li><a href="Home.html"> Home</a></li>
            <li><a href="About.html"> About</a></li>
            <li><a href="Gallery.html"> Gallery</a></li>
            <li><a href="Contact Us.html"> Contact Us</a></li>
        </ul>

        <form class="search-form">
            <input type="text" placeholder="search">
            <button>search</button>
        </form>

    </nav>

    <div class="content">
        <h1 style="color: aliceblue;">don't waste your time any other shope</h1>
        <font size="50" color="white" face="bold">World's Best Pizza Point</font>
        <hr>
        <button>ORDER NOW</button>
    </div>

    <img align="right" width="300"
        src="https://c.ndtvimg.com/2021-02/bj6olj1o_pizza_625x300_20_February_21.jpg?im=FeatureCrop,algorithm=cascade,width=1200,height=675">

</body>

</html>
