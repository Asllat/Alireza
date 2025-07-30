<!doctype html>
  <html>
  <head>
    <title>Alireza first website</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Zain:ital,wght@0,200;0,300;0,400;0,700;0,800;0,900;1,300;1,400&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playwrite+AU+QLD:wght@100..400&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap" rel="stylesheet">

  </head>
  <body style="margin-bottom:500px;margin-left:0px;padding-top:64px;padding-left:50px;">
    <style>
    .subscribe {background-color: rgb(200, 0, 0);
  color: white;
  border: none;
  height: 35px;
  width: 85px;
  margin-left:480px;
  border-radius: 50px;
  cursor:pointer;
  margin-right: 4px;
  transition: opacity 0.5s;
}
.subscribe:hover{background-color: rgb(400, 0, 0);
  color: black;
}
.subscribe:active{background-color: rgb(800, 0, 0);
  opacity: 0.8;
}
.join {background-color: rgb(999,999, 999);
  color: green;
  border: solid;
  height: 35px;
  width: 85px;
  border-radius: 5px;
  margin-left:480px;
  border-width: 2px;
  margin-right: 4px;
  cursor:pointer;
  transition: background-color 0.4s ‚ color 0.4s;
}
.join:hover{background-color: green;
  color: rgb(999,999, 999);
}
.join:active{opacity: 0.8;
}
.tweeter {background-color: rgb(2,135, 255);
  color: white;
  border: none;
  height: 35px;
  width: 85px;
  margin-left:480px;
  border-radius: 10px;
  font-weight:200;
  font-size:15px;
  cursor:pointer;
  transition: box-shadow 0.4s;
}
.tweeter:hover{box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.4);
}
.shop {color:yellow;
}
.shop:hover {text-decoration:underline;
}
.image1 {width:340px;
}
.image1-1 {width:340px;
  height:227px;
  object-fit:cover
}
.image2 {width:50px;
height:50px;
object-fit:cover;
border-radius: 500px;
}
.input1 {width:300px;
border-radius: 2px;
font-size:15px;
padding:2px;
margin-bottom:10px;
display:block;
}
.author {font-size:15px;
font-family:Roboto;
margin-bottom:2px;
}
.views2 {font-size:10px;
font-family:Roboto ;
color: rgb(96,96, 96);
}
.subject {font-size:20px;
  width:325px;
  margin-top:0;
  font-weight:700;
  line-height:28px;
}
.div1 {width:340px;
  psition:relative;
}
.full {display:grid;
  grid-template-columns:55px 1fr;}
.gridy{display:grid;
  grid-template-columns:1fr 1fr 1fr;
  row-gap:20px;
  column-gap:10px;
}
    @media (max-width : 400px){.gridy {grid-template-columns:1fr 1fr;}}
    @media (min-width : 1000px){.gridy {grid-template-columns:1fr 1fr 1fr 1fr;}}
    @media (min-width : 401px) and (max-width : 999px) {.gridy {grid-template-columns:1fr 1fr 1fr;}}
</style>
    <style class="header1">
    .input1 {width:300px;
border-radius: 10px;
font-size:15px;
padding:2px;
margin-bottom:10px;
margin-left:-20px;
margin-top:5px;
display:block;
height:23px;
border: solid 1px;
box-shadow:inset 1px 2px 1px rgba(0,0,0,0.2);
}
    .header {height:70px;
      display:flex;
      flex-direction:row;
      justify-content:space-between;
      width:1090px;
      position:fixed;
      background-color:rgb(999,999, 999);
      top:0;
      right:0;
      left:0;
      border-bottom:1px solid rgba(0,0,0,0.4);
    }
    .left-section {width:250px;
      display:flex;
      align-items:center;
    }
    .right-section {width:250px;
      display:flex;
      align-items:center;
      flex-shrink:0;
    }
    .middle-section{flex:1;
      padding:20px;
      align-items:center;
      max-width:300px;
      display:flex;
      margin-top:10px;
      margin-left:15px;
      width:0;
    }
    </style>
