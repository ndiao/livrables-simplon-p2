# Tutoriel HTML/CSS
## Les balises de base
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Gmail</title>
    <link rel="stylesheet" href="untitled.css">
    <script src="untitled.js"></script>
</head>
<body>

    <div id="sidebar">
        <img id="mn" src="index.png" alt="" srcset="">
        <img id="mm" src="gmail-logo.jpg" alt="" srcset="">
        
        <div class="toggle-btn" onclick="toggleSidebar()">
            <span></span>
            <span></span>
            <span></span>
        </div>
            <ul> 
                <li>Boite de réception</li>
                <li>Messages suivis</li>
                <li>En attente</li>
                <li>Messages envoyés</li>
                <li>Brouillons</li>
                <li>Unwanted</li>
            </ul>
    </div> 
  </body>
</html>
