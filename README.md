# Web page for gym
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>national Gym</title>
    <link rel="project.css" href="" class="css">

    <style>
        body {
            color: white;
            margin: 0px;
            padding: 0px;
            background: url('image1.jpg');
            font-family: 'Baloo Bhai 2', cursive;
            background-repeat: no-repeat;
            background-size: cover;
        }

        .left {
            position: absolute;
            left: 34px;
            top: 10px;
            display: inline-block;
            /* border: 2px solid red; */



        }

        .left img {
            width: 81px;
            margin: 19px;
            text-align: center;
        }

        .left div {
            text-align: center;
            line-height: 0px;
            font-size: 18px;
        }

        .mid {
            display: block;
            width: 43%;
            margin: 5px auto;
            /* border: 2px solid green;  */


        }

        .right {
            position: absolute;
            right: 34px;
            top: 10px;
            display: inline-block;
            /* border: 2px solid yellow; */

        }

        .btn {
            margin: 8px 9px;
            color: white;
            background-color: black;
            padding: 0px 17px;
            border: 2px solid grey;
            border-radius: 10px;
            font-size: 18px;
            cursor: pointer;
            font-family: 'Baloo Bhai 2', cursive;
        }

        .btn:hover {
            background-color: rgb(79, 84, 84);
        }

        .navbar {
            display: inline-block;
        }

        .navbar li {

            display: inline-block;

        }

        .navbar li a {
            color: white;
            text-decoration: none;
            padding: 15px;
            font-size: 21px;
        }

        .navbar li a:hover,
        .navbar li a.active {
            text-decoration: underline;
            color: gray;

        }

        .container {
            border: 2px solid white;
            margin: 119px 166px;
            padding: 35px 83px;
            width: 33%;
            border-radius: 12px;

        }

        .form-group input {

            text-align: center;
            display: block;
            width: 423px;
            padding: 5px;
            font-size: 13px;
            margin: 5px auto;
            border-radius: 14px;
            font-family: 'Baloo Bhai 2', cursive;

        }

        .container h1 {
            text-align: center;
        }

        .container button {
            display: block;
            width: 25%;
            height: 34px;
            border-radius: 16px;
            margin: 14px auto;
        }
    </style>
</head>
<link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&display=swap" rel="stylesheet">

<body>

    <head class="header">
        <div class="left">
            <img src="image2.jpg" alt="" class="image">
            <div>National Fitness</div>
        </div>
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact us</a></li>
            </ul>
        </div>
        <div class="right">
            <button class="btn">Call us now</button>
            <button class="btn">e-mail</button>
        </div>
    </head>
    <div class="container">
        <h1>Join the Best gym in Bihar Now</h1>
        <form action="noaction.php" method="post">
            <div class="form-group">
                <input type="text" name="Name" placeholder="Enter your name" id="">
                <input type="text" name="Name" placeholder="Enter your Age" id="">
                <input type="text" name="Name" placeholder="Enter your Gender" id="">
                <input type="text" name="Name" placeholder="Enter your Locality" id="">
                <button type="submit">Submit</button>
            </div>
        </form>
    </div>

</body>

</html>
