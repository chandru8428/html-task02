
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>admin page</title>
    <link rel="stylesheet" href="task.css">
</head>
<body>
    <center>
        <h1 style="display: inline-flex; align-content: center;">CONTECT US</h1>
     </center>
     <center>
        <div class="form">
             <center> 
            <h1>contect us</h1>
            <input type="name" placeholder="Enter your name here">
            <input type="name" placeholder="Enter your number">
            <input type="number"  placeholder="Enter age here">
            <input type="email" placeholder="Enter Email id">
            <button class="btrn"><a href="#">send massage</a></button>
            <h1>our contect No:98765432</h1>
        </center>
       </div>
       </center>
        </body>
        <style>
           h1{
    font-family: 'Times New Roman', Times, serif;
    font-weight: bolder;
    font-size: 39px;
    color: rgba(215, 49, 7, 0.803);
    margin-bottom: 600px;
    }
body {
    background-image: url(bg.jpg);
    background-size: cover;
    background-blend-mode: color-burn;
    display: flex;
    justify-content: center;   
    align-items: center;       
    min-height: 100vh;         
    margin: 0;                 
}
.form {
    width: 340px;
    height: 410px;
    background: linear-gradient(to top, rgba(0, 0, 0, 0.8) 50%, rgba(0, 0, 0, 0.8) 50%);
    display: flex;
    flex-direction: column;     
    align-items: center;         
    justify-content: center;      
    border: 3px groove;
    padding: 20px;
}
.form h1{
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    text-align: center;
    color: #de1212;
    width: 220px;
    font-size: 22px;
    background-color: aliceblue;
    border-radius: 30px;
    margin: 2px;
    padding: 8px;
}
.form input{
    background: transparent;
    width: 240px;
    height: 28px;
     border-bottom: 1px solid  #de1212;
     border-top: none;
     border-left: none;
     border-right: none;
     color: aliceblue;
     font-size: 10px;
     letter-spacing: 1px;
     margin-top: 25px;
     font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.form input :focus{
    outline: none;
}
::placeholder{
    color: aliceblue;
    font-family: arial;
}
.btrn{
    width: 240px;
    height: 40px;
    background: #de1212;
    margin-top: 26px;
    font-size: 16px;
    border-radius:10px;
    cursor: pointer;
    color: rgb(235, 239, 242);
    transition: 0.4s ea;
}
.btrn :hover{
    background: #f3f6f7;
    color: #de1271;
    width: 240px;
    height: 40px;
}
.btrn a{
    text-decoration: none;
    color: black;
    font-weight: bold;
}
.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    text-align:center;
    padding-top:20px
}
.form .link a{
    text-decoration:none;
    color: #de1212;
} 
        </style>
         </html>
