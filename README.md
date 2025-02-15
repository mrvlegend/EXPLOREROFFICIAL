<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
   
  <style>
       body{
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    display: flex;
    justify-content: center;
    align-items: center;
    
    height: 100vh;
    margin: 0;
    

}
.container{
    background-color: white;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 90%; 
    max-width: 400px; 
}
.login h2 {
    margin-bottom: 20px;
    text-align: center;
}
label{
    display:block;
    margin-bottom: 10px;
}
button {
    width: 100%;
    padding: 10px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

}
    </style>
</head>
<body>
    <div class="container">
        <div class="login">
            <h2 >login</h2>
            <div class="entry">
                <label for="username" >user name</label>
                <input type="text" id="username" name="username"required>
            </div>
            <div class="entry">
                <label for="password" >user name</label>
                <input type="text" id="password"name="password" required>
            </div>
           <button type="submit">Login</button>
           </div>
           </div>
</body>
</html>
