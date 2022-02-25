# GYM-Registration-Form.github.io
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width = device - width, initial - scale = 1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <tittle> Mrudu's Fitness Center</tittle>
</head>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin" rel="stylesheet">
<link rel="stylesheet" href="css/style.css">
<style>
    body {
        font-family: 'Baloo Bhaina 2', cursive;
        color: white;
        margin: 0px;
        padding: 0px;
        background: url("https://t3.ftcdn.net/jpg/02/63/86/60/360_F_263866080_R8lSdWRbIPrLfxTUyHkU8yEwAi7vLmhd.jpg")
    }

    .left {
        display: inline-block;
        border: 2px solid antiquewhite;
        position: absolute;
        left: 31px;
        top: 33px;
    }

    .left img {
        width: 65px;
        align-items: center;
    }

    .left div {
        line-height: 23px;
        font-size: 20px;
        text-align: center;
    }

    .mid {
        display: block;
        width: 40%;
        margin: 20px auto;
        border: 2px solid antiquewhite;


    }

    .right {
        position: absolute;
        right: 34px;
        top: 20px;
        display: inline-block;
        border: 2px solid antiquewhite;
    }

    .navbar {
        display: inline-block;
    }

    .navbar li {
        display: inline-block;
        font-size: 25px;
    }

    .navbar li a:hover,
    .navbar li a:active {
        text-decoration: underline;
        color: grey;
    }

    .btn {
        font-family: 'Baloo Bhaina 2', cursive;
        margin: 0px 9px;
        background-color: black;
        color: white;
        padding: 4px 14px;
        border: 2px solid grey;
        border-radius: 10px;
        font-size: 20px;
        cursor: pointer;
    }

    .btn:hover {
        background-color: rgb(14, 12, 12);
    }

    .container {
        border: 2px solid antiquewhite;
        margin: 8px 99px;
        padding: 129px 221px;
        width: 42%;
        border-radius: 13px;
    }

    .form-group input {
        font-family: 'Baloo Bhaina 2', cursive;
        text-align: center;
        display: block;
        width: 508pxpx;
        padding: 1px;
        border: 2px solid black;
        margin: 11px auto;
        font-size: 25px;
        border-radius: 8px;

    }

    .container h1 {
        text-align: center;
    }

    .container button {
        display: block;
        width: 74%;
        margin: 20px auto;
    }
</style>

<body>
    <header class="header">
        <div class="left">
            <img src="https://i.pinimg.com/564x/6b/1c/7f/6b1c7ffd10f05827f244c3f0746f6509.jpg">
            <div>Mrudu's Fitness</div>

        </div>
        <div class="mid">
            <ul class="navbar">
                <li> <a href="#" class="active">Home </a></li>
                <li> <a href="#"> About Us</a></li>
                <li> <a href="#">Fitness calc </a></li>
                <li> <a href="#">Contact Us </a></li>
            </ul>

        </div>
        <div class="right">
            <button class="btn"> Call Us Now</button>
            <button class="btn"> Email Us</button>
        </div>
    </header>
    <div class="container">
        <h1>join the best gym now</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type=" text" name="" placeholder="enter your Name ">
            </div>
            <div class="form-group">
                <input type=" text" name="" placeholder="enter your Age ">
            </div>
            <div class="form-group">
                <input type=" text" name="" placeholder="enter your Gender ">
            </div>
            <div class="form-group">
                <input type=" text" name="" placeholder="enter your Locality ">
            </div>
            <button class="btn">submit</button>
        </form>
    </div>

</body>

</html>
