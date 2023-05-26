# GRID.HTMl 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grid</title>
    <style>
        .cont{
            display: grid;
            grid-template-columns: 500px 500px 500px;
            grid-template-rows: 1fr 1fr 1fr;
            grid-template-areas: "header header header"; 
            height: 500px;
        }
        .box{
            /* height: 100px;
            width: 100px; */
            margin: 2px;
        }
        .box1{
            justify-self: auto;
            background-color: #111111;
            grid-area: "header header header";
        }
        .box2{
            background-color: #d31111;
        }
        .box3{
            background-color: #7cdf0c;
        }


    </style>
</head>
<body>
    <div>
        <div class="cont">
          <div class="box box1"></div>
          <div class="box box2"></div>
          <div class="box box3"></div>
          <div class="box box1"></div>
          <div class="box box2"></div>
          <div class="box box3"></div>
          <div class="box box1"></div>
          <div class="box box2"></div>
          <div class="box box3"></div>
        </div>
    </div>
</body>
</html>
