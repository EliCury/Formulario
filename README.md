HTML
```
<html>
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
            <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
                <link href="https://fonts.googleapis.com/css2?family=Lato:ital@1&display=swap" rel="stylesheet">
        <link href = "css/style.css" rel="stylesheet" />
        <title>Modulo Css</title>
    </head>
    <body>
    <div class ="form"> 
        <img src="riot.jpg" alt="">
        <input type="text" name="nome" placeholder="Seu nome..." />
        <input type="email" name="nome" placeholder="Seu nome..." />
        <textarea placeholder="Sua mensagem..."></textarea>
        <input type="submit" value="Enviar" />
    </div><!--form-->
    </body>
    </html> 
```

CSS
```
*{
    margin : 0;
    padding: 0;
    box-sizing: border-box;
    
}
body{
    background-color: #a30c1d;
}
.form{
    padding: 20px;
    text-align: center;
}
.form img{
    max-width: 600px;
    width: 100%;
}
.form input[type=text],
.form input[type=email]{
    padding-left:10px;
    display: block;
    border-radius: 20px;
    margin: 10px auto;
    font-size: 16px;
    max-width: 500px;
    width: 100%;
    height: 35px;
    border: 1px solid #ccc;
}
.form textarea{
    padding: 10px;
    resize: vertical;
    display: block;
    border-radius: 20px;
    margin: 10px auto;
    font-size: 16px;
    max-width: 500px;
    width: 100%;
    height: 120px;
}
.form input[type=submit]{
    padding-left:10px;
    display: block;
    border-radius: 20px;
    margin: 10px auto;
    font-size: 16px;
    max-width: 500px;
    width: 100%;
    cursor: pointer;
    color: white;
    background-color: rgb(143, 1, 107);
    height: 35px;
    border: 0;
}
