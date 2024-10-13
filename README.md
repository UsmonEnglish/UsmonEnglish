<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Video Playlist</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000000;
            color: #000000;
            position: relative;
        }

        .header {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0px;
            background-color: #000000;
            box-shadow: 0 0px 0px rgba(0, 0, 0, 0.1);
            z-index: 100; /* Ensure header is above other content */
        }

        .logo {
            width: 60px;        
            height: 40px;
        margin-left: 8px;
        }
       
        .logo-container {
            display: flex;
            align-items: center;
        }

        .logo-text {
            margin-left: 20px;
            font-weight: bold;
            font-size: 1.4em;
            color: #030303;
        }

        .search-bar {
    display: flex;
    align-items: center;
    margin-right: 10px; /* Adjust according to the width of the logo */
}
 
            .search-input {
            padding: 10px;
            margin-right: 10px;
            width: 100px;
            border: 1px solid #ccc;
            border-radius: 20px;
            outline: none;
            font-size: 1em;
        }

        button {             
            padding: 1px;
            background-color: #ffffff          ;
            color: #000000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 2em;          
        }    

        .video-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 20px;
            padding: 0px;
            margin-top: 70px; /* Adjust to avoid overlap with fixed header */
        }

        .video-embed {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 aspect ratio */
            overflow: hidden;
        }

        .video-embed iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        .buttons {
            display: flex;
    align-items: center;
    margin-right: 100px;
            position: fixed;
            bottom: 0px; /* Adjust as needed */
            left: 0px; /* Adjust as needed */
            display: flex;
            z-index: 0; /* Ensure buttons are on top of other content */
            background: #000000; /* Optional background color for better visibility */
            padding: 10px;
           padding-right: 500px;
            border-radius: 1px;
            box-shadow: 0 0px 150px rgba(0, 0, 0, 0.4);
        }

        .buttons button {
            margin-left: 33px;
                                  
        }      
    </style>
</head>

<body>
    <div class="header">
        <div class="logo-container">
            <img class="logo" src="https://i.postimg.cc/xTBfCmwQ/Picsart-24-03-12-09-24-19-156.png" alt="Your Logo">
            <p class="logo-text">SomoiFilm</p>
        </div>
        <div class="search-bar">
            <input type="text" class="search-input" placeholder="  Кино Поиск">
            <button>
        <i class="fas fa-search search-icon"></i>
    </button>
        </div>
    </div>

    <div class="video-container">
        <div class="video-embed">
            <iframe width="0" height="315" src="https://www.youtube.com/embed/QCSLxQVyrW0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <div class="video-embed">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/uKl7qYN71uE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <div class="video-embed">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/5hxos30I2zw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
        <div class="video-embed">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/uKl7qYN71uE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>
        <div class="buttons">
        <button class="youtube-button"><i class="icon fab fa-youtube"></i></button>
         <button>
        <i class="fas fa-search search-icon"></i>
    </button>
    <style>
        .circular-button {
            display: inline-block;
            width: 44px;
            height: 44px;
            background-color: #ffeaff;
            color: #000000;
            border: none;
            border-radius: 50%; /* Makes the button circular */
            font-size: 20px;
            cursor: pointer;
            display: flex;
            justify-content: center;
            align-items: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .video-icon {
            font-size: 24px;
        }
    </style>
</head>

<body>
    <button class="circular-button">
        <i class="""></i>
    </button>    
       <button class="youtube-button"><i class="icon fas fa-language"></i></button>
        <button class="youtube-button"><i class="icon fas fa-user"></i> </button>
    

    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/js/all.min.js"></script>
</body>
</html>
