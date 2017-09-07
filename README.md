<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>切换背景图片</title>
<link href="css/css.css" rel="stylesheet" type="text/css">
</head>

<body>
	
    <div class="head">
        <img src="image/img11.jpg" id="photo1">
        <img src="image/img10.jpg" id="photo2">
        <img src="image/img1.jpg" id="photo3">
        <img src="image/img7.jpg" id="photo4">
        <img src="image/img6.jpg" id="photo5">
    </div>
    
    <div class="banner">
   		<ul>
            <li>
            	<div class="banner-ul1">
                	<a class="banner-div1" href="#photo1">
            			<img src="image/img11.jpg">
            		</a>
                
                	<div class="banner-font">
                        Hipster&nbsp;&nbsp;&nbsp;Fashion
                        <br>
                        Haircut
            		</div>
                	
                
                </div>
            	
            	
            </li>
            
            
            <li>
            	<div class="banner-ul2">
                	<a class="banner-div1" href="#photo2">
            			<img src="image/img10.jpg">
            		</a>
                
                	<div class="banner-font">
                        Hipster&nbsp;&nbsp;&nbsp;Fashion
                        <br>
                        Haircut
                        <br>
                        I love you as fate
            		</div>
                
                </div>
            </li>
            
            
            <li>
            	<div class="banner-ul3">
                	<a class="banner-div1" href="#photo3">
            			<img src="image/img1.jpg">
            		</a>
                
                	<div class="banner-font">
                        Hipster&nbsp;&nbsp;&nbsp;Fashion
                        <br>
                        Haircut
            		</div>
                </div>
            </li>
            
            
            <li>
            	<div class="banner-ul4">
                	<a class="banner-div1" href="#photo4">
            			<img src="image/img7.jpg">
            		</a>
                
                	<div class="banner-font">
                        Hipster&nbsp;&nbsp;&nbsp;Fashion
                        <br>
                        Haircut
            		</div>
                </div>
            </li>
            
            
            <li>
            	<div class="banner-ul5">
                	<a class="banner-div1" href="#photo5">
            			  <img src="image/img6.jpg">
            		  </a>
                
                	<div class="banner-font">
                        Hipster&nbsp;&nbsp;&nbsp;Fashion
                        <br>
                        Haircut
                        <br>
                        BanQing
                        <br>
                        ShaBi
            		  </div>
                
                </div>
            </li>
       </ul>
    </div>  
</body>
</html>
<style>
    body{margin:0;padding:0; font-size:12px; font-family:"SourceHanSansSC-Light","Microsoft Yahei",微软雅黑,"Helvetica Neue",Arial,sans-
    serif; width:100%; color:#757575;}
    html,dl,dt,dd,ul,ol,li,h1,h2,h4,h5,h6,pre,form,fieldset,input,textarea,blockquote,p,img{padding:0; margin:0;}
    img{vertical-align:top; border:none;}
    button,select,textarea{outline:none}
    figure,form,fieldset{border:0;margin:0;padding:0}
    textarea{resize:none}
    ul,li{list-style-type:none;}
    textarea:focus,input:focus{outline:none;}
    table{border-collapse:collapse; border-spacing:0; empty-cells:show; }
    a{color:#232323;text-decoration:none;}
    a:hover{color:#000;text-decoration:none;}

    b,strong{font-weight:normal;}
    cite,em,i{font-style:normal;}
    .fl {float:left;}
    .fr {float:right;}

    .c:after {content:""; display:block; height:0; clear:both;}
    .c{*zoom:1;}







    .head img{position:absolute; top:0px; left:0px; width:1920px; height:974px;}
    .banner{ z-index:9999; position:fixed; bottom:100px;}
    .banner ul li{width:200px; height:170px; position:relative; left:420px; float:left; margin-right:20px;}

    .banner-ul1{width:200px; height:170px; background:#F6F4CD;border-radius:5px; border:1px solid #FFF;text-align:center;}
    .banner-div1{width:100px; height:100px; margin:auto; margin-top:-60px; border:3px solid #FFF; border-radius:50%; display:block;}
    .banner-div1 img{width:100px; height:100px; border-radius:50%; cursor:pointer; animation:img;}
    .banner-font{margin-top:10px; font-size:16px; color:#FFF;text-shadow:1px 1px 1px #000;}



    .banner-ul2{width:200px; height:196px; background:#D5EBE8;border-radius:5px; border:1px solid #FFF;text-align:center;}
    .banner-ul3{width:200px; height:170px; background:#0166FF;border-radius:5px; border:1px solid #FFF;text-align:center;}
    .banner-ul4{width:200px; height:170px; background:#C990B2;border-radius:5px; border:1px solid #FFF;text-align:center;}
    .banner-ul5{width:200px; height:196px; background:#666666;border-radius:5px; border:1px solid #FFF;text-align:center;}


    #photo1:target { z-index:999; animation:img 1s;}
    #photo2:target { z-index:999; animation:img2 2s;}
    #photo3:target { z-index:999; animation:img3 3s;}
    #photo4:target { z-index:999; animation:img4 5s;}
    #photo5:target { z-index:999; animation:img5 3s;}


    @keyframes img{
      0%{
        -webkit-transform:rotateY(360deg) scale(0); 

        transform-origin:top left; 

      }

      100%{
        -webkit-transform:rotateY(0) scale(1); 

      }
    }

    @keyframes img2{
      0%{
        -webkit-transform:rotateY(360deg) scale(0); 

        transform-origin:100 0; 

      }

      100%{
        -webkit-transform:rotateY(0) scale(1); 

      }
    }


    @keyframes img3{
      0%{ 
        -webkit-transform:rotateY(760deg) scale(0); 

        transform-origin:left bottom; 

      }

      100%{
        -webkit-transform:rotateY(0) scale(1); 

      }
    }

    @keyframes img4{
      0%{
        -webkit-transform:rotateY(560deg) scale(0); 

        transform-origin:top right; 

      }

      100%{
        -webkit-transform:rotateY(0) scale(1); 

      }
    }


    @keyframes img5{
      0%{
        -webkit-transform:rotateY(260deg) scale(0); 

        transform-origin:0 100; 

      }

      100%{
        -webkit-transform:rotateY(0) scale(1); 

      }
    }

</style>
