<!DOCTYPE HTML> 
<html> 
  
<head> 
    <title> 
        Pubg Poster
    </title>     
</head> 
  
<body id = "body" style = "text-align:center;"> 
      
    <h1 style = "color:yellow;" > 
        Final Overall standings
    </h1> 
      
    <p id = "Pubg_UP" style = 
            "font-size: 15px; font-weight: bold;"> 
    </p> 
      
    <button onclick = "Pubg_Click()"> 
        click here 
    </button> 
      
    <p id = "Pubg_DOWN" style = 
            "color:Yellow; font-size: 20px; font-weight: bold;"> 
    </p> 
      
    <script> 
        var up = document.getElementById('Pubg_UP'); 
        up.innerHTML = "Click on the button to add image element"; 
        var down = document.getElementById('Pubg_DOWN'); 
          
        function Pubg_Click() {
            var img = document.createElement('img');
            img.src = 
'file:///C:/Users/Pavilion/Downloads/picture1.jpeg';
            document.getElementById('body').appendChild(img);
            down.innerHTML = ""; 
        } 
    </script> 
</body> 
  
</html>
