<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Profile</title>

    <style>
        body{
            margin:0;
            font-family: Arial, sans-serif;
            background:#0d1117;
            color:white;
            text-align:center;
        }

        .header{
            padding:40px 20px;
            background: linear-gradient(135deg,#1f2937,#111827);
            box-shadow:0 10px 30px rgba(0,0,0,0.5);
        }

        .header img{
            border-radius:50%;
            margin-bottom:15px;
        }

        .skills{
            margin-top:30px;
        }

        .skills img{
            margin:10px;
            transition:0.3s;
        }

        .skills img:hover{
            transform:scale(1.2);
        }

        .stats{
            margin-top:40px;
        }
    </style>
</head>

<body>

<!-- HEADER -->
<div class="header">

    <!-- GIF Avatar -->
    <div id="header">
        <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="120"/>
    </div>

    <h1>My GitHub Profile</h1>
    <p>Ya krutoy specialist!</p>

</div>

<!-- SKILLS -->
<div class="skills">

    <h2>⚡ Skills</h2>

    <img src="https://github.com/devicons/devicon/blob/master/icons/lua/lua-original.svg"
         title="LUA" width="40" height="40"/>

    <img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-plain-wordmark.svg"
         title="HTML" width="40" height="40"/>

    <img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-plain.svg"
         title="CSS" width="40" height="40"/>

</div>

<!-- STATS -->
<div class="stats">

    <h2>🔥 My Stats</h2>

    <a href="https://git.io/streak-stats">
        <img src="https://github-readme-streak-stats.herokuapp.com?user=kreadzs&theme=dracula&hide_border=true&short_numbers=true&date_format=j%2Fn%5B%2FY%5D"/>
    </a>

</div>

</body>
</html>