<style class="general"> 
    .text-title{direction: rtl;
  font-size: 18;
  font-weight: bold;
  margin-bottom:2px;
  text-align: center;
  font-family: Zain;
}
.offer{background-color: rgb(500,100, 50);
  color: rgb(999,999, 999);
  width:940px;
  padding-left:50px;
  padding-right:50px;
  border-radius: 2px;
  margin-top:50px;
  text-align: center;
}
    .intro{display:grid;
      width:1040px;
      text-align:center;
      margin-top:1080px;
    }
    .svg1{margin-top:5px;}
    .svg-youtube{height: 58px !important ;
      width:58px !important;
      margin-top:5px;
    }
    .search-icon{border-radius: 100px;
     background-color: rgb(999,999, 999);
      height:30px;
      width:30px;
      margin-bottom:10px;
      margin-top:5px;
      position:relative;
    }
    .microphone{border-radius: 100px;
     background-color: rgb(999,999, 999);
      height:28px;
      margin-top:5px;
      width:28px;
      margin-bottom:10px;
      --fa-animation-duration:2s;
    --fa-fade-opacity:0.5;}
    .svg-square {margin-top:5px;
       margin-left:80px;
    }
    .bell {height:40px;
      width:40px;
      margin-left:5px;
    }
    .camera {height:58px;
      width:58px;
      margin-left:0px;
      margin-top:10px;
    }
    .profile {height:50px;
      width:50px;
      margin-left:0px;
      margin-top:5px;
      border-radius: 100px;
      object-fit:cover;
    }
    .side-bar{position:fixed;
      background-color:rgb(999,999, 999);
      top:0;
      bottom:0;
      left:0;
      width:50px;
    margin-top:71px;}
    .video-time{position:absolute;
      top:270px;
      margin-left:290px;
      z-index:1;
      color:white;
      background-color: rgba(0,0,0,0.7);
      border-radius: 2px;
      padding:2px;
      font-family: Roboto,arial;
    }
    .bell-container{position:relative;
      width:45px;
      height:45px;
      margin-top:14px;
    }
    .bell-number{position:absolute;
      background-color:rgb(175,0, 0);
      border-radius: 100px;
      padding:2px 6px;
      font-size:14px;
      top:0px;
      right:0px;
    }
    .video-time1 {position:absolute;
      top:270px;
      margin-left:295px;
      z-index:1;
      color:white;
      background-color: rgba(0,0,0,0.7);
      border-radius: 2px;
      padding:2px;
      font-family: Roboto,arial;}
    .sidebar-link{height:55px;
      margin-bottom:2px;
    }
    .sidebar-link:hover {background-color: rgba(0,0,0,0.1);}
    .home {margin-left:-4px;}
    .compass {margin-left:5px;
      margin-top:7px;
    }
    .p-home{font-size:5px;
      margin-top:-15px;
      margin-left:13px;
    }
    .p-compass{font-size:5px;
      margin-top:-4px;
      margin-left:11px;}
    .subscriptions{margin-left:-2px;
      margin-top:0px;}
    .p-subscriptions{font-size:5px;
      margin-top:-14px;
      margin-left:1px;}
    .youtube-music{margin-left:1px;
      margin-top:3px;}
    .p-youtube-music {font-size:5px;
      margin-top:-6px;
      margin-left:7px;}
    .library {margin-left:-1px;
      margin-top:3px;}
    .p-library {font-size:5px;
      margin-top:-13px;
      margin-left:11px;}
    .searching{font-size:5px;
      position:absolute;
      top:30px;
      left:-1px;
      z-index:5;
      background-color: rgba(0,0,0,0.1);
      padding:1px;
      border-radius:1px;
      opacity:0;
      pointer-events:none;
    }
    .search-icon:hover .searching{opacity:1;}
    .open-mic {font-size:5px;
      position:absolute;
      top:55px;
      left:647px;
      z-index:5;
      background-color: rgba(0,0,0,0.1);
      padding:1px;
      border-radius:1px;
      opacity:0;
      pointer-events:none;}
    .microphone:hover .open-mic{opacity:1;}
