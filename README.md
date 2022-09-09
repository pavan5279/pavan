<!DOCTYPE html>   
<html>   
<head>  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<title> Login Page </title>  
<style>   
Body {  
  font-family: Calibri, Helvetica, sans-serif;  
  background-color: red;
  background-image:url(https://media.istockphoto.com/photos/fake-news-live-screen-template-on-digital-world-map-background-picture-id1174948330?k=20&m=1174948330&s=612x612&w=0&h=GpUTl_u35sg4-eciIR4oDyzd2Zj-UINXQBtGjmnLWaE=);   
}  
button {   
       background-color: #4CAF50;   
       width: 90%;  
        color: white;   
        padding: 15px;   
        margin: 15px 10px;

        border: none;   
        cursor: pointer;   
         } 
  
 form {   
        border: 0px solid #f1f1f1;   
    }   
 input[type=text], input[type=password] {   
        width: 30%;   
        margin: 4px 3px;  
        padding: 10px 12px;   
        display: inline-block;   
        border: 2px solid green;   
        box-sizing: border-box;   
    }  
 button:hover {   
        opacity: 0.9;   
    }   
  .cancelbtn {   
        width: auto;   
        padding: 5px 18px;  
        margin: 5px 5px; 
margin-right: auto;
    margin-left: auto; 
    }   
        
     
 .container {   
        margin: 5px;
        padding: 50px;
        width: 500px;
margin-right:auto;
    margin-left:auto;
           
        background-color: lightblue;  
    } 

</style>   
</head>    
<body>    
    <center> <h1 style="color:white"> PASSIVE AGGRESSIVE CLASSIFIER </h1> </center>   
    <form>  
        <div class="container">   
            <label>Username : </label>   
            <input type="text" placeholder="Enter Username" name="username" required> <br> 
            <label>Password : </label>   
            <input type="password" placeholder="Enter Password" name="password" required> <br> 
           
                
<button type="submit">Login</button>

   

<br>  
            <input type="checkbox" checked="checked"> Remember me   
            <button type="button" class="cancelbtn"> Cancel</button><br>
            Forgot <a href="#"> password? </a>   
        </div>   
    </form>     
</body>     
</html>  
