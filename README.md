<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="out.css">
</head>
<body>
    <div id="box">
        <h1>hello</h1>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium consectetur veniam illum blanditiis aliquid in eligendi, cupiditate exercitationem corporis optio quisquam. Maiores, tenetur consequatur quo ab voluptatibus sint distinctio aspernatur?


    </div>
    <div id="secthion">
        <h2>wellcam</h2>
    </div>
    <div id="class">
        <h3>bad boy</h3>
    </div>
    <div id="intro"> 
        <div id="master1"></div>
        <div id="master2"></div>
        <div id="master3"></div>
    </div>
        
    
    <div id="footer">footer

    </div>
</body>
</html>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;

}
body
{
    box-sizing: border-box;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;

}
div{
    border: 3px solid rgb(20, 20, 18);
}
#box{
    width: 100%;
    height: 100px;
    background-color: aqua;
    
    
}
#secthion{
    width: 100%;
    height: 100px;
    background-color: blue;
}
#class{
    width: 100%;
    height: 150px; ;
    background-color:coral ;
}

#intro{
  width: 100%;
  height: 30vh;
  background-color: antiquewhite;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
#intro div {
    width: 33.33%;
    height: 30.33 vh;
    background-color:yellow;
}
#footer{
    width: 100%;
    height: 150px; ;
    background-color: magenta;
}
