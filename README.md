# Mini-project-web<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title> clearfix with pseudo after</title>
    <style>
    *{
        margin:0;
        padding:0;
        box-sizing:border-box;
    }
    body{
        text-align: center;
        font-size:30px;
    }
    .header{
        height:70px;
        background-color: rgb(255,217,102);
    }
    .article{
        height:200px;
        background-color: rgb(189,215,238);
        width:75%;
        float:left;
    }
    .sidebar{
        height:200px;
        background-color: rgb(197,224,180);
        width:25%;
        float:right;
    }
    .footer{
        height:80px;
        background-color: rgb(255,217,102);
    }
    /* .container::after{
        content:"";
        display:block;
        clear:both;
    } */
    .container{
        display:flow-root;
    }
    </style>
</head>
<body>
    <div class="header">header</div>
    <div class="container">
        <div class="article">article</div>
        <div class="sidebar">sidebar</div>
        
    </div>
    <div class="footer">footer</div>
</body>
</html>
