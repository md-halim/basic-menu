<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>menu</title>
    <style>
        *{
    margin:0;
    padding:0;
}
ul,ol{list-style-type:none;}
.menu{
    width:800px;
    height:200px;
    background-color:darkorange;
    margin:auto;
}
.menu ul li{
    float: left;
    position: relative;
}
.menu ul li a{
    color:black;
    display:block;
    font-size:14px;
    font-weight:bold;
    text-decoration:none;
    padding:12px 16px;
    text-transform:uppercase;   
}
.menu ul li a:hover{
    background-color:palevioletred;
}
/* create dropdown list */
.menu ul li ul{
    background-color:darkolivegreen;
    border-radius: 0px 5px 5px 5px;
    display: none;
    position: absolute;
    width:140px;
}
.menu ul li:hover ul{
    display:block;
}
.menu ul li ul li{
    width:100%;
   
}
.menu ul li ul a{
    color:white;
    border-radius:10px;
    font: 1em sans-serif;
    font-size:12px;
    padding-top:10px;    
}
    </style>
</head>
<body>
    <div class="menu">
        <ul>
            <li><a href="#">home</a></li>
            <li><a href="#">about</a></li>
            <li><a href="#">services</a>
                <ul>
                    <li><a href="#">data</a></li>
                    <li><a href="#">design</a></li>
                    <li><a href="#">economics</a></li>
                    <li><a href="#">management</a></li>
                    <li><a href="#">knowledge</a></li>
                </ul>    
            </li>
            <li><a href="#">blog</a></li>
            <li><a href="#">contact</a></li>
        </ul>
    </div>
</body>
</html>
