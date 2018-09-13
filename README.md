# HTML5
Just learn HTML5 on W3school
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <div style="text-align:cennter;">
        <button onclick="playPause()">播放/暂停</button>
        <button onclick="makeBig()">大</button>
        <button onclick="makeNormal()">中</button>
        <button onclick="makeSmall()"小></button>
    </br>
    <video id="videol" width="420" style="margin-top:150px;">
        <sourse src="/example/html5/mov_bbb.ogg" type="video/ogg"/>
        Your browser does not support HTML5 video.
    </video>
    <script type="text/javascript">
    var myVideo=document.getElementById("videol");
    function playPause()
    {
        if (myVideo.paused)
            myVideo.play();
        else
            myVideo.plause();
    }
    function makeBig()
    {
        myVideo.width=560;
    }
    function makeSmall()
    {
        myVideo.width=320;
    }
    function makeNormal()
    {
        myVideo.width=420;
    }
    </script>
    </div> 
    
</body>
</html>