</style>
    <div class="header">
      <div class="left-section"><svg class="svg1"width="50" height="50" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M4 6H20" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M4 12H20" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
<path d="M4 18H20" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
<svg class="svg-youtube" width="32px" height="32px" viewBox="0 0 32 32" id="icon" xmlns="http://www.w3.org/2000/svg"><defs><style>.cls-1{fill:none;}</style></defs><title>logo--youtube</title><path d="M29.41,9.26a3.5,3.5,0,0,0-2.47-2.47C24.76,6.2,16,6.2,16,6.2s-8.76,0-10.94.59A3.5,3.5,0,0,0,2.59,9.26,36.13,36.13,0,0,0,2,16a36.13,36.13,0,0,0,.59,6.74,3.5,3.5,0,0,0,2.47,2.47C7.24,25.8,16,25.8,16,25.8s8.76,0,10.94-.59a3.5,3.5,0,0,0,2.47-2.47A36.13,36.13,0,0,0,30,16,36.13,36.13,0,0,0,29.41,9.26ZM13.2,20.2V11.8L20.47,16Z"/><rect id="_Transparent_Rectangle_" data-name="&lt;Transparent Rectangle&gt;" class="cls-1" width="32" height="32"/></svg>
</div>
        <div class="middle-section"><input class="input1" type="text" placeholder="search&#128269">
          <button class="search-icon"><i class="fa-solid fa-magnifying-glass"></i><div class="searching">Search</div></button>
          <button class="microphone"><i class="fa-solid fa-microphone fa-fade"></i><div class="open-mic">Search with your voice</div></button>
        </div>
        <div class="right-section">
          <svg class="svg-square" xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
  <rect x="2" y="2" width="5" height="5" />
  <rect x="9.5" y="2" width="5" height="5" />
  <rect x="17" y="2" width="5" height="5" />
  <rect x="2" y="9.5" width="5" height="5" />
  <rect x="9.5" y="9.5" width="5" height="5" />
  <rect x="17" y="9.5" width="5" height="5" />
  <rect x="2" y="17" width="5" height="5" />
  <rect x="9.5" y="17" width="5" height="5" />
  <rect x="17" y="17" width="5" height="5" />
</svg>
          <div class="bell-container">
            <svg class="bell"xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
  <path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"></path>
  <path d="M13.73 21a2 2 0 0 1-3.46 0"></path>
</svg>
            <div class="bell-number">4</div>
            </div>
<svg class="camera" width="100" height="100" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
  <!-- بدنه اصلی دوربین -->
  <rect x="15" y="25" width="50" height="30" rx="5" stroke="black" stroke-width="3"/>

  <!-- لنزهای دوربین -->
  <circle cx="28" cy="15" r="10" stroke="black" stroke-width="3"/>
  <circle cx="52" cy="15" r="10" stroke="black" stroke-width="3"/>

  <!-- جلوی دوربین (ذوزنقه) - ضلع بزرگتر به سمت جلو -->
  <path d="M65 30L85 25L85 50L65 45Z" stroke="black" stroke-width="3" stroke-linejoin="round"/>

  <!-- نقاط روی بدنه دوربین -->
  <circle cx="20" cy="40" r="2" fill="black"/>
  <circle cx="25" cy="40" r="2" fill="black"/>
  <circle cx="30" cy="40" r="2" fill="black"/>

  <!-- پایه‌های دوربین -->
  <path d="M40 55L30 80" stroke="black" stroke-width="3" stroke-linecap="round"/>
  <path d="M60 55L70 80" stroke="black" stroke-width="3" stroke-linecap="round"/>
</svg>
          <img class="profile" src="/storage/emulated/0/Pictures/Telegram/IMG_20250728_133526_087.jpg">
</div>
    </div>
    <div class="side-bar">
      <div class="sidebar-link"><svg class="home" width="55" height="55" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
  
<rect x="25" y="45" width="50" height="30" fill="#000000"/>

  
<polygon points="25,45 75,45 50,25" fill="#000000"/>

  
<rect x="45" y="60" width="10" height="15" fill="#FFFFFF"/>
        <p class="p-home">Home</p>
