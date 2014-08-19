movieznow
=========
<!DOCTYPE html>
<html lang="en" class="no-js">
  <head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
   
    <link href='http://fonts.googleapis.com/css?family=Kreon:300,400,700' rel='stylesheet' type='text/css'>
   
    <title>
      {Title}
    </title>
    <link rel="shortcut icon" href="{Favicon}">
    <link rel="alternate" type="application/rss+xml" href="{RSS}">
    {block:Description}
    <meta name="description" content="{MetaDescription}" />
    {/block:Description}
   
   
    <style type='text/css'>
  /***************** SCROLLBAR ********************/
 
      ::-webkit-scrollbar-thumb:vertical {
        border-left:2px solid #f8f8f8;
        border-right:2px solid #f8f8f8;
        border-top:0;
        border-bottom:0;
        background-color:#0a0a0a;
        height: 7px;
      }
      ::-webkit-scrollbar-thumb:horizontal {
        background-color:#0a0a0a;
        height:7px!important;
        border-top:2px solid #f8f8f8;
        border-bottom:2px solid #f8f8f8;
        border-left:0;
        border-right:0;
      }
      ::-webkit-scrollbar {
        background-color:#f8f8f8;
        height:7px;
        width:7px;
      }
     
    /***************** GENERAL *******************/
     
      body{
        background-color:#f8f8f8;
        color:#000;
        font-family:calibri;
        font-size:10px;
        background-attachment:fixed;
        background-repeat:repeat;
        text-align:justify;
      }
     
      .content{
        width:1065px;
        margin:auto;
        background:#trans;
        margin-top:150px;
      }
     
   .content a {
        color:#fff;
        text-decoration:none;
    }
