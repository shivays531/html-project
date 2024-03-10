<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .outbox {
            border: 2px solid grey;
            box-shadow: 20px 25px 50px;
            width: 500px;
            height: 800px;
            margin-top: 50px;
            margin-left: 100px;
            border-radius: 20px;
            font-family: Arial, Helvetica, sans-serif;


            /* background-color: yellow; */
        }

        .gtr {
            /* position: relative; */
            width: 480px;
            height: 400px;
            border-radius: 20px;
            margin: 10px;
            /* padding: 0px; */
            background-color: yellow;
        }

        .CAR {
            border: 1px solid grey;
            /* background-color: yellow; */
            display: inline-block;
            position: relative;
            left: 50px;
            border-radius: 20px;
            padding: 5px;
            color: grey;
        }

        .nissan {
            display: inline-block;
            position: relative;
            left: 80px;
            border: 1px solid grey;
            border-radius: 20px;
            padding: 5px;
            color: grey;
        }

        H1 {
            /* border: 2PX solid; */
            margin: 20px;
            margin-top: 30px;
        }

        p {
            margin: 20px;
        }

        ul {
            padding: 20px;
            margin: 20px;
        }

        a {
text-align: center;
            /* border: 2px solid; */
            position: relative;
            left: 200px;
            text-decoration: none;
            color: rgba(19, 19, 222, 0.92);
            border: 1px solid red;
            border-radius: 20px;
            padding: 5px;
            background-color: rgb(255, 141, 141);

        }
        .button{
            text-align: center;
        }
        a:link{
            color: rgb(42, 139, 223);
        }
        

        /* a:active {
            color: black;
            background-color: black;
        } */

        a:visited {
            color: chartreuse;
        }
        a:hover{
            color: red;
            background-color: rgb(216, 183, 183);
        }
        
    </style>
</head>

<body>
    <div class="outbox"><img src="GTR.jpeg" alt="gtr" width="460px" class="gtr">
        <div class="CAR"> CAR</div>
        <div class="nissan"> NISSAN GTR</div>
        <div class="heading">
            <H1>Nissan GTR R35</H1>
            <p>Nissan GT-R price starts at Rs. 2.12 Crores(ex-showroom Noida) and it comes with 3799cc engine.The
                mileage is 8.4kmpl with a <b>petrol</b> typed fuel tank capacity of <b>74 litres</b>. </p>
            <ul>Other details:
                <li>Seating capacity - 4</li>
                <li>Tansmission Type - automatic</li>
            </ul>
        </div>
        <a href="https://www.nissanusa.com/vehicles/sports-cars/gt-r.html" class="button"><b>Read More</b></a>
    </div>

</body>

</html>
