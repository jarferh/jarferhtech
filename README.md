# jarferhtech
my website
<!DOCTYPE html>
<html>
   <head>
      <meta charset="utf-f">
      <meta http-equiv="x-ua-compatible" content="ie=edge">
      <title>Jarferh Tech</title>
      <meta name="description" content="">
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <link rel="stylesheet" href="main.css">
    </head>
 <body>
   <div class="headersection templete clear">
      <div class="logo">
         <img src="designs/logo4.png">
         <h2>JARFERH TECH</h2>
         <p>the ultimate experience</p>
      </div>
      <div class="social">
         

      </div>
   </div>
   <div class="navsection templete clear">
      <ul>
         <li><a href="index.html">Home</a></li>
         <li><a href="about.html">About</a></li>
         <li><a href="contact.html">Contact</a></li>
         <li><a id="active" href="privacy.html">Privacy</a></li>
      <div class="form clear">
         <ul style="float: right;">
            <li><a href="joinus.html">Join us</a></li>
          </ul>
      </div>
      </ul>
   </div>
   <div class="contentsection templete clear">
      <div class="maincontent clear" style="height: 500px;">
        <div class="privacy">
            <h2>Privacy Policy</h2>
            <hr>
        </div>
      </div>
   </div>
   <div class="space templete"></div>
   <div  class="footersection templete clear">
      <div class="footermenu clear">
         <ul id="sitemap">
            <h2>Site map</h2>
            <li><a id="inuse" href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="privacy.html">Privacy</a></li>
         </ul>
         <ul id="jar">
            <h2>Category</h2>
            <li><a href="index.html">how to</a></li>
            <li><a href="about.html">money making</a></li>
            <li><a href="contact.html">android tricks</a></li>
            <li><a href="privacy.html">graphic design</a></li>
         </ul>
         <ul id="social">
            <h2>Social</h2>
            <li><a href="index.html">facebook</a></li>
            <li><a href="about.html">instagram</a></li>
            <li><a href="contact.html">whatsapp</a></li>
            <li><a href="privacy.html">telegram</a></li>
            <li><a href="privacy.html">youtube</a></li>
         </ul>
         <ul class="socialimg">
            <h2 id="follow">Follow us</h2>
            <br>
            <a href=""><li><img src="img/facebook.png"></li></a>
            <a href=""><li><img src="img/instagram.png"></li></a>
            <a href=""><li><img src="img/whatsapp.png"></li></a>
            <a href=""><li><img src="img/telegram.png"></li></a>
            <a href=""><li><img src="img/youtube.png"></li></a>
         </ul>
      </div>
      <p>&copy;COPYRIGHT Jarferh</p>
   </div>
 </body>
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script type="text/javascript" >var scrolltotop={setting:{startline:100,scrollto:0,scrollduration:1e3,fadeduration:[500,100]},controlHTML:'<img src="https://lh3.googleusercontent.com/pw/AM-JKLWi05EDA1z4nVnk_t_9TUa6vC8a8F6TxPnarMGEFNS4hp4Ci-X5UcNjOrD-IKn4UOvtwWINIuo01C6azvNEQ4URQOkSzieCG8y9OFZHLhRRpAgp7BFckIr6CMxmq1OKi9yWWmqz-RgdY8yv6dGdKRqk=s51-no" />',controlattrs:{offsetx:5,offsety:5},anchorkeyword:"#top",state:{isvisible:!1,shouldvisible:!1},scrollup:function(){this.cssfixedsupport||this.$control.css({opacity:0});var t=isNaN(this.setting.scrollto)?this.setting.scrollto:parseInt(this.setting.scrollto);t="string"==typeof t&&1==jQuery("#"+t).length?jQuery("#"+t).offset().top:0,this.$body.animate({scrollTop:t},this.setting.scrollduration)},keepfixed:function(){var t=jQuery(window),o=t.scrollLeft()+t.width()-this.$control.width()-this.controlattrs.offsetx,s=t.scrollTop()+t.height()-this.$control.height()-this.controlattrs.offsety;this.$control.css({left:o+"px",top:s+"px"})},togglecontrol:function(){var t=jQuery(window).scrollTop();this.cssfixedsupport||this.keepfixed(),this.state.shouldvisible=t>=this.setting.startline?!0:!1,this.state.shouldvisible&&!this.state.isvisible?(this.$control.stop().animate({opacity:1},this.setting.fadeduration[0]),this.state.isvisible=!0):0==this.state.shouldvisible&&this.state.isvisible&&(this.$control.stop().animate({opacity:0},this.setting.fadeduration[1]),this.state.isvisible=!1)},init:function(){jQuery(document).ready(function(t){var o=scrolltotop,s=document.all;o.cssfixedsupport=!s||s&&"CSS1Compat"==document.compatMode&&window.XMLHttpRequest,o.$body=t(window.opera?"CSS1Compat"==document.compatMode?"html":"body":"html,body"),o.$control=t('<div id="topcontrol">'+o.controlHTML+"</div>").css({position:o.cssfixedsupport?"fixed":"absolute",bottom:o.controlattrs.offsety,right:o.controlattrs.offsetx,opacity:0,cursor:"pointer"}).attr({title:"Scroll to Top"}).click(function(){return o.scrollup(),!1}).appendTo("body"),document.all&&!window.XMLHttpRequest&&""!=o.$control.text()&&o.$control.css({width:o.$control.width()}),o.togglecontrol(),t('a[href="'+o.anchorkeyword+'"]').click(function(){return o.scrollup(),!1}),t(window).bind("scroll resize",function(t){o.togglecontrol()})})}};scrolltotop.init();</script>

</html>