</svg>
</div>
      <div class="sidebar-link"><svg class="compass" width="37" height="37" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg">
  <circle cx="30" cy="30" r="28" stroke="black" stroke-width="4"/>
  
  <path d="M44 16 L34 34 L16 44 L26 26 Z" fill="black"/>
  
  <circle cx="30" cy="30" r="3" fill="white"/>
</svg>
        <p class="p-compass">Explore</p>
</div>
      <div class="sidebar-link"><svg class="subscriptions"width="50" height="50" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect x="10" y="15" width="40" height="30" rx="10" ry="10" fill="black"/>
  
  <path d="M26 25 L36.5 30 L26 35 Z" fill="white"/>
</svg>
        <p class="p-subscriptions">Subscriptions</p>
</div>
      <div class="sidebar-link"><svg class="youtube-music"width="44" height="44" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg">
  <circle cx="30" cy="30" r="25" fill="black"/>
  
  <circle cx="30" cy="30" r="20" stroke="white" stroke-width="1.5" fill="none"/>
  
  <path d="M26 22 L40 30 L26 38 Z" fill="white"/>
</svg>
        <p class="p-youtube-music">YT Music</p>
</div>
      <div class="sidebar-link"><svg class="library" width="50" height="50" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
  <rect x="25" y="25" width="50" height="50" rx="1" ry="1" fill="black" stroke="black" stroke-width="2"/>
  <path d="M42 37L62 50L42 63Z" fill="white"/>
</svg>
        <p class="p-library">Library</p>
</div>
    </div>
    <div class="gridy">
      <div class="div1">
<div><img class="image1" src="/storage/emulated/0/Download/nothing-headphone-1-68642389881b5331b393fbe6.webp">
</div>
        <div class="video-time">10:10</div>
<div class="full">
  <div class="pic2div"><img class="image2" src="/storage/emulated/0/Pictures/Telegram/IMG_20250725_142208_494.jpg">
</div>
  <div class="info-div"><p class="subject"><strong>Nothing</strong> first head phone is incredible</p>
<p class="author">Alireza Abyari</p>
<p class="views2">8.5k view &#183 7 days ago</p>
</div>
</div>
</div>
    <div class="div1">
<div><img class="image1" src="/storage/emulated/0/Pictures/Telegram/IMG_20250726_193653_896.jpg">
</div>
      <div class="video-time1">8:18</div>
<div class="full">
  <div class="pic2div"><img class="image2" src="/storage/emulated/0/Pictures/Telegram/IMG_20250726_193342_413.jpg">
</div>
  <div class="info-div"><p class="subject"><strong>The orange girl</strong> story contains effective narration</p>
<p class="author">Fz Noori</p>
<p class="views2">5.4k view &#183 2 weeks ago</p>
</div>
</div>
</div>
      <div class="div1">
<div><img class="image1-1" src="/storage/emulated/0/Pictures/arcane-jinx-hd-wallpaper-uhdpaper.com-164@2@c.jpg">
</div>
        <div class="video-time">15:45</div>
<div class="full">
  <div class="pic2div"><img class="image2" src="/storage/emulated/0/Pictures/Telegram/IMG_20250726_203631_117.jpg">
</div>
  <div class="info-div"><p class="subject"><strong>Arcane season2</strong> details made a fanstic reaction from the fans</p>
<p class="author">Mah Ryan</p>
<p class="views2">2.1k view &#183 5days ago</p>
</div>
</div>
      </div>
      </div>
    <div class="intro">
<p class="text-title"> به سایت من خوش اومدین:)</p> 
<a href="https://tabdeal.org" target="blank">payment</a>
<button class="subscribe">subscribe</button>
<button class="join">join</button>
<button class="tweeter">tweeter</button>
<p class="offer"><u>80%</u> <b>special offer</b> for <i>holiday</i> <span class="shop">shop now &#128722</span></p>
      </div>
</body>
</html>