.content a:hover{
color:#FF0000}
  .sfm input {background-color: #f5f5f5; 
    font-size: 8px; 
    border: 0px; 
    text-transform: uppercase; 
    margin-top: 0px; 
    color: #999; 
    letter-spacing: 1px; 
    padding: 4px 8px;
    font-family: cambria;}

.words {
color: #000;
margin-left:100px}
.words a {
color:#000;
text-decoration:none;

font-family:cambria;
text-transform:uppercase}
.words a:hover {
letter-spacing:2px;
color:#FF0000}





 /********************* HEADER **********************/
     
      header {
        text-align: justify;
        padding:0;
        background: #0a0a0a;
        color: #fff;
        width:100%;
        height:130px;
        position:fixed;
        top:0;
        left:0;
        font-family:kreon;
        font-weight:300;
        z-index:10000000;
      }
     
     
      header::after {
        content: '';
        display: inline-block;
        width: 100%;
      }
     
      header > div,
      header nav,
      header div h1 {
        display: inline-block;
        vertical-align: middle;
        margin:0;
        padding:0;
      }
     
      header > div {
        width: 50%;
        height: 100%;
        text-align: left;
      }
     
      header > div::before {
        content: '';
        display: inline-block;
        vertical-align: middle;
        height: 100%;
      }
     
      header div h1{
        text-transform:uppercase;
        letter-spacing:1px;
        font-size:30px;
        margin-left:22%;
      }
     
      header nav{
        font-size:13px;
        text-transform:uppercase;
        margin-right:10%;
      }
      header nav a{
        margin-right:15px;
        padding:10px 0px;
        border-top:0px solid #0a0a0a;
        border-bottom:4px solid #0a0a0a;
        -webkit-transition:all 0.5s ease-in-out;
        -o-transition:all 0.5s ease-in-out;
        -moz-transition:all 0.5s ease-in-out;
        transition:all 0.5s ease-in-out;
        text-decoration:none;
        color:#fff;
      }
     
      header nav a:hover{
        padding:4px 0px;
        border-color:#fff;
      }
     
      header div h1 span{
        font-size:8px;
        font-weight:300;
        line-height:8px;
        display:block;
        letter-spacing:2px;
      }
     
     
      @media screen and (max-width:766px){        
        header > div,
        header > div h1,
        header nav {
          height: auto;
          width: auto;
          display: block;
          text-align: center;
          margin:10px 0px!important;
        }
       
        .content, .film-grid{
          width:auto;
          max-width:638px;
          margin:auto;
        }
       
        .content{
        margin-top:150px;
        }        
    }
 
    @media screen and (min-width:767px) and (max-width:950px){
        header > div,
        header > div h1,
        header nav {
            height: auto;
            width: auto;
            display: block;
            text-align: center;
            margin:10px 0px!important;
            }
   
        .content, .film-grid{
            width:auto;
            max-width:851px;
            margin:auto;
        }
   
        .content{
            margin-top:150px;

        }
.conten
    }
 
  </style>
<!------------------------ SCRIPTS ------------------------->
 
  <script src="http://code.jquery.com/jquery-latest.js">
  </script>
  <script type="text/javascript">
    $(window).load(function(){
      $('.film').click(function () {
        var $t = $(this);
        $t.siblings().css("z-index", 1);
        if ($t.css("z-index") == 1)
          $t.css("z-index", 2).find('.onclickstuff').addClass('scaleup').removeClass('hide'),
            $t.siblings().find('.onclickstuff').addClass('hide').removeClass('scaleup');
        else
          $t.css("z-index", 1).find('.onclickstuff.scaleup').removeClass('scaleup').removeClass('hide'),
            $t.siblings().find('.hide').removeClass('hide'),
              $t.siblings().find('.scaleup').removeClass('scaleup');
      }
                      );
    }
                  );
  </script>
  </head>
 
  <body>
    <div class="content">


  <!------------------------- HEADER ----------------------------->
      <header>
        <div>
          <h1>
            <a href="/">moviez now</a><embed src="http://www.sheepproductions.com/billy/billy.swf?autoplay=true&f0=http://landsofkes.legendsofkesmai.com/community_files/misc/Psycho%20uploading%20for%20ICOL/Rupert%20Holmes%20-%20Escape%20(The%20Pina%20Colada%20Song).mp3&t0=&total=1" quality="high" wmode="transparent" width="200" height="10" name="billy" align="middle" type="application/x-shockwave-flash" />  <!-------- CHANGE YOUR TITLE ---------->
            <span>

              movies. now. yay! <!----- CHANGE YOUR DESCRIPTION/LEGEND/INSTRUCTIONS ---->
            </span>
          </h1>
        </div>
        <nav>    <!----------------- NAVIGATION LINKS ------------------>
          <a href="/">
            browse
          </a>
          <a href="/genres">
            genres
          </a>
          <a href="/new">
            new arrivals
          </a>
          <a href="/account">
            account
          </a>
          <form action="/search" method="get" class="sfm">
    <input type="text" name="q" value="{Search}" id="sf"/>
    <input type="submit" value=">>" id="sb"/>
</form>
        </nav>
      </header>
</div>

     <div class="words"><p><div style="font-family:kreon; font-size:64px;">Genres:</div></p>
<div style="font-size:35px"><li><a href="/tagged/action" color="#D8D8D8">action</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/scifi" color="#D8D8D8">science fiction</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/drama" color="#D8D8D8">drama</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/romance" color="#D8D8D8">romance</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/comedy" color="#D8D8D8">comedy</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/thriller" color="#D8D8D8">thriller</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/crime" color="#D8D8D8">crime</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/fantasy" color="#D8D8D8">fantasy</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/adventure" color="#D8D8D8">adventure</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/musical" color="#D8D8D8">musical</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/children" color="#D8D8D8">children</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/mystery" color="#D8D8D8">mystery</a></li></div>     
<div style="font-size:35px"><li><a href="/tagged/horror" color="#D8D8D8">horror</a></li></div>
<div style="font-size:35px"><li><a href="/tagged/animation" color="#D8D8D8">animation</a></li></div>
     
     
     

     
     
     
     
     
     
     
     



