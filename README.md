<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
<meta content='width=device-width, initial-scale=1.0' name='viewport'/>
<script type='text/javascript'>//<![CDATA[
var curl = window.location.href;if (curl.indexOf('m=1') != -1) {curl = curl.replace('m=1', 'm=0');window.location.href = curl;}
//]]></script>
<link href='http://fonts.googleapis.com/css?family=Open+Sans:300,400,700' rel='stylesheet' type='text/css'/>
  <link href='http://fonts.googleapis.com/css?family=Roboto+Slab' rel='stylesheet' type='text/css'/>
<link href='//netdna.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.css' rel='stylesheet'/>
<b:include data='blog' name='all-head-content'/>
<b:if cond='data:blog.url == data:blog.homepageUrl'>
</b:if>
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<title><data:blog.pageTitle/></title> 
<b:else/>
<title><data:blog.pageName/> ~ <data:blog.title/></title>
</b:if>
<b:if cond='data:blog.url == data:blog.homepageUrl'>
<meta content='Description-here' name='description'/>
<meta content='Keywords-here' name='keywords'/>
</b:if>

<b:skin><![CDATA[

/*
/********************************
/////////////////////////////////////////////////////////
//                                                     //
//  Template Version: 2.0 //
// 	Template Name: Social Mag
//  Designer: Syed Faizan Ali //
//  Company:Templateism
//  All rights are Strictly Reserved  //
//                                                     //
/////////////////////////////////////////////////////////
********************************/


/*=====================================
= Admin CSS
=====================================*/
body#layout ul{list-style-type:none;list-style:none}
body#layout ul li{list-style-type:none;list-style:none}
body#layout #rsidebar-wrapper{display:block;margin:0px;}
body#layout #social-menu { display: none; }
body#layout #main-wrapper { width: 824px; float: left; }
body#layout .sidebar .widget-content { width: auto; } 
body#layout #email-subscribe{height:auto;width: 338px;}
body#layout .featured {width: 821px;}
body#layout #copyrights .right { width: 100%; }

/*=====================================
= CSS Reset
=====================================*/
.clearfix:after{content:"\0020";display:block;height:0;clear:both;visibility:hidden;overflow:hidden}
#container,#header,#main,#main-fullwidth,#footer,.clearfix{display:block}
#main{margin:0px;}
.clear{clear:both}
h1,h2,h3,h4,h5,h6{margin-bottom:16px;font-weight:normal;line-height:1}
h1{font-size:40px}
h2{font-size:30px}
h3{font-size:20px}
h4{font-size:16px}
h5{font-size:14px}
h6{font-size:12px}
h1 img,h2 img,h3 img,h4 img,h5 img,h6 img{margin:0}
table{margin-bottom:20px;width:100%}
th{font-weight:bold}
thead th{background:#c3d9ff}
th,td,caption{padding:4px 10px 4px 5px}
tr.even td{background:#e5ecf9}
tfoot{font-style:italic}
caption{background:#eee}
li ul,li ol{margin:0}
ul,ol{margin:0 20px 20px 0;padding-left:40px}
ul{list-style-type:disc}
ol{list-style-type:decimal}
dl{margin:0 0 20px 0}
dl dt{font-weight:bold}
dd{margin-left:20px}
pre{margin:20px 0;white-space:pre}
pre,code,tt{font:14px 'andale mono','lucida console',monospace;line-height:18px}

/*=====================================
= Global CSS
=====================================*/
body{color: #555;background-color: #D2F5EA;font-family: open sans, Helvetica, Sans-serif;font-size: 14px;margin:0px;padding:0px;}
a:link,a:visited{-moz-transition: all .7s ease-in-out; -webkit-transition: all .7s ease-in-out; transition: all .7s ease-in-out;color:#33bcf2;text-decoration:none;outline:none;}
a:hover{-moz-transition: all .7s ease-in-out; -webkit-transition: all .7s ease-in-out; transition: all .7s ease-in-out;color:#00ACF0;text-decoration:none;outline:none;}


/*=====================================
= Header
=====================================*/
.margin-1200{width:1176px;margin:0px auto 0px;overflow:hidden;}
#header-wrapper{float:left;width:100%;background: #fff;padding-bottom:20px;}
#header-inner{background-position:center;margin-left:auto;margin-right:auto}
#header { float: left; margin: 40px 20px 0px 30px; }
#header h1{color:#F55630;margin:0;padding:0;font-weight:bold;font-size:32px;line-height:32px;font-family: 'Roboto Slab', serif;}
#header .description{padding-left:7px;color:#374142;line-height:14px;font-size:14px;padding-top:0px;margin-top:10px;}
#header h1 a,#header h1 a:visited{color:#F55630;text-decoration:none}
#header h2{padding-left:5px;color:#374142;font:14px Arial,Helvetica,Sans-serif}
/*span.secondbc { color: hsla(31, 92%, 48%, 0.98); }*/
/*h1.title:before { content: " "; font-family: none; color: #F55630; }*/

/*=====================================
= Outer Wrapper
=====================================*/
#outer-wrapper{width:100%;}r
#main-wrapper{width:615px;float:left;margin:0px;padding:0px 0px 0px 0px;word-wrap:break-word;overflow:hidden;}
#rsidebar-wrapper{width:340px;float:right;margin: 30px 0px 0px 0px;}

/*=====================================
= Posts
=====================================*/
h2.date-header{margin:1.5em 0 .5em;display:none;}
.post{margin-bottom:15px;}
.post-title{margin:0px;}
.post-title a,.post-title a:visited,.post-title strong{display:block;text-decoration:none;color:#333333;text-decoration:none;}
.post-title strong,.post-title a:hover,.featured .label_title:hover{color:#33bcf2;text-decoration:none;}
.post-footer{margin:5px 0;}
.postmeta .fa { margin-right: 5px; } 
.publ,.pubb,.publab { border-right: 1px solid #d2d2d2; padding-right: 10px; margin-right: 10px; }
.post-body h2 { font-family: 'Roboto Slab'; font-size: 35px; line-height: 40px; margin: 25px 0px 10px 0px; } 
.post-body h3 { font-family: 'Roboto Slab'; font-size: 30px; line-height: 35px; margin: 25px 0px 10px 0px; } 
.post-body h4 { font-family: 'Roboto Slab'; font-size: 25px; line-height: 30px; margin: 25px 0px 10px 0px; }
blockquote { font-family: 'Roboto Slab', serif; font-size: 20px; overflow: hidden; margin: 20px 0px 20px 0px; padding: 20px; background: #F8F8F8; }
#related-posts { border: 1px solid #ccc; float: left; width: 97%; border-top: 1px solid #ccc; margin: 20px 0px; background: #F4F4F4; padding: 10px; }
#related-posts h2 { background: #33bcf2; color: #fff; text-transform: uppercase; float: left; padding: 10px; font-size: 18px; margin-left: 8px; }
#related-posts h2:before { content: ""; font-family: fontawesome; margin-right: 10px; }

/*=====================================
= Search
=====================================*/
#search #buttonsinput { height: 42px; background: #00bf8f; border: 0px; font-family: open sans; color: #fff; font-size: 15px; padding: 0 23px }
#search #s { height: 22px; width: 300px; border: transparent; padding: 10px; font-family: open sans; background: #f0ede9; color: #8B8B8B; font-size: 15px; }
#search:before { content: "\f002"; font-family: FontAwesome; color: #8B8B8B; }
#search { float: right; background: #f0ede9; padding-left: 20px; font-size: 15px; margin-top: 37px;}
.feed-links{display:none;}

/*=====================================
= Social
=====================================*/
#social-menu li a { padding: 9px 17px; float: left; margin-right: 5px; font-size: 18px; color: #fff; }
#social-menu { float: right;margin-top:37px;margin-right: 15px;} 
#social-menu li { display: block; float: left;}
#social-menu ul { margin: 0px; }

/*=====================================
= Email Subscribe
=====================================*/
#email-subscribe { margin:0px;background: #71DAC0; padding: 20px; color: #fff; font-size: 14px; border: 2px solid #2DA5E8; width: 350px; float:right; margin-bottom:20px; height: 350px; } #email-subscribe h2 { color: #fff; font-weight: 400; font-family: open sans; text-align: center; text-transform: uppercase; font-size: 27px; line-height: 30px; } 
#email-subscribe h2 span { text-transform: uppercase; font-weight: bold; font-size: 49px; letter-spacing: -3px; line-height: 55px; } 
.FollowByEmail .follow-by-email-inner .follow-by-email-address { padding: 15px 10px; background: #08D19E; border: 0px!important; color: #fffimportant; font-family:open sans; font-size:14px }
 #email-subscribe .FollowByEmail .follow-by-email-inner .follow-by-email-submit { background: #2d3e50; padding: 14px 30px 14px 30px; float: left; width: auto!important; height: auto!important; margin: 0px; font-family: open sans; font-size: 18px; font-weight: 700; border-top-left-radius: 0px; border-bottom-left-radius: 0px; }
#email-subscribe ::-webkit-input-placeholder {color: #fff}
#email-subscribe th, td, caption { padding-left: 0px; }
#email-subscribe p { font-size: 16px; text-align: center; color: #00F9BC; }

/*=====================================
= Index Setting
=====================================*/
.cover { direction: ltr; margin: 25px 0; background-color: #fff; max-height: 292px; } 
#coverflow .next { margin-top: 110px;top:0;right: 0; } #coverflow .prev {  margin-top: 110px;top:0;left: 0; } 
#coverflow button { top: 300px; position: absolute; z-index: 55; border: 0; padding: 15px; background-color: rgba(0, 0, 0, 0.66); color: #fff; cursor: pointer; opacity: 0; } #coverflow:hover button { opacity: 1; } 
#coverflow { margin: 0px; }
#coverflow .recent-box { padding:0px;display:block;width: 395px; height: 292px; position: relative; } 
#coverflow .recent-box .imageContainer { width: 395px; height: 292px; } 
#coverflow .recent-box .imageContainer img { width: 100%; height: 100%; }
#coverflow .recent-box .label_title { position: absolute; z-index: 5; color: #fff; width: auto; padding: 0 50px; text-align: center; left: 0; right: 0; bottom: 15px; margin: 0; font-weight: bold; font-size: 14px; line-height: 2em; text-transform: uppercase; text-decoration: none; overflow: hidden; height: 25px; } 
#coverflow .recent-box .label_title:before { content: ""; } 
#coverflow .recent-box:after { content: no-close-quote; position: absolute; bottom: 0; left: 0; width: 100%; height: 56px; background: rgba(0, 0, 0, 0.72);} 
#coverflow .recent-box .toe { position: absolute; top: 0px; } 
#coverflow .recent-box .toe a { padding: 10px 20px; float: left; background: #00bf8f; text-decoration: none; color:#fff; } #coverflow .recent-box .toe .recent-com { background: #000!important; opacity: 0.8; }

/*=====================================
= Sidebar
=====================================*/
.sidebar{margin:0 0 10px 0;font-size:13px;color:#374142;}
.sidebar a{text-decoration:none;color: #33bcf2; font-size: 14px;}
.sidebar a:hover{text-decoration:underline;color: #33bcf2;}
.sidebar h2 { margin: 0 0 10px 0; color: #555; font-size: 18px; line-height: 16px; text-transform: capitalize; background: #F4F4F4; border-bottom: 1px solid #d2d2d2; padding: 15px 10px; text-align: center; }
.sidebar ul{list-style-type:none;list-style:none;margin:0px;padding:0px;}
.sidebar ul li{padding:0 0 9px 0;margin:0 0 8px 0;}
.sidebar .widget { margin: 30px 0px; padding: 0; color: #374142; font-size: 13px; background: #fff; border: 1px solid #d2d2d2; }
.sidebar .widget-content { padding: 20px; width: 300px; }
.main .widget{margin:0 0 5px;padding:0 0 2px}
.main .Blog{border-bottom-width:0}

/*=====================================
= Footer
=====================================*/
#copyrights{color:#374142;background:#fff;text-align:center;padding:30px 0;border-top: 1px solid #ccc;}
#copyrights a{color:#374142}
#copyrights a:hover{color:#374142;text-decoration:none}
#copyrights .left { float: left; }
#copyrights .right { float: right; } 
#copyrights .right li { display: block; float: left; margin-left: 10px; } 
#copyrights .right ul { margin: 0px; padding: 0px; } 
#copyrights .right ul li a { text-decoration:none;}

/*=====================================
= Comments
=====================================*/
#comments { float: left; width: 100%; }
#comments-block3 { padding: 0; margin: 0; float: left; overflow: hidden; position: relative; }
#comment-name-url { width: 465px; float: left; } #comment-date { width: 465px; float: left; margin-top: 5px; font-size: 10px; }
.avatar-image-container { background: none!important; border: none!important; ; }
.datetime.secondary-text { float: right; }
.comments .comments-content .comment-content { line-height: 20px; font-size: 14px; }
.comments .comment .comment-actions a { padding-right: 5px; padding-top: 5px; text-decoration: none; }
.comments .comments-content .comment { margin-bottom: 40px; padding-bottom: 8px; }
.user.blog-author a { font-size: 20px; text-decoration: none; }
.comment-actions a { color: #fff; }
.comment-actions { padding: 10px; margin-top: 20px; float: right; background: #00bf8f; margin-bottom: 10px; }
.comment-block { border: 1px solid #ddd; padding: 20px; }
.comment-header { border-bottom: 1px solid #ddd; padding-bottom: 20px; }
#comments h4:before { content: "\f0e6"; font-family: fontawesome; margin-right: 10px; } 
#comments h4 { background: #33bcf2; color: #fff; text-transform: uppercase; padding: 10px; font-size: 18px; margin: 5px 0px; }
#navbar-iframe{height:0;visibility:hidden;display:none;}

/*=====================================
= Responsive Menu
=====================================*/
nav#nav-mobile { position: relatitve; display: none; }
#nav-trigger { margin-left: 20px; float: right; display: none; text-align: center; }
#nav-trigger { background: #33bcf2; float: right; width: 100%; }
#nav-trigger span { color: #EEE; line-height: 57px; } nav#nav-mobile { margin: 0px; } 
nav#nav-mobile { display: none; } .children.expanded a { color: #fff!important; } 
#nav-trigger span .fa { font-size: 18px; } 
nav#nav-mobile { float: left; width: 100%; background: #33bcf2; margin-top: -10px; }

/*=====================================
= Menu
=====================================*/
.menus,.menus *{margin:0;padding:0;list-style:none;list-style-type:none;line-height:1.0}
.menus ul{position:absolute;top:-999em;width:100%}
.menus ul li{width:100%}
.menus li:hover{visibility:inherit}
.menus li{float:left;position:relative}
.menus a{display:block;position:relative}
.menus li:hover ul,.menus li.sfHover ul{left:0;top:100%;z-index:99}
.menus li:hover li ul,.menus li.sfHover li ul{top:-999em}
.menus li li:hover ul,.menus li li.sfHover ul{left:100%;top:0}
.menus li li:hover li ul,.menus li li.sfHover li ul{top:-999em}
.menus li li li:hover ul,.menus li li li.sfHover ul{left:100%;top:0}
.sf-shadow ul{padding:0 8px 9px 0;-moz-border-radius-bottomleft:17px;-moz-border-radius-topright:17px;-webkit-border-top-right-radius:17px;-webkit-border-bottom-left-radius:17px}
.menus .sf-shadow ul.sf-shadow-off{background:transparent}
.menu-primary-container{float:left;padding:0 10px;position:relative;height:36px;background:url(http://3.bp.blogspot.com/-MYS4dWVzP7E/UC7eq8_isMI/AAAAAAAAAw4/1EgVe7LFnos/s000/menu-primary-bg.png) left top repeat-x;z-index:400;-moz-border-radius:10px;-khtml-border-radius:10px;-webkit-border-radius:10px;border-radius:10px}
.menu-primary{}
.menu-primary ul{min-width:160px}
.menu-primary li a{color:#222121;padding:12px 15px;text-decoration:none;text-transform:uppercase;font:normal 11px/11px Arial,Helvetica,Sans-serif}
.menu-primary li a:hover,.menu-primary li a:active,.menu-primary li a:focus,.menu-primary li:hover > a,.menu-primary li.current-cat > a,.menu-primary li.current_page_item > a,.menu-primary li.current-menu-item > a{color:#C72714;outline:0;background:url(http://3.bp.blogspot.com/-MYS4dWVzP7E/UC7eq8_isMI/AAAAAAAAAw4/1EgVe7LFnos/s000/menu-primary-bg.png) left -136px repeat-x}
.menu-primary li li a{color:#fff;text-transform:none;background:#E64633;padding:10px 15px;margin:0;border:0;font-weight:normal}
.menu-primary li li a:hover,.menu-primary li li a:active,.menu-primary li li a:focus,.menu-primary li li:hover > a,.menu-primary li li.current-cat > a,.menu-primary li li.current_page_item > a,.menu-primary li li.current-menu-item > a{color:#fff;background:#F85B49;outline:0;border-bottom:0;text-decoration:none}
.menu-primary a.sf-with-ul{padding-right:20px;min-width:1px}
.menu-primary .sf-sub-indicator{position:absolute;display:block;overflow:hidden;right:0;top:0;padding:11px 10px 0 0}
.menu-primary li li .sf-sub-indicator{padding:9px 10px 0 0}
.wrap-menu-primary .sf-shadow ul{background:url('http://4.bp.blogspot.com/-HZR7XIAppvQ/UC7esBSSHsI/AAAAAAAAAxA/tOQJJyB__CI/s000/menu-primary-shadow.png') no-repeat bottom right}
.menu-secondary-container { width: 100%; background: #33bcf2; float: left; }
.menu-secondary{}
.menu-secondary ul{min-width:160px}
.menu-secondary li a {color: #fff; text-transform: uppercase; font-size: 18px; text-decoration: none; padding: 19px 18px 18px 18px; border-right: 1px solid rgba(255, 255, 255, 0.21); }
.menu-secondary li a:hover,.menu-secondary li a:active,.menu-secondary li a:focus,.menu-secondary li:hover > a,.menu-secondary li.current-cat > a,.menu-secondary li.current_page_item > a,.menu-secondary li.current-menu-item > a{color:#fff;background:rgba(0, 0, 0, 0.08);outline:0}
.menu-secondary li li a{color: #fff; background: #33bcf2; padding: 10px 15px; text-transform: none; margin: 0; font-weight: normal;}
.menu-secondary li li a:hover,.menu-secondary li li a:active,.menu-secondary li li a:focus,.menu-secondary li li:hover > a,.menu-secondary li li.current-cat > a,.menu-secondary li li.current_page_item > a,.menu-secondary li li.current-menu-item > a{color:#fff;background:#2eacde;outline:0}
.menu-secondary a.sf-with-ul{padding-right:26px;min-width:1px}
.menu-secondary .sf-sub-indicator{position:absolute;display:block;overflow:hidden;right:0;top:0;padding:12px 13px 0 0}
.menu-secondary li li .sf-sub-indicator{padding:9px 13px 0 0}
.wrap-menu-secondary .sf-shadow ul{background:url('http://2.bp.blogspot.com/-ErWByFPNils/UC7etR9NBcI/AAAAAAAAAxQ/nHaZ5IKMRjM/s000/menu-secondary-shadow.png') no-repeat bottom right}

}
/*=====================================
= Index Setting
=====================================*/
.index #rsidebar-wrapper { display: none; } 
.index #main-wrapper { width: 100%; }
.index .post-summary { height: 240px; overflow: hidden; border-top-left-radius: 2px; -webkit-border-top-left-radius: 2px; border-top-right-radius: 2px; -webkit-border-top-right-radius: 2px; }
.index .post-outer { height: 379px;width: 31.5%; float: left; background: #fff; margin: 10px; -webkit-box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05); box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05); }
.index .post-body{padding:0px;}
.index .crop img { width: 100%; min-height: 240px; }
.index .post h2 a { font-family: 'Roboto Slab', serif; font-weight: 400; line-height: 34px; margin: 20px 20px 10px 20px; font-size: 25px; }
.index .post-details { float: left; padding: 0 20px; color: #A4A4A4; } 
.index .post-details a { color: #A4A4A4; text-decoration: none; } 
.index .post-details span { float: left; overflow: hidden; margin-right: 20px;}
.index .post-summary iframe { width: 100%; height: 243px; }
.index blockquote { font-family: 'Roboto Slab', serif; font-size: 20px; height: 201px; overflow: hidden; margin: 0px; padding: 20px; background: #F8F8F8; } 
blockquote:before { content: "\f10d"; font-family: fontawesome; color: #00bf8f; } 
blockquote:after { content: "\f10e"; font-family: fontawesome; margin-left: 5px; color: #00bf8f; } 


/*=====================================
= Featured
=====================================*/
.featured { width: 746px; float: left; background: #fff; -webkit-box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05); box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05);margin: 0px 0px 20px 0px; } 
.featured img { width: 100%; } .featured ul { padding: 0px; margin: 0px; }
.featured li{display:block;padding:0px;} 
.featured .widget{margin:0px;}
.featured .label_title {padding: 20px 20px 10px 20px;font-family: 'Roboto Slab', serif; font-weight: 400; line-height: 34px; font-size: 25px;color:#555;text-decoration:none;float:left;margin: 0px;} 
.featured .toe a { padding: 0px 10px 20px 20px; float: left; color: #A4A4A4; text-decoration: none; } 
.featured .toe { float: left; width: 100%; } 
.featured .imageContainer { height: 294px; overflow: hidden; }


/*=====================================
= Status Msg
=====================================*/
.status-msg-body { background: #fff; float: left; text-align: center; }
.status-msg-wrap { background: #fff; width: 100%; text-align: center; margin-bottom: 20px; float: left; border-bottom: 1px solid #d2d2d2; margin-top: 31px; padding: 10px 0px; } .status-msg-border { border: none; }
.status-msg-body a { display: none; }
.status-msg-body { background: #fff; float: left; text-align:center; }
.status-msg-body:before { content: "\f0eb"; font-family: fontawesome; font-size: 20px; }


/*=====================================
= Load More Post Trigger
=====================================*/
.ias_trigger a:before { content: "\f021"; font-family: fontawesome; margin-right: 10px; } 
.ias_trigger a { font-size: 16px; color: #555; text-decoration: none; font-weight: bold; text-transform: capitalize; } 
.ias_trigger { float: left; width: 100%; text-align: center; background: #fff; padding: 10px 0px; margin-top: 20px; }
.ias_trigger:hover a { color: #fff; } .ias_trigger:hover { background: #00bf8f; color: #fff; }

/*=====================================
= Page CSS
=====================================*/
.static_page #main-wrapper { width: 777px; background: #fff; padding: 20px; margin-top: 30px; float: left; -webkit-box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05); box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05); border: 1px solid #d2d2d2}
.static_page img { max-width: 100%; height: auto; }
.static_page .post-body h2 { margin: 10px 0px 25px 0px; }

/*=====================================
= Item CSS
=====================================*/
.item #main-wrapper { width: 777px; background: #fff; padding: 20px; margin-top: 30px; float: left; -webkit-box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05); box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05); border: 1px solid #d2d2d2}
.post-body img { max-width: 100%; height: auto; }
.post h1 { font-family: 'Roboto Slab', serif; font-size: 40px; line-height: 45px; width: 100%; float: left; }
.postmeta { float: left; border-bottom: 1px solid #ccc; width: 100%; margin: 20px 0px; border-top: 1px solid #ccc; padding: 10px 0px; }
.item .blog-pager-newer-link { margin-right: 10px; }
.item #blog-pager { float: right; margin: 0px; line-height: 40px; } 
.item #blog-pager a { background: #00bf8f; padding: 8px 15px; color: #fff; font-size: 18px; } 
.item #blog-pager a:hover { background: #00A97F; }


/*=====================================
= Share Buttons
=====================================*/
.share-button-link-text { display: block; text-indent: 0; } 
.post-share-buttons { display: block; width: 100%; float: left; margin-bottom: 30px; border-bottom: 1px solid #ccc; padding-bottom: 20px; } 
.post-share-buttons .fb { background: #375593; color: #fff; font-size: 18px; padding: 8px 15px; text-decoration:none; } 
.post-share-buttons .fb a { color:#fff; text-decoration:none; } 
.post-share-buttons .tw { background: #0eb6f6; color: #fff; padding: 8px 15px; font-size: 18px; } 
.post-share-buttons .pin { background: #cb2027; padding: 8px 15px; color: #fff; font-size: 18px; } 
.post-share-buttons .gp { background: #dd4b39; padding: 8px 15px; color: #fff; font-size: 18px; }


/*=====================================
= About Author
=====================================*/
.aboutauthor { float: left; width: 100%;margin-top:30px; }
.aboutauthor img { width: 111px; height: auto; float: left; margin-right: 20px; }
.authorname { font-family: 'Roboto Slab'; font-size: 23px; margin: 5px 0px!important; }
.aboutauthor p { margin: 0px; } 
.aboutauthor h3 { background: #00bf8f; color: #fff; text-transform: uppercase; padding: 10px; font-size: 18px; } 
.authorrank { text-transform: uppercase; margin: 0px 0px 10px 0px!important; }


/*=====================================
= Pagination
=====================================*/
.index .blog-pager { width: 100%; float: left; }
.showpageOf { display: none; } .showpagePoint { background: #000000; padding: 5px; padding: 10px 12px 9px 12px; font-weight: bold; color: #fff; } 
.showpageNum a { background: #00bf8f; padding: 5px; padding: 10px 12px 9px 12px; color: #000; font-weight: bold; } 
.showpageArea a { text-decoration: none; } .showpageArea a:hover { transition: all 0.3s ease-out; background: #000000; } 
.showpage a { background: #00bf8f; padding: 5px; padding: 10px 12px 9px 12px; color: #000; font-weight: bold; } 
span.showpage a { margin-left: 10px; margin-right: 10px; } 
.showpageArea { float: left; } 
.showpagePoint { margin-right: 5px; } 
.showpageNum a { margin-right: 5px; } 
.showpageArea a { font-family: open sans; font-weight: 400; text-shadow: none; } 
.showpageArea { font-family: open sans; font-weight: 400; text-shadow: none; } 
.feed-links { display: none; } 
.showpageArea a { float: left; font-size: 15px; color: #fff!important; padding-left: 15px; padding-right: 15px; } 
.showpagePoint { float: left; font-size: 15px; padding-left: 15px; padding-right: 15px; }

/*=====================================
= Responsive CSS
=====================================*/
@-moz-document url-prefix() {
@media screen and (max-width: 1110px) {
#search #s { width: 615px!important; } 
}

@media screen and (max-width: 810px) {
#search #s { width: 135px!important; } 
}
}

@media screen and (max-width: 1110px) {
nav#nav-mobile ul{display:none;}
nav#nav-mobile,#nav-trigger {display: block!important;}
.menu-secondary-container {display: none!important;}
.menus li {width: 100%;text-align:center;}
.margin-1200 {max-width: 800px;}
#search { margin-right: 10px; width: 760px; margin-left: 10px; } 
#search #s { width: 620px; } 
#email-subscribe { width: 754px; }
.featured { width: 100%; }
.index .post-outer { width: 47.5%;}
.item #main-wrapper,
.static_page #main-wrapper { width: 94.5%; }
#rsidebar-wrapper { width: 100%; }
.sidebar .widget-content { width: 759px; }
#related-posts a { width: 164px!important; }
#related-posts img { width: 165px!important; height: 115px!important; }


}

@media screen and (max-width: 810px) {
nav#nav-mobile,#nav-trigger {display: block!important;}
.menu-secondary-container {display: none!important;}
.menus li {width: 100%;}
.margin-1200 {max-width: 320px;}
#header { float: left; margin: 10px 20px 0px 20px; text-align: center; }
#social-menu { width: 295px; margin: auto; }
#search #s { width: 141px; }
#search { width: 281px;margin-top: 12px;}
#main-wrapper { width: 87%; }
.item #main-wrapper,
.static_page #main-wrapper { width: 86.5%; }
.publ, .pubb, .publab { width: 100%!important; float: left; border: 0px; text-align: center; }
.item #blog-pager { margin-top: 10px; width: 100%; }
#related-posts { width: 93%;}
#related-posts a { width: 97%!important; height: auto!important; } 
#related-posts img { width: 100%!important; height: auto!important; }
.sidebar .widget-content { width: 100%; padding: 0px; }
.sidebar .widget { background: none; border: 0px; }
 .sidebar h2 { border: 1px solid #ccc; }
#email-subscribe { width: 86%; height: auto!important; margin-right: 0px;}
.featured .imageContainer { height: auto;}
.index .post-outer { width: 94.5%; height: auto;}
#coverflow .recent-box {width: 320px; height: 292px;}
#coverflow .recent-box .imageContainer{width: 320px;}
iframe{width: 100%; height: auto;}
#copyrights .right { float: left; width: 100%; }
#copyrights .right ul li { width: 100%; float: left; margin: 0px; }
}


.quickedit{
display:none;
}.fa-group:before,
.fa-users:before {
  content: "";]]></b:skin>


<b:template-skin>
 <![CDATA[
/*=====================================
= Layout Styles
=====================================*/
body#layout #header-wrapper:before {content: 'Templateism Admin Panel';}
body#layout #rsidebar-wrapper:before {content: 'Sidebar';}
body#layout #main-wrapper:before {  content: 'Post Body';  }
body#layout #coverflow:before {  content: 'Post Slider (Homepage)';  }
body#layout .featured:before {  content: 'Featured Post (Homepage)';  }
body#layout #email-subscribe:before {  content: 'RSS Feed Email';  }
body#layout #copyrights:before {  content: 'Footer Links';  }
body#layout #main-wrapper:before,
body#layout #coverflow:before,
body#layout #copyrights:before,
body#layout #header-wrapper:before,
body#layout #email-subscribe:before,
body#layout .featured:before,
body#layout #rsidebar-wrapper:before { background-color: #00ab6f; color: #fff; padding: 15px 0; display: block; font-size: 23px; text-align: center; margin: 0 4px; margin-bottom: 8px; text-transform: uppercase; font-family: open sans,arial; }
 ]]>
 </b:template-skin>

<script src='//code.jquery.com/jquery-1.10.2.min.js' type='text/javascript'/>

<script type='text/javascript'>
//<![CDATA[
//Related Posts Setting
var defaultnoimage="http://3.bp.blogspot.com/-PpjfsStySz0/UF91FE7rxfI/AAAAAAAACl8/092MmUHSFQ0/s1600/no_image.jpg";
var maxresults=4;
var splittercolor="#fff";
var relatedpoststitle="Sản phẩm cùng danh mục"

//Post Thumbnail Setting
var thumbnail_mode = "no-float";
summary_noimg = 0;
summary_img = 100;
img_thumb_height = "";
img_thumb_width = 400;
//]]>
</script>

<script type='text/javascript'>
//<![CDATA[

var _0x3ccf=["\x51\x20\x32\x62\x28\x59\x2C\x31\x39\x29\x7B\x7A\x28\x59\x2E\x31\x34\x28\x22\x3C\x22\x29\x21\x3D\x2D\x31\x29\x7B\x71\x20\x73\x3D\x59\x2E\x31\x7A\x28\x22\x3C\x22\x29\x3B\x31\x37\x28\x71\x20\x69\x3D\x30\x3B\x69\x3C\x73\x2E\x42\x3B\x69\x2B\x2B\x29\x7B\x7A\x28\x73\x5B\x69\x5D\x2E\x31\x34\x28\x22\x3E\x22\x29\x21\x3D\x2D\x31\x29\x7B\x73\x5B\x69\x5D\x3D\x73\x5B\x69\x5D\x2E\x31\x35\x28\x73\x5B\x69\x5D\x2E\x31\x34\x28\x22\x3E\x22\x29\x2B\x31\x2C\x73\x5B\x69\x5D\x2E\x42\x29\x7D\x7D\x59\x3D\x73\x2E\x33\x74\x28\x22\x22\x29\x7D\x31\x39\x3D\x28\x31\x39\x3C\x59\x2E\x42\x2D\x31\x29\x3F\x31\x39\x3A\x59\x2E\x42\x2D\x32\x3B\x32\x73\x28\x59\x2E\x33\x73\x28\x31\x39\x2D\x31\x29\x21\x3D\x27\x20\x27\x26\x26\x59\x2E\x31\x34\x28\x27\x20\x27\x2C\x31\x39\x29\x21\x3D\x2D\x31\x29\x31\x39\x2B\x2B\x3B\x59\x3D\x59\x2E\x31\x35\x28\x30\x2C\x31\x39\x2D\x31\x29\x3B\x31\x6D\x20\x59\x2B\x27\x27\x7D\x51\x20\x33\x76\x28\x31\x5A\x2C\x31\x6F\x2C\x33\x77\x29\x7B\x71\x20\x47\x3D\x44\x2E\x33\x72\x28\x31\x5A\x29\x3B\x71\x20\x31\x4F\x3D\x22\x22\x3B\x71\x20\x55\x3D\x22\x22\x3B\x71\x20\x31\x58\x3D\x22\x22\x3B\x71\x20\x48\x3D\x47\x2E\x31\x50\x28\x22\x31\x58\x22\x29\x3B\x7A\x28\x48\x2E\x42\x3E\x3D\x31\x29\x7B\x31\x68\x3D\x48\x5B\x30\x5D\x2E\x4A\x3B\x71\x20\x31\x6E\x3D\x22\x22\x3B\x71\x20\x33\x6C\x3D\x22\x22\x3B\x71\x20\x31\x4D\x3D\x2F\x28\x5C\x3F\x76\x3D\x7C\x5C\x2F\x5C\x64\x5C\x2F\x7C\x5C\x2F\x32\x31\x5C\x2F\x29\x28\x5B\x61\x2D\x32\x33\x2D\x32\x32\x2D\x39\x5C\x2D\x5C\x32\x35\x5D\x2B\x29\x2F\x3B\x71\x20\x31\x44\x3D\x2F\x28\x5C\x2F\x32\x31\x5C\x2F\x32\x79\x5C\x2F\x29\x28\x5B\x61\x2D\x32\x33\x2D\x32\x32\x2D\x39\x5C\x2D\x5C\x32\x35\x5D\x2B\x29\x2F\x3B\x7A\x28\x31\x68\x29\x7B\x32\x65\x3D\x31\x68\x2E\x31\x77\x28\x31\x4D\x29\x3B\x32\x38\x3D\x31\x68\x2E\x31\x77\x28\x31\x44\x29\x3B\x7A\x28\x32\x38\x29\x7B\x31\x6E\x3D\x31\x68\x2E\x31\x77\x28\x31\x44\x29\x5B\x32\x5D\x3B\x55\x3D\x27\x31\x38\x3A\x2F\x2F\x31\x51\x2E\x33\x78\x2E\x31\x36\x2F\x31\x53\x2F\x32\x79\x2F\x27\x2B\x31\x6E\x7D\x4B\x20\x7A\x28\x32\x65\x29\x7B\x31\x6E\x3D\x31\x68\x2E\x31\x77\x28\x31\x4D\x29\x5B\x32\x5D\x3B\x55\x3D\x27\x31\x38\x3A\x2F\x2F\x33\x47\x2E\x33\x48\x2E\x31\x36\x2F\x33\x49\x2F\x27\x2B\x31\x6E\x2B\x27\x2F\x33\x4A\x2E\x31\x70\x27\x7D\x7A\x28\x55\x29\x7B\x55\x3D\x55\x7D\x4B\x7B\x71\x20\x48\x3D\x47\x2E\x31\x50\x28\x22\x48\x22\x29\x3B\x7A\x28\x48\x2E\x42\x3E\x3D\x31\x29\x7B\x55\x3D\x48\x5B\x30\x5D\x2E\x4A\x7D\x4B\x7B\x55\x3D\x22\x31\x38\x3A\x2F\x2F\x32\x2E\x31\x42\x2E\x31\x78\x2E\x31\x36\x2F\x2D\x32\x66\x2F\x32\x6B\x2F\x32\x69\x2F\x32\x6E\x2D\x32\x68\x2F\x31\x6C\x2F\x32\x6A\x2E\x31\x52\x22\x7D\x7D\x7D\x7D\x4B\x7B\x71\x20\x48\x3D\x47\x2E\x31\x50\x28\x22\x48\x22\x29\x3B\x7A\x28\x48\x2E\x42\x3E\x3D\x31\x29\x7B\x55\x3D\x48\x5B\x30\x5D\x2E\x4A\x7D\x4B\x7B\x55\x3D\x22\x31\x38\x3A\x2F\x2F\x32\x2E\x31\x42\x2E\x31\x78\x2E\x31\x36\x2F\x2D\x32\x66\x2F\x32\x6B\x2F\x32\x69\x2F\x32\x6E\x2D\x32\x68\x2F\x31\x6C\x2F\x32\x6A\x2E\x31\x52\x22\x7D\x7D\x7A\x28\x55\x29\x7B\x31\x4F\x3D\x27\x3C\x47\x20\x50\x3D\x22\x32\x67\x2D\x33\x46\x22\x3E\x3C\x47\x20\x50\x3D\x22\x32\x67\x22\x3E\x3C\x61\x3E\x3C\x61\x20\x5A\x3D\x22\x27\x2B\x31\x6F\x2B\x27\x22\x3E\x3C\x48\x20\x4A\x3D\x22\x27\x2B\x55\x2B\x27\x22\x20\x22\x27\x2B\x20\x2B\x48\x5B\x30\x5D\x2E\x4A\x2B\x20\x2B\x27\x22\x2F\x3E\x3C\x2F\x61\x3E\x3C\x2F\x47\x3E\x3C\x2F\x47\x3E\x27\x3B\x32\x61\x3D\x33\x45\x7D\x71\x20\x31\x63\x3D\x31\x4F\x2B\x27\x3C\x47\x20\x50\x3D\x22\x31\x63\x2D\x31\x67\x22\x3E\x27\x2B\x32\x62\x28\x47\x2E\x32\x63\x2C\x32\x61\x29\x2B\x27\x20\x2E\x2E\x2E\x27\x2B\x27\x3C\x2F\x47\x3E\x27\x3B\x47\x2E\x32\x63\x3D\x31\x63\x7D\x71\x20\x49\x3D\x31\x62\x20\x31\x61\x28\x29\x3B\x71\x20\x58\x3D\x30\x3B\x71\x20\x56\x3D\x31\x62\x20\x31\x61\x28\x29\x3B\x71\x20\x52\x3D\x31\x62\x20\x31\x61\x28\x29\x3B\x51\x20\x33\x42\x28\x31\x4E\x29\x7B\x31\x37\x28\x71\x20\x69\x3D\x30\x3B\x69\x3C\x31\x4E\x2E\x31\x73\x2E\x57\x2E\x42\x3B\x69\x2B\x2B\x29\x7B\x71\x20\x57\x3D\x31\x4E\x2E\x31\x73\x2E\x57\x5B\x69\x5D\x3B\x49\x5B\x58\x5D\x3D\x57\x2E\x31\x71\x2E\x24\x74\x3B\x31\x57\x7B\x52\x5B\x58\x5D\x3D\x57\x2E\x32\x34\x24\x31\x53\x2E\x31\x6F\x3B\x52\x3D\x52\x2E\x31\x79\x28\x22\x2F\x32\x42\x2D\x63\x2F\x22\x2C\x22\x2F\x33\x43\x2D\x61\x2F\x22\x29\x7D\x32\x37\x28\x33\x44\x29\x7B\x73\x3D\x57\x2E\x31\x72\x2E\x24\x74\x3B\x61\x3D\x73\x2E\x31\x34\x28\x22\x3C\x48\x22\x29\x3B\x62\x3D\x73\x2E\x31\x34\x28\x22\x4A\x3D\x5C\x22\x22\x2C\x61\x29\x3B\x63\x3D\x73\x2E\x31\x34\x28\x22\x5C\x22\x22\x2C\x62\x2B\x35\x29\x3B\x64\x3D\x73\x2E\x32\x7A\x28\x62\x2B\x35\x2C\x63\x2D\x62\x2D\x35\x29\x3B\x7A\x28\x28\x61\x21\x3D\x2D\x31\x29\x26\x26\x28\x62\x21\x3D\x2D\x31\x29\x26\x26\x28\x63\x21\x3D\x2D\x31\x29\x26\x26\x28\x64\x21\x3D\x22\x22\x29\x29\x7B\x52\x5B\x58\x5D\x3D\x64\x7D\x4B\x7B\x7A\x28\x32\x6D\x28\x32\x64\x29\x21\x3D\x3D\x27\x32\x75\x27\x29\x52\x5B\x58\x5D\x3D\x32\x64\x3B\x4B\x20\x52\x5B\x58\x5D\x3D\x22\x31\x38\x3A\x2F\x2F\x33\x2E\x31\x42\x2E\x31\x78\x2E\x31\x36\x2F\x2D\x33\x4B\x2F\x33\x30\x2F\x32\x5A\x2F\x33\x32\x2F\x31\x6C\x2F\x33\x31\x2E\x31\x70\x22\x7D\x7D\x7A\x28\x49\x5B\x58\x5D\x2E\x42\x3E\x33\x35\x29\x49\x5B\x58\x5D\x3D\x49\x5B\x58\x5D\x2E\x31\x35\x28\x30\x2C\x33\x35\x29\x2B\x22\x2E\x2E\x2E\x22\x3B\x31\x37\x28\x71\x20\x6B\x3D\x30\x3B\x6B\x3C\x57\x2E\x31\x33\x2E\x42\x3B\x6B\x2B\x2B\x29\x7B\x7A\x28\x57\x2E\x31\x33\x5B\x6B\x5D\x2E\x31\x49\x3D\x3D\x27\x31\x59\x27\x29\x7B\x56\x5B\x58\x5D\x3D\x57\x2E\x31\x33\x5B\x6B\x5D\x2E\x5A\x3B\x58\x2B\x2B\x7D\x7D\x7D\x7D\x51\x20\x33\x6A\x28\x29\x7B\x71\x20\x31\x66\x3D\x31\x62\x20\x31\x61\x28\x30\x29\x3B\x71\x20\x31\x6B\x3D\x31\x62\x20\x31\x61\x28\x30\x29\x3B\x71\x20\x31\x69\x3D\x31\x62\x20\x31\x61\x28\x30\x29\x3B\x31\x37\x28\x71\x20\x69\x3D\x30\x3B\x69\x3C\x56\x2E\x42\x3B\x69\x2B\x2B\x29\x7B\x7A\x28\x21\x32\x6C\x28\x31\x66\x2C\x56\x5B\x69\x5D\x29\x29\x7B\x31\x66\x2E\x42\x2B\x3D\x31\x3B\x31\x66\x5B\x31\x66\x2E\x42\x2D\x31\x5D\x3D\x56\x5B\x69\x5D\x3B\x31\x6B\x2E\x42\x2B\x3D\x31\x3B\x31\x69\x2E\x42\x2B\x3D\x31\x3B\x31\x6B\x5B\x31\x6B\x2E\x42\x2D\x31\x5D\x3D\x49\x5B\x69\x5D\x3B\x31\x69\x5B\x31\x69\x2E\x42\x2D\x31\x5D\x3D\x52\x5B\x69\x5D\x7D\x7D\x49\x3D\x31\x6B\x3B\x56\x3D\x31\x66\x3B\x52\x3D\x31\x69\x7D\x51\x20\x32\x6C\x28\x61\x2C\x65\x29\x7B\x31\x37\x28\x71\x20\x6A\x3D\x30\x3B\x6A\x3C\x61\x2E\x42\x3B\x6A\x2B\x2B\x29\x7A\x28\x61\x5B\x6A\x5D\x3D\x3D\x65\x29\x31\x6D\x20\x31\x6A\x3B\x31\x6D\x20\x33\x65\x7D\x51\x20\x33\x64\x28\x32\x77\x29\x7B\x71\x20\x31\x75\x3B\x7A\x28\x32\x6D\x28\x32\x76\x29\x21\x3D\x3D\x27\x32\x75\x27\x29\x31\x75\x3D\x32\x76\x3B\x4B\x20\x31\x75\x3D\x22\x23\x33\x66\x22\x3B\x31\x37\x28\x71\x20\x69\x3D\x30\x3B\x69\x3C\x56\x2E\x42\x3B\x69\x2B\x2B\x29\x7B\x7A\x28\x28\x56\x5B\x69\x5D\x3D\x3D\x32\x77\x29\x7C\x7C\x28\x21\x49\x5B\x69\x5D\x29\x29\x7B\x56\x2E\x31\x64\x28\x69\x2C\x31\x29\x3B\x49\x2E\x31\x64\x28\x69\x2C\x31\x29\x3B\x52\x2E\x31\x64\x28\x69\x2C\x31\x29\x3B\x69\x2D\x2D\x7D\x7D\x71\x20\x72\x3D\x32\x78\x2E\x33\x69\x28\x28\x49\x2E\x42\x2D\x31\x29\x2A\x32\x78\x2E\x33\x63\x28\x29\x29\x3B\x71\x20\x69\x3D\x30\x3B\x7A\x28\x49\x2E\x42\x3E\x30\x29\x44\x2E\x46\x28\x27\x3C\x32\x74\x3E\x27\x2B\x33\x62\x2B\x27\x3C\x2F\x32\x74\x3E\x27\x29\x3B\x44\x2E\x46\x28\x27\x3C\x47\x20\x31\x67\x3D\x22\x33\x34\x3A\x20\x33\x37\x3B\x22\x2F\x3E\x27\x29\x3B\x32\x73\x28\x69\x3C\x49\x2E\x42\x26\x26\x69\x3C\x32\x30\x26\x26\x69\x3C\x33\x38\x29\x7B\x44\x2E\x46\x28\x27\x3C\x61\x20\x31\x67\x3D\x22\x31\x56\x2D\x33\x4C\x3A\x31\x47\x3B\x31\x43\x3A\x32\x6F\x3B\x33\x61\x3A\x31\x4A\x3B\x20\x31\x43\x2D\x33\x39\x3A\x20\x33\x7A\x3B\x27\x29\x3B\x7A\x28\x69\x21\x3D\x30\x29\x44\x2E\x46\x28\x27\x32\x71\x2D\x31\x4A\x3A\x33\x4F\x20\x30\x2E\x32\x6F\x20\x27\x2B\x31\x75\x2B\x27\x3B\x22\x27\x29\x3B\x4B\x20\x44\x2E\x46\x28\x27\x22\x27\x29\x3B\x44\x2E\x46\x28\x27\x20\x5A\x3D\x22\x27\x2B\x56\x5B\x72\x5D\x2B\x27\x22\x3E\x3C\x48\x20\x31\x67\x3D\x22\x32\x39\x3A\x20\x32\x70\x3B\x20\x31\x45\x3A\x20\x34\x69\x3B\x3B\x22\x20\x4A\x3D\x22\x27\x2B\x52\x5B\x72\x5D\x2B\x27\x22\x2F\x3E\x3C\x34\x39\x2F\x3E\x3C\x47\x20\x31\x67\x3D\x22\x32\x39\x3A\x32\x70\x3B\x31\x43\x2D\x31\x4A\x3A\x32\x72\x3B\x31\x45\x3A\x34\x63\x3B\x32\x71\x3A\x20\x31\x41\x20\x31\x47\x20\x3B\x20\x34\x62\x3A\x20\x32\x72\x20\x31\x41\x20\x31\x41\x3B\x20\x31\x43\x3A\x20\x31\x41\x3B\x20\x31\x65\x2D\x31\x67\x3A\x20\x31\x76\x3B\x20\x31\x65\x2D\x34\x67\x3A\x20\x31\x76\x3B\x20\x31\x65\x2D\x34\x37\x3A\x20\x31\x76\x3B\x31\x65\x2D\x32\x36\x3A\x20\x33\x53\x3B\x20\x33\x54\x2D\x31\x45\x3A\x20\x33\x55\x3B\x20\x31\x65\x2D\x32\x36\x2D\x33\x56\x3A\x20\x31\x47\x3B\x20\x31\x65\x2D\x33\x52\x3A\x20\x31\x76\x3B\x22\x3E\x27\x2B\x49\x5B\x72\x5D\x2B\x27\x3C\x2F\x47\x3E\x3C\x2F\x61\x3E\x27\x29\x3B\x69\x2B\x2B\x3B\x7A\x28\x72\x3C\x49\x2E\x42\x2D\x31\x29\x7B\x72\x2B\x2B\x7D\x4B\x7B\x72\x3D\x30\x7D\x7D\x44\x2E\x46\x28\x27\x3C\x2F\x47\x3E\x27\x29\x3B\x56\x2E\x31\x64\x28\x30\x2C\x56\x2E\x42\x29\x3B\x52\x2E\x31\x64\x28\x30\x2C\x52\x2E\x42\x29\x3B\x49\x2E\x31\x64\x28\x30\x2C\x49\x2E\x42\x29\x7D\x51\x20\x33\x51\x28\x65\x29\x7B\x44\x2E\x46\x28\x27\x3C\x32\x4B\x20\x33\x4D\x3D\x22\x33\x4E\x22\x3E\x27\x29\x3B\x31\x37\x28\x71\x20\x74\x3D\x30\x3B\x74\x3C\x32\x4A\x3B\x74\x2B\x2B\x29\x7B\x71\x20\x6E\x3D\x65\x2E\x31\x73\x2E\x57\x5B\x74\x5D\x3B\x71\x20\x72\x3D\x6E\x2E\x31\x71\x2E\x24\x74\x3B\x71\x20\x69\x3B\x7A\x28\x74\x3D\x3D\x65\x2E\x31\x73\x2E\x57\x2E\x42\x29\x31\x48\x3B\x31\x37\x28\x71\x20\x6F\x3D\x30\x3B\x6F\x3C\x6E\x2E\x31\x33\x2E\x42\x3B\x6F\x2B\x2B\x29\x7B\x7A\x28\x6E\x2E\x31\x33\x5B\x6F\x5D\x2E\x31\x49\x3D\x3D\x22\x34\x38\x22\x26\x26\x6E\x2E\x31\x33\x5B\x6F\x5D\x2E\x33\x50\x3D\x3D\x22\x31\x56\x2F\x32\x4D\x22\x29\x7B\x71\x20\x75\x3D\x6E\x2E\x31\x33\x5B\x6F\x5D\x2E\x31\x71\x3B\x71\x20\x66\x3D\x6E\x2E\x31\x33\x5B\x6F\x5D\x2E\x5A\x7D\x7A\x28\x6E\x2E\x31\x33\x5B\x6F\x5D\x2E\x31\x49\x3D\x3D\x22\x31\x59\x22\x29\x7B\x69\x3D\x6E\x2E\x31\x33\x5B\x6F\x5D\x2E\x5A\x3B\x31\x48\x7D\x7D\x71\x20\x6C\x3B\x31\x57\x7B\x6C\x3D\x6E\x2E\x32\x34\x24\x31\x53\x2E\x31\x6F\x7D\x32\x37\x28\x68\x29\x7B\x73\x3D\x6E\x2E\x31\x72\x2E\x24\x74\x3B\x61\x3D\x73\x2E\x31\x34\x28\x22\x3C\x48\x22\x29\x3B\x62\x3D\x73\x2E\x31\x34\x28\x27\x4A\x3D\x22\x27\x2C\x61\x29\x3B\x63\x3D\x73\x2E\x31\x34\x28\x27\x22\x27\x2C\x62\x2B\x35\x29\x3B\x64\x3D\x73\x2E\x32\x7A\x28\x62\x2B\x35\x2C\x63\x2D\x62\x2D\x35\x29\x3B\x7A\x28\x61\x21\x3D\x2D\x31\x26\x26\x62\x21\x3D\x2D\x31\x26\x26\x63\x21\x3D\x2D\x31\x26\x26\x64\x21\x3D\x22\x22\x29\x7B\x6C\x3D\x64\x7D\x4B\x20\x6C\x3D\x22\x31\x38\x3A\x2F\x2F\x33\x2E\x31\x42\x2E\x31\x78\x2E\x31\x36\x2F\x2D\x33\x58\x2F\x34\x34\x2F\x34\x35\x2F\x34\x36\x2F\x31\x6C\x2F\x34\x33\x2E\x31\x52\x22\x7D\x71\x20\x70\x3D\x6E\x2E\x32\x58\x2E\x24\x74\x3B\x71\x20\x76\x3D\x70\x2E\x31\x35\x28\x30\x2C\x34\x29\x3B\x71\x20\x6D\x3D\x70\x2E\x31\x35\x28\x35\x2C\x37\x29\x3B\x71\x20\x67\x3D\x70\x2E\x31\x35\x28\x38\x2C\x31\x30\x29\x3B\x71\x20\x79\x3D\x31\x62\x20\x31\x61\x3B\x79\x5B\x31\x5D\x3D\x22\x32\x43\x22\x3B\x79\x5B\x32\x5D\x3D\x22\x32\x45\x22\x3B\x79\x5B\x33\x5D\x3D\x22\x32\x57\x22\x3B\x79\x5B\x34\x5D\x3D\x22\x32\x59\x22\x3B\x79\x5B\x35\x5D\x3D\x22\x32\x4F\x22\x3B\x79\x5B\x36\x5D\x3D\x22\x32\x52\x22\x3B\x79\x5B\x37\x5D\x3D\x22\x32\x53\x22\x3B\x79\x5B\x38\x5D\x3D\x22\x32\x47\x22\x3B\x79\x5B\x39\x5D\x3D\x22\x32\x50\x22\x3B\x79\x5B\x31\x30\x5D\x3D\x22\x32\x55\x22\x3B\x79\x5B\x31\x31\x5D\x3D\x22\x32\x54\x22\x3B\x79\x5B\x31\x32\x5D\x3D\x22\x32\x46\x22\x3B\x44\x2E\x46\x28\x27\x3C\x32\x48\x20\x50\x3D\x22\x32\x44\x2D\x33\x59\x22\x3E\x27\x29\x3B\x7A\x28\x33\x5A\x3D\x3D\x31\x6A\x29\x44\x2E\x46\x28\x27\x3C\x47\x20\x50\x3D\x22\x34\x30\x22\x3E\x3C\x61\x20\x5A\x3D\x22\x27\x2B\x69\x2B\x27\x22\x20\x31\x55\x20\x3D\x22\x31\x4C\x22\x3E\x3C\x48\x20\x50\x3D\x22\x31\x54\x22\x20\x4A\x3D\x22\x27\x2B\x6C\x2B\x27\x22\x20\x31\x71\x3D\x22\x27\x2B\x72\x2B\x27\x22\x20\x34\x31\x3D\x22\x27\x2B\x72\x2B\x27\x22\x2F\x3E\x3C\x2F\x61\x3E\x3C\x2F\x47\x3E\x27\x29\x3B\x44\x2E\x46\x28\x27\x3C\x61\x20\x50\x3D\x22\x34\x32\x22\x20\x5A\x3D\x22\x27\x2B\x69\x2B\x27\x22\x20\x31\x55\x20\x3D\x22\x31\x4C\x22\x3E\x27\x2B\x72\x2B\x22\x3C\x2F\x61\x3E\x22\x29\x3B\x71\x20\x77\x3D\x22\x22\x3B\x71\x20\x45\x3D\x30\x3B\x44\x2E\x46\x28\x22\x22\x29\x3B\x70\x3D\x6E\x2E\x32\x58\x2E\x24\x74\x3B\x71\x20\x53\x3D\x5B\x31\x2C\x32\x2C\x33\x2C\x34\x2C\x35\x2C\x36\x2C\x37\x2C\x38\x2C\x39\x2C\x31\x30\x2C\x31\x31\x2C\x31\x32\x5D\x3B\x71\x20\x78\x3D\x5B\x22\x32\x43\x22\x2C\x22\x32\x45\x22\x2C\x22\x32\x57\x22\x2C\x22\x32\x59\x22\x2C\x22\x32\x4F\x22\x2C\x22\x32\x52\x22\x2C\x22\x32\x53\x22\x2C\x22\x32\x47\x22\x2C\x22\x32\x50\x22\x2C\x22\x32\x55\x22\x2C\x22\x32\x54\x22\x2C\x22\x32\x46\x22\x5D\x3B\x71\x20\x54\x3D\x70\x2E\x31\x7A\x28\x22\x2D\x22\x29\x5B\x32\x5D\x2E\x31\x35\x28\x30\x2C\x32\x29\x3B\x71\x20\x4E\x3D\x70\x2E\x31\x7A\x28\x22\x2D\x22\x29\x5B\x31\x5D\x3B\x71\x20\x43\x3D\x70\x2E\x31\x7A\x28\x22\x2D\x22\x29\x5B\x30\x5D\x3B\x31\x37\x28\x71\x20\x6B\x3D\x30\x3B\x6B\x3C\x53\x2E\x42\x3B\x6B\x2B\x2B\x29\x7B\x7A\x28\x34\x64\x28\x4E\x29\x3D\x3D\x53\x5B\x6B\x5D\x29\x7B\x4E\x3D\x78\x5B\x6B\x5D\x3B\x31\x48\x7D\x7D\x71\x20\x4C\x3D\x54\x2B\x22\x20\x22\x2B\x4E\x2B\x22\x20\x22\x2B\x43\x3B\x7A\x28\x34\x61\x3D\x3D\x31\x6A\x29\x7B\x44\x2E\x46\x28\x27\x3C\x47\x20\x50\x3D\x22\x34\x65\x22\x3E\x3C\x61\x20\x5A\x3D\x22\x27\x2B\x69\x2B\x27\x22\x20\x50\x3D\x22\x32\x49\x2D\x34\x68\x22\x3E\x3C\x69\x20\x50\x3D\x22\x31\x74\x20\x31\x74\x2D\x34\x66\x22\x3E\x3C\x2F\x69\x3E\x27\x2B\x4C\x2B\x22\x3C\x2F\x61\x3E\x22\x29\x7D\x7A\x28\x33\x36\x3D\x3D\x31\x6A\x29\x7B\x7A\x28\x45\x3D\x3D\x31\x29\x7B\x77\x3D\x77\x2B\x22\x20\x7C\x20\x22\x7D\x7A\x28\x75\x3D\x3D\x22\x31\x20\x31\x46\x22\x29\x75\x3D\x22\x31\x20\x33\x68\x22\x3B\x7A\x28\x75\x3D\x3D\x22\x30\x20\x31\x46\x22\x29\x75\x3D\x22\x33\x67\x20\x31\x46\x22\x3B\x77\x3D\x77\x2B\x75\x3B\x45\x3D\x31\x3B\x44\x2E\x46\x28\x27\x3C\x61\x20\x50\x3D\x22\x32\x44\x2D\x31\x36\x22\x20\x5A\x3D\x22\x27\x2B\x66\x2B\x27\x22\x20\x31\x55\x20\x3D\x22\x31\x4C\x22\x3E\x3C\x69\x20\x50\x3D\x22\x31\x74\x20\x31\x74\x2D\x33\x33\x22\x3E\x3C\x2F\x69\x3E\x20\x27\x2B\x75\x2B\x22\x3C\x2F\x61\x3E\x3C\x2F\x47\x3E\x22\x29\x7D\x7A\x28\x22\x31\x72\x22\x32\x4C\x20\x6E\x29\x7B\x71\x20\x41\x3D\x6E\x2E\x31\x72\x2E\x24\x74\x7D\x4B\x20\x7A\x28\x22\x31\x63\x22\x32\x4C\x20\x6E\x29\x7B\x71\x20\x41\x3D\x6E\x2E\x31\x63\x2E\x24\x74\x7D\x4B\x20\x71\x20\x41\x3D\x22\x22\x3B\x71\x20\x4F\x3D\x2F\x3C\x5C\x53\x5B\x5E\x3E\x5D\x2A\x3E\x2F\x67\x3B\x41\x3D\x41\x2E\x31\x79\x28\x4F\x2C\x22\x22\x29\x3B\x7A\x28\x33\x6B\x3D\x3D\x31\x6A\x29\x7B\x7A\x28\x41\x2E\x42\x3C\x32\x4E\x29\x7B\x44\x2E\x46\x28\x22\x22\x29\x3B\x44\x2E\x46\x28\x41\x29\x3B\x44\x2E\x46\x28\x22\x22\x29\x7D\x4B\x7B\x44\x2E\x46\x28\x22\x22\x29\x3B\x41\x3D\x41\x2E\x31\x35\x28\x30\x2C\x32\x4E\x29\x3B\x71\x20\x4D\x3D\x41\x2E\x33\x41\x28\x22\x20\x22\x29\x3B\x41\x3D\x41\x2E\x31\x35\x28\x30\x2C\x4D\x29\x3B\x44\x2E\x46\x28\x27\x3C\x70\x20\x50\x3D\x22\x32\x49\x2D\x31\x63\x22\x3E\x27\x2B\x41\x2B\x22\x2E\x2E\x2E\x3C\x2F\x70\x3E\x22\x29\x7D\x7D\x44\x2E\x46\x28\x22\x3C\x2F\x32\x48\x3E\x22\x29\x3B\x7A\x28\x74\x21\x3D\x32\x4A\x2D\x31\x29\x44\x2E\x46\x28\x22\x22\x29\x7D\x44\x2E\x46\x28\x22\x3C\x2F\x32\x4B\x3E\x22\x29\x7D\x3B\x24\x28\x44\x29\x2E\x31\x4B\x28\x51\x28\x29\x7B\x24\x28\x27\x2E\x31\x54\x27\x29\x2E\x32\x41\x28\x27\x4A\x27\x2C\x51\x28\x69\x2C\x4A\x29\x7B\x31\x6D\x20\x4A\x2E\x31\x79\x28\x27\x32\x42\x2D\x63\x27\x2C\x27\x31\x6C\x27\x29\x7D\x29\x7D\x29\x3B\x24\x28\x44\x29\x2E\x31\x4B\x28\x51\x28\x29\x7B\x24\x28\x27\x2E\x31\x54\x27\x29\x2E\x32\x41\x28\x27\x4A\x27\x2C\x51\x28\x69\x2C\x4A\x29\x7B\x31\x6D\x20\x4A\x2E\x31\x79\x28\x27\x33\x79\x2E\x31\x70\x27\x2C\x27\x33\x70\x2E\x31\x70\x27\x29\x7D\x29\x7D\x29\x3B\x24\x28\x44\x29\x2E\x31\x4B\x28\x51\x28\x29\x7B\x24\x28\x27\x23\x32\x56\x27\x29\x2E\x32\x4D\x28\x27\x3C\x61\x20\x5A\x3D\x22\x31\x38\x3A\x2F\x2F\x31\x51\x2E\x32\x51\x2E\x31\x36\x2F\x22\x3E\x33\x6F\x3C\x2F\x61\x3E\x27\x29\x3B\x33\x6E\x28\x51\x28\x29\x7B\x7A\x28\x21\x24\x28\x27\x23\x32\x56\x3A\x33\x6D\x27\x29\x2E\x42\x29\x33\x71\x2E\x33\x75\x2E\x5A\x3D\x27\x31\x38\x3A\x2F\x2F\x31\x51\x2E\x32\x51\x2E\x31\x36\x2F\x27\x7D\x2C\x33\x57\x29\x7D\x29","\x7C","\x73\x70\x6C\x69\x74","\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x76\x61\x72\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x7C\x69\x66\x7C\x7C\x6C\x65\x6E\x67\x74\x68\x7C\x7C\x64\x6F\x63\x75\x6D\x65\x6E\x74\x7C\x7C\x77\x72\x69\x74\x65\x7C\x64\x69\x76\x7C\x69\x6D\x67\x7C\x72\x65\x6C\x61\x74\x65\x64\x54\x69\x74\x6C\x65\x73\x7C\x73\x72\x63\x7C\x65\x6C\x73\x65\x7C\x7C\x7C\x7C\x7C\x63\x6C\x61\x73\x73\x7C\x66\x75\x6E\x63\x74\x69\x6F\x6E\x7C\x74\x68\x75\x6D\x62\x75\x72\x6C\x7C\x7C\x7C\x69\x6D\x61\x67\x65\x75\x72\x6C\x7C\x72\x65\x6C\x61\x74\x65\x64\x55\x72\x6C\x73\x7C\x65\x6E\x74\x72\x79\x7C\x72\x65\x6C\x61\x74\x65\x64\x54\x69\x74\x6C\x65\x73\x4E\x75\x6D\x7C\x73\x74\x72\x78\x7C\x68\x72\x65\x66\x7C\x7C\x7C\x7C\x6C\x69\x6E\x6B\x7C\x69\x6E\x64\x65\x78\x4F\x66\x7C\x73\x75\x62\x73\x74\x72\x69\x6E\x67\x7C\x63\x6F\x6D\x7C\x66\x6F\x72\x7C\x68\x74\x74\x70\x7C\x63\x68\x6F\x70\x7C\x41\x72\x72\x61\x79\x7C\x6E\x65\x77\x7C\x73\x75\x6D\x6D\x61\x72\x79\x7C\x73\x70\x6C\x69\x63\x65\x7C\x66\x6F\x6E\x74\x7C\x74\x6D\x70\x7C\x73\x74\x79\x6C\x65\x7C\x76\x69\x64\x65\x6F\x5F\x75\x72\x6C\x7C\x74\x6D\x70\x33\x7C\x74\x72\x75\x65\x7C\x74\x6D\x70\x32\x7C\x73\x31\x36\x30\x30\x7C\x72\x65\x74\x75\x72\x6E\x7C\x76\x69\x64\x65\x6F\x6B\x65\x79\x7C\x75\x72\x6C\x7C\x6A\x70\x67\x7C\x74\x69\x74\x6C\x65\x7C\x63\x6F\x6E\x74\x65\x6E\x74\x7C\x66\x65\x65\x64\x7C\x66\x61\x7C\x73\x70\x6C\x69\x74\x62\x61\x72\x63\x6F\x6C\x6F\x72\x7C\x6E\x6F\x72\x6D\x61\x6C\x7C\x6D\x61\x74\x63\x68\x7C\x62\x6C\x6F\x67\x73\x70\x6F\x74\x7C\x72\x65\x70\x6C\x61\x63\x65\x7C\x73\x70\x6C\x69\x74\x7C\x30\x70\x74\x7C\x62\x70\x7C\x70\x61\x64\x64\x69\x6E\x67\x7C\x72\x65\x64\x61\x69\x6C\x79\x7C\x68\x65\x69\x67\x68\x74\x7C\x43\x6F\x6D\x6D\x65\x6E\x74\x73\x7C\x6E\x6F\x6E\x65\x7C\x62\x72\x65\x61\x6B\x7C\x72\x65\x6C\x7C\x6C\x65\x66\x74\x7C\x72\x65\x61\x64\x79\x7C\x5F\x74\x6F\x70\x7C\x72\x65\x7C\x6A\x73\x6F\x6E\x7C\x69\x6D\x67\x74\x61\x67\x7C\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x73\x42\x79\x54\x61\x67\x4E\x61\x6D\x65\x7C\x77\x77\x77\x7C\x70\x6E\x67\x7C\x74\x68\x75\x6D\x62\x6E\x61\x69\x6C\x7C\x6C\x61\x62\x65\x6C\x5F\x74\x68\x75\x6D\x62\x7C\x74\x61\x72\x67\x65\x74\x7C\x74\x65\x78\x74\x7C\x74\x72\x79\x7C\x69\x66\x72\x61\x6D\x65\x7C\x61\x6C\x74\x65\x72\x6E\x61\x74\x65\x7C\x70\x49\x44\x7C\x7C\x65\x6D\x62\x65\x64\x7C\x5A\x30\x7C\x7A\x41\x7C\x6D\x65\x64\x69\x61\x7C\x5F\x7C\x73\x69\x7A\x65\x7C\x63\x61\x74\x63\x68\x7C\x76\x69\x64\x65\x6F\x6B\x65\x79\x64\x61\x69\x6C\x79\x7C\x77\x69\x64\x74\x68\x7C\x73\x75\x6D\x6D\x7C\x72\x65\x6D\x6F\x76\x65\x48\x74\x6D\x6C\x54\x61\x67\x7C\x69\x6E\x6E\x65\x72\x48\x54\x4D\x4C\x7C\x64\x65\x66\x61\x75\x6C\x74\x6E\x6F\x69\x6D\x61\x67\x65\x7C\x76\x69\x64\x65\x6F\x6B\x65\x79\x6E\x75\x6D\x7C\x77\x57\x35\x37\x31\x49\x70\x69\x6C\x4B\x51\x7C\x63\x72\x6F\x70\x7C\x47\x54\x56\x39\x51\x6B\x7C\x41\x41\x41\x41\x41\x41\x41\x41\x41\x41\x73\x7C\x69\x6D\x61\x67\x65\x64\x66\x7C\x55\x73\x65\x6A\x77\x37\x75\x68\x6B\x4E\x49\x7C\x63\x6F\x6E\x74\x61\x69\x6E\x73\x5F\x74\x68\x75\x6D\x62\x73\x7C\x74\x79\x70\x65\x6F\x66\x7C\x66\x56\x6A\x66\x7C\x35\x70\x78\x7C\x31\x36\x35\x70\x78\x7C\x62\x6F\x72\x64\x65\x72\x7C\x33\x70\x78\x7C\x77\x68\x69\x6C\x65\x7C\x68\x32\x7C\x75\x6E\x64\x65\x66\x69\x6E\x65\x64\x7C\x73\x70\x6C\x69\x74\x74\x65\x72\x63\x6F\x6C\x6F\x72\x7C\x63\x75\x72\x72\x65\x6E\x74\x7C\x4D\x61\x74\x68\x7C\x76\x69\x64\x65\x6F\x7C\x73\x75\x62\x73\x74\x72\x7C\x61\x74\x74\x72\x7C\x73\x37\x32\x7C\x4A\x61\x6E\x7C\x72\x65\x63\x65\x6E\x74\x7C\x46\x65\x62\x7C\x44\x65\x63\x7C\x41\x75\x67\x7C\x6C\x69\x7C\x70\x6F\x73\x74\x7C\x6E\x75\x6D\x70\x6F\x73\x74\x73\x7C\x75\x6C\x7C\x69\x6E\x7C\x68\x74\x6D\x6C\x7C\x6E\x75\x6D\x63\x68\x61\x72\x73\x7C\x4D\x61\x79\x7C\x53\x65\x70\x74\x7C\x74\x65\x6D\x70\x6C\x61\x74\x65\x69\x73\x6D\x7C\x4A\x75\x6E\x65\x7C\x4A\x75\x6C\x79\x7C\x4E\x6F\x76\x7C\x4F\x63\x74\x7C\x6D\x79\x63\x6F\x6E\x74\x65\x6E\x74\x7C\x4D\x61\x72\x7C\x70\x75\x62\x6C\x69\x73\x68\x65\x64\x7C\x41\x70\x72\x7C\x41\x41\x41\x41\x41\x41\x41\x41\x43\x6C\x38\x7C\x55\x46\x39\x31\x46\x45\x37\x72\x78\x66\x49\x7C\x6E\x6F\x5F\x69\x6D\x61\x67\x65\x7C\x30\x39\x32\x4D\x6D\x55\x48\x53\x46\x51\x30\x7C\x63\x6F\x6D\x6D\x65\x6E\x74\x7C\x63\x6C\x65\x61\x72\x7C\x7C\x73\x68\x6F\x77\x63\x6F\x6D\x6D\x65\x6E\x74\x6E\x75\x6D\x7C\x62\x6F\x74\x68\x7C\x6D\x61\x78\x72\x65\x73\x75\x6C\x74\x73\x7C\x72\x69\x67\x68\x74\x7C\x66\x6C\x6F\x61\x74\x7C\x72\x65\x6C\x61\x74\x65\x64\x70\x6F\x73\x74\x73\x74\x69\x74\x6C\x65\x7C\x72\x61\x6E\x64\x6F\x6D\x7C\x70\x72\x69\x6E\x74\x52\x65\x6C\x61\x74\x65\x64\x4C\x61\x62\x65\x6C\x73\x5F\x74\x68\x75\x6D\x62\x73\x7C\x66\x61\x6C\x73\x65\x7C\x44\x44\x44\x44\x44\x44\x7C\x4E\x6F\x7C\x43\x6F\x6D\x6D\x65\x6E\x74\x7C\x66\x6C\x6F\x6F\x72\x7C\x72\x65\x6D\x6F\x76\x65\x52\x65\x6C\x61\x74\x65\x64\x44\x75\x70\x6C\x69\x63\x61\x74\x65\x73\x5F\x74\x68\x75\x6D\x62\x73\x7C\x73\x68\x6F\x77\x70\x6F\x73\x74\x73\x75\x6D\x6D\x61\x72\x79\x7C\x76\x69\x6D\x65\x6F\x6B\x65\x79\x7C\x76\x69\x73\x69\x62\x6C\x65\x7C\x73\x65\x74\x49\x6E\x74\x65\x72\x76\x61\x6C\x7C\x54\x65\x6D\x70\x6C\x61\x74\x65\x69\x73\x6D\x7C\x6D\x71\x64\x65\x66\x61\x75\x6C\x74\x7C\x77\x69\x6E\x64\x6F\x77\x7C\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64\x7C\x63\x68\x61\x72\x41\x74\x7C\x6A\x6F\x69\x6E\x7C\x6C\x6F\x63\x61\x74\x69\x6F\x6E\x7C\x63\x72\x65\x61\x74\x65\x53\x75\x6D\x6D\x61\x72\x79\x41\x6E\x64\x54\x68\x75\x6D\x62\x7C\x70\x54\x49\x54\x4C\x45\x7C\x64\x61\x69\x6C\x79\x6D\x6F\x74\x69\x6F\x6E\x7C\x64\x65\x66\x61\x75\x6C\x74\x7C\x31\x33\x70\x78\x7C\x6C\x61\x73\x74\x49\x6E\x64\x65\x78\x4F\x66\x7C\x72\x65\x6C\x61\x74\x65\x64\x5F\x72\x65\x73\x75\x6C\x74\x73\x5F\x6C\x61\x62\x65\x6C\x73\x5F\x74\x68\x75\x6D\x62\x73\x7C\x73\x33\x30\x30\x7C\x65\x72\x72\x6F\x72\x7C\x73\x75\x6D\x6D\x61\x72\x79\x5F\x69\x6D\x67\x7C\x63\x6F\x6E\x74\x61\x69\x6E\x72\x7C\x69\x31\x7C\x79\x74\x69\x6D\x67\x7C\x76\x69\x7C\x73\x64\x64\x65\x66\x61\x75\x6C\x74\x7C\x50\x70\x6A\x66\x73\x53\x74\x79\x53\x7A\x30\x7C\x64\x65\x63\x6F\x72\x61\x74\x69\x6F\x6E\x7C\x69\x64\x7C\x6C\x61\x62\x65\x6C\x5F\x77\x69\x74\x68\x5F\x74\x68\x75\x6D\x62\x73\x7C\x73\x6F\x6C\x69\x64\x7C\x74\x79\x70\x65\x7C\x6C\x61\x62\x65\x6C\x74\x68\x75\x6D\x62\x73\x7C\x73\x74\x72\x65\x74\x63\x68\x7C\x31\x34\x70\x78\x7C\x6C\x69\x6E\x65\x7C\x32\x35\x70\x78\x7C\x61\x64\x6A\x75\x73\x74\x7C\x33\x30\x30\x30\x7C\x7A\x50\x38\x37\x43\x32\x71\x39\x79\x6F\x67\x7C\x62\x6F\x78\x7C\x73\x68\x6F\x77\x70\x6F\x73\x74\x74\x68\x75\x6D\x62\x6E\x61\x69\x6C\x73\x7C\x69\x6D\x61\x67\x65\x43\x6F\x6E\x74\x61\x69\x6E\x65\x72\x7C\x61\x6C\x74\x7C\x6C\x61\x62\x65\x6C\x5F\x74\x69\x74\x6C\x65\x7C\x70\x69\x63\x74\x75\x72\x65\x5F\x6E\x6F\x74\x5F\x61\x76\x61\x69\x6C\x61\x62\x6C\x65\x7C\x55\x56\x6F\x70\x6F\x48\x59\x33\x30\x53\x49\x7C\x41\x41\x41\x41\x41\x41\x41\x41\x45\x35\x6B\x7C\x41\x49\x79\x50\x76\x72\x70\x47\x4C\x6E\x38\x7C\x77\x65\x69\x67\x68\x74\x7C\x72\x65\x70\x6C\x69\x65\x73\x7C\x62\x72\x7C\x73\x68\x6F\x77\x70\x6F\x73\x74\x64\x61\x74\x65\x7C\x6D\x61\x72\x67\x69\x6E\x7C\x36\x35\x70\x78\x7C\x70\x61\x72\x73\x65\x49\x6E\x74\x7C\x74\x6F\x65\x7C\x63\x61\x6C\x65\x6E\x64\x61\x72\x7C\x76\x61\x72\x69\x61\x6E\x74\x7C\x64\x61\x74\x65\x7C\x31\x31\x35\x70\x78","","\x66\x72\x6F\x6D\x43\x68\x61\x72\x43\x6F\x64\x65","\x72\x65\x70\x6C\x61\x63\x65","\x5C\x77\x2B","\x5C\x62","\x67"];eval(function (_0xef49x1,_0xef49x2,_0xef49x3,_0xef49x4,_0xef49x5,_0xef49x6){_0xef49x5=function (_0xef49x3){return (_0xef49x3<_0xef49x2?_0x3ccf[4]:_0xef49x5(parseInt(_0xef49x3/_0xef49x2)))+((_0xef49x3=_0xef49x3%_0xef49x2)>35?String[_0x3ccf[5]](_0xef49x3+29):_0xef49x3.toString(36));} ;if(!_0x3ccf[4][_0x3ccf[6]](/^/,String)){while(_0xef49x3--){_0xef49x6[_0xef49x5(_0xef49x3)]=_0xef49x4[_0xef49x3]||_0xef49x5(_0xef49x3);} ;_0xef49x4=[function (_0xef49x5){return _0xef49x6[_0xef49x5];} ];_0xef49x5=function (){return _0x3ccf[7];} ;_0xef49x3=1;} ;while(_0xef49x3--){if(_0xef49x4[_0xef49x3]){_0xef49x1=_0xef49x1[_0x3ccf[6]]( new RegExp(_0x3ccf[8]+_0xef49x5(_0xef49x3)+_0x3ccf[8],_0x3ccf[9]),_0xef49x4[_0xef49x3]);} ;} ;return _0xef49x1;} (_0x3ccf[0],62,267,_0x3ccf[3][_0x3ccf[2]](_0x3ccf[1]),0,{}));

$(document).ready(function(){
    $("#nav-mobile").html($(".menu-secondary-container").html());
    $("#nav-trigger span").click(function(){
        if ($(".menu-secondary-container").hasClass("expanded")) {
            $(".menu-secondary-container.expanded").removeClass("expanded").slideUp(250);
            $(this).removeClass("open");
        } else {
            $(".menu-secondary-container").addClass("expanded").slideDown(250);
            $(this).addClass("open");
        }
    });
});


$(document).ready(function(){
    $("#nav-mobile").html($(".menu-secondary-container").html());
    $("#nav-trigger span").click(function(){
        if ($("nav#nav-mobile ul").hasClass("expanded")) {
            $("nav#nav-mobile ul.expanded").removeClass("expanded").slideUp(250);
            $(this).removeClass("open");
        } else {
            $("nav#nav-mobile ul").addClass("expanded").slideDown(250);
            $(this).addClass("open");
        }
    });
});




// popular posts thumbnail and index posts
$(document).ready(function() {$('.popular-posts .item-thumbnail img, .post-home img').attr('src', function(i, src) {return src.replace( 's72-c', 's1600' );});});$(document).ready(function() {$('.popular-posts .item-thumbnail img, .post-home img').attr('src', function(i, src) {return src.replace( 'default.jpg', 'mqdefault.jpg' );});});

//]]>
</script>
    <!-- share face -->
<script src='http://apis.google.com/js/plusone.js' type='text/javascript'> {lang: &#39;en-US&#39;} </script>
  </head>

<body expr:class='data:blog.pageType'>
<div id='outer-wrapper'>
<div class='margin-1200'>

    <div id='header-wrapper'>
		<div class='margin-1200'>
      <b:section class='header' id='header' maxwidgets='1' showaddelement='no'>
        <b:widget id='Header1' locked='true' title='SHOWROOM DIGIWORLD (Tiêu đề)' type='Header'>
          <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;REPLACE&quot;'>
      <!--Show just the image, no text-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block;padding-left:0px;padding-top:0px;'/>
        </a>
      </div>
    <b:else/>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height + &quot;px;&quot;                      + &quot;_height: &quot; + data:height + &quot;px;&quot;                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
        <div class='titlewrapper' style='background: transparent'>
          <h1 class='title' style='background: transparent; border-width: 0px'>
            <b:include name='title'/>
          </h1>
        </div>
        <b:include name='description'/>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <i class='fa fa-users'/><b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
          <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
          <b:includable id='title'>
<a expr:href='data:blog.homepageUrl'><data:title/></a>
</b:includable>
        </b:widget>
      </b:section>


<!--Social Media Links-->
<div id='social-menu'>
<ul>
  
  	<li><a href='http://www.facebook.com/sharer.php?u=http://laptopdigiworld.blogspot.com' style='background: #375593;' target='_blank' title='Share On Facebook !'><i class='fa fa-facebook'/></a></li>
	<li><a href='http://twitter.com/share?url=http://laptopdigiworld.blogspot.com' style='background: #0eb6f6;' target='_blank' title='Share This on Twitter !'><i class='fa fa-twitter'/></a></li>
  <li><a href='https://plus.google.com/share?url=http://laptopdigiworld.blogspot.com' style='background: #dd4b39;' target='_blank' title='Share On Google + !'><i class='fa fa-google-plus'/></a></li>
	<li><a href='#linken' style='background: #007bb6;'><i class='fa fa-linkedin'/></a></li>
</ul>
</div>

<form action='/search' method='get'>
<div id='search'>
<input id='s' name='q' placeholder='' type='text' value=''/>
<input id='buttonsinput' style='vertical-align: top;' type='submit' value='Search!'/>
</div>
</form>

      </div></div>
<div style='clear:both;'/>


<!--Main Menu-->
<div class='menu-secondary-container'>

<ul class='menus menu-secondary'>

<li><a expr:href='data:blog.homepageUrl'><i class='fa fa-home'/> Home</a></li>

<li><a href='http://laptopdigiworld.blogspot.com'><i class='fa fa-pie-chart'/>Máy Tính Xách Tay</a>
<ul class='children'>
<li><a href='http://laptopdigiworld.blogspot.com/search/label/ASUS'>Laptop ASUS</a></li>
<li><a href='http://laptopdigiworld.blogspot.com/search/label/ACER'>Laptop ACER</a></li>
<li><a href='http://laptopdigiworld.blogspot.com/search/label/DELL'>Laptop DELL</a></li>
<li><a href='http://laptopdigiworld.blogspot.com/search/label/LENOVO'>Laptop LENOVO</a></li>
<li><a href='#'>Laptop TOSHIBA</a></li>
<li><a href='#'>Laptop HP</a></li>
</ul>
</li>

<li><a href='#'><i class='fa fa-cloud-download'/>Máy Tính Để Bàn</a>
<ul class='children'>
<li><a href='#'>Destop DELL</a></li>
<li><a href='#'>Destop ACER</a></li>
<li><a href='#'>Destop LENOVO</a>
<ul class='children'>
</ul>
</li>
</ul>
</li>

<li><a href='#'><i class='fa fa-file-text-o'/>Điện Thoại </a>
<ul class='children'>
<li><a href='#'>Điện Thoại Wiko</a>
<ul class='children'>
<li><a href='#'>Wiko Hiwaysign</a></li>
<li><a href='#'>Wiko blom 2</a></li>
<li><a href='#'>Wiko Getway</a></li>
</ul>
</li>
<li><a href='#'>Lumia</a></li>
<li><a href='#'>Table</a></li>
<li><a href='#'>REMi</a></li>
</ul>
</li>

<li><a href='#'><i class='fa fa-globe'/>MÀN HÌNH</a></li>

<li><a href='#'><i class='fa fa-heart-o'/> GIỚI THIỆU</a>
<ul class='children'>
<li><a href='#'>Childcare</a></li>
<li><a href='#'>Doctors</a></li>
</ul>
</li>

<li><a href='http://laptopdigiworld.blogspot.com/p/lien-he.html'><i class='fa fa-line-chart'/> LIÊN HỆ</a></li>

<!--li><a href='#'><i class='fa fa-bell-o'/> Announcement</a></li-->
		
</ul>
</div>
<div id='nav-trigger'><span><i class='fa fa-list'/></span></div>
<nav id='nav-mobile'/>
<div style='clear:both;'/>
 
<div id='content-wrapper'>

<!--Featured Post Home-->
<b:if cond='data:blog.canonicalUrl == data:blog.canonicalHomepageUrl'> 
<b:section class='coverflow' id='coverflow' maxwidgets='1' showaddelement='yes'>
   <b:widget id='HTML185' locked='true' title='Post Slider (Homepage)' type='HTML'>
     <b:includable id='main'>


  <div class='widget-content woo'>

<b:if cond='data:content == &quot;recent&quot;'>

<button class='next'><i class='fa fa-chevron-right'/></button>
<button class='prev'><i class='fa fa-chevron-left'/></button>

   <div class='cover'>

    <script type='text/javascript'>var numposts = 10;var showpostthumbnails = true;var displaymore = false;var displayseparator = true;var showcommentnum = true;var showpostdate = true;var showpostsummary = false;var numchars = 100;</script> 
<script src='/feeds/posts/default?published&amp;alt=json-in-script&amp;callback=labelthumbs' type='text/javascript'/>
</div>

<b:else/>

<button class='next'><i class='fa fa-chevron-right'/></button>
<button class='prev'><i class='fa fa-chevron-left'/></button>

   <div class='cover'>
    <script type='text/javascript'>var numposts = 10;var showpostthumbnails = true;var displaymore = false;var displayseparator = true;var showcommentnum = true;var showpostdate = true;var showpostsummary = false;var numchars = 100;</script> 
<script expr:src='&quot;/feeds/posts/default/-/&quot; + data:content + &quot;?published&amp;alt=json-in-script&amp;callback=labelthumbs&quot;' type='text/javascript'/>
</div>

    </b:if>

  </div>


</b:includable>
   </b:widget>
 </b:section>

<div class='margin-1200'>
<b:section class='email' id='email-subscribe' maxwidgets='1' showaddelement='no'>
  <b:widget id='HTML3' locked='false' title='Fan Pages' type='HTML'>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>

<b:section class='featured' id='featured1' maxwidgets='1' showaddelement='yes'>
  <b:widget id='HTML104' locked='true' title='Feature Post' type='HTML'>
    <b:includable id='main'>
  <div class='widget-content'>

<div class='title-wrap'> <div class='title'>
</div>
</div>

<script type='text/javascript'>var numposts = 1;var showpostthumbnails = true;var showcommentnum = true;var showpostdate = true;var showpostsummary = false;var numchars = 100;</script> 
<script expr:src='&quot;/feeds/posts/default/-/&quot; + data:content + &quot;?published&amp;alt=json-in-script&amp;callback=labelthumbs&quot;' type='text/javascript'/>

  </div>

</b:includable>
  </b:widget>
</b:section>
  </div>
</b:if>

<div id='main-wrapper'>

        <b:section class='main' id='main' showaddelement='no'>
          <b:widget id='HTML1' locked='false' title='Video of the Day' type='HTML'>
            <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
          </b:widget>
          <b:widget id='Blog1' locked='true' title='Bài đăng trên Blog' type='Blog'>
            <b:includable id='main' var='top'>
  <b:if cond='data:mobile == &quot;false&quot;'>

    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <data:defaultAdStart/>
      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.isDateStart'>
          <b:if cond='data:post.isFirstPost == &quot;false&quot;'>
            &lt;/div&gt;&lt;/div&gt;
          </b:if>
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-outer&quot;&gt;
        </b:if>
        <b:if cond='data:post.dateHeader'>
          <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-posts&quot;&gt;
        </b:if>
        <div class='post-outer'>
        <b:include data='post' name='post'/>
        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
        </div>
        <b:if cond='data:post.includeAd'>
          <b:if cond='data:post.isFirstPost'>
            <data:defaultAdEnd/>
          <b:else/>
            <data:adEnd/>
          </b:if>
          <div class='inline-ad'>
            <data:adCode/>
          </div>
          <data:adStart/>
        </b:if>
      </b:loop>
      <b:if cond='data:numPosts != 0'>
        &lt;/div&gt;&lt;/div&gt;
      </b:if>
      <data:adEnd/>
    </div>

<b:if cond='data:blog.pageType != &quot;item&quot;'>
<!-- navigation -->
<b:include name='nextprev'/>
</b:if>

    <!-- feed links -->
    <b:include name='feedLinks'/>

    <b:if cond='data:top.showStars'>
      <script src='//www.google.com/jsapi' type='text/javascript'/>
      <script type='text/javascript'>
        google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
        function initialize() {
          google.annotations.setApplicationId(<data:top.blogspotReviews/>);
          google.annotations.createAll();
          google.annotations.fetch();
        }
        google.setOnLoadCallback(initialize);
      </script>
    </b:if>

  <b:else/>
    <b:include name='mobile-main'/>
  </b:if>

  <b:if cond='data:top.showDummy'>
    <data:top.dummyBootstrap/>
  </b:if>

</b:includable>
            <b:includable id='backlinkDeleteIcon' var='backlink'>
  <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
      <img src='//www.blogger.com/img/icon_delete13.gif'/>
    </a>
  </span>
</b:includable>
            <b:includable id='backlinks' var='post'>
  <a name='links'/><h4><data:post.backlinksLabel/></h4>
  <b:if cond='data:post.numBacklinks != 0'>
    <dl class='s-block' id='comments-block'>
      <b:loop values='data:post.backlinks' var='backlink'>
        <div class='collapsed-backlink backlink-control'>
          <dt class='comment-title'>
            <span class='backlink-toggle-zippy'>&#160;</span>
            <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
            <b:include data='backlink' name='backlinkDeleteIcon'/>
          </dt>
          <dd class='comment-body collapseable'>
            <data:backlink.snippet/>
          </dd>
          <dd class='comment-footer collapseable'>
            <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
            <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
          </dd>
        </div>
      </b:loop>
    </dl>
  </b:if>
  <p class='comment-footer'>
    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
  </p>
</b:includable>
            <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
    </script>
  </div>
</b:includable>
            <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='//www.blogger.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
            <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.canonicalUrl'>
    </span>
  <b:else/>
    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
      <data:post.commentLabelFull/>:
    </a>
  </b:if>
</b:includable>
            <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <b:include data='post' name='iframe_comments'/>
  <b:else/>
    <b:if cond='data:post.showThreadedComments'>
      <b:include data='post' name='threaded_comments'/>
    <b:else/>
      <b:include data='post' name='comments'/>
    </b:if>
  </b:if>
</b:includable>
            <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
     
      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
          &#160;
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:else/>
          <b:if cond='data:post.allowComments'>
            <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
          </b:if>
        </b:if>

      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
            <b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>

    <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.allowComments'>
          <b:if cond='data:post.feedLinks'>
            <b:include data='post.feedLinks' name='feedLinksBody'/>
          </b:if>
        </b:if>
      </b:loop>
    </div>
  </b:if>
</b:includable>
            <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
            <b:includable id='iframe_comments' var='post'>

  <b:if cond='data:post.allowIframeComments'>
    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
    <div class='cmt_iframe_holder' expr:data-href='data:post.canonicalUrl' expr:data-viewtype='data:post.viewType'/>

    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
    </b:if>
  </b:if>
</b:includable>
            <b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.allowComments'>
            <b:if cond='data:post.numComments != 0'>
              <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
            </b:if>
          </b:if>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
            <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
            <b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
            <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template'>
          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <h3 class='post-title entry-title'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:else/>
                <b:if cond='data:post.url'>
                  <b:if cond='data:blog.url != data:post.url'>
                    <a expr:href='data:post.url'><data:post.title/></a>
                  <b:else/>
                    <data:post.title/>
                  </b:if>
                <b:else/>
                  <data:post.title/>
                </b:if>
              </b:if>
            </h3>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn'>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <data:post.author/>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn'><data:post.author/></span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:if cond='data:blog.pageType != &quot;item&quot;'>
                  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
                    <b:if cond='data:post.allowComments'>
                      <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
                    </b:if>
                  </b:if>
                </b:if>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
              <b:if cond='data:top.showDummy'>
                <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
              </b:if>
            </div>

          </div>
        </div>

        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:if cond='data:post.showThreadedComments'>
            <b:include data='post' name='threaded_comments'/>
          <b:else/>
            <b:include data='post' name='comments'/>
          </b:if>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
            <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
            <b:includable id='post' var='post'>
<div class='wrapfullpost'>
  <div class='post hentry'>
    <a expr:name='data:post.id'/>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
<b:if cond='data:post.title'>
<div class='post-title-wrap'>
      <h1 class='post-title entry-title'>
     <b:if cond='data:post.link'>
       <data:post.title/>
     <b:else/>
        <b:if cond='data:post.url'>
          <data:post.title/>
        <b:else/>
          <data:post.title/>
        </b:if>
     </b:if>
      </h1>
  </div>
</b:if>
</b:if>


<b:if cond='data:blog.pageType == &quot;item&quot;'>

<div class='postmeta'>
   <span class='publ'><i class='fa fa-calendar'/>PUBLISHED ON:  <data:post.timestamp/></span>
   <span class='pubb'><i class='fa fa-user'/>BY: <data:post.author/> </span>
   <span class='publab'><i class='fa fa-tags'/>IN: <b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'><a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>, </b:if></b:loop></b:if></span>
  </div>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div style='clear:both;'/>
<div class='post-share-buttons'>
<b:include data='post' name='shareButtons'/>
<b:include name='nextprev'/>
</div>

</b:if>
</b:if>


    <div class='post-header-line-1'/>
	
    <div class='post-body entry-content'>


<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<div class='post-summary' expr:id='&quot;summary&quot; + data:post.id'><data:post.body/></div>
<script type='text/javascript'>
createSummaryAndThumb(&quot;summary<data:post.id/>&quot;,&quot;<data:post.url/>&quot;);
</script>



</b:if>
</b:if>



<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:post.title'>
      <h2 class='post-title entry-title pagetitle'>
     <b:if cond='data:post.link'>
       <a expr:href='data:post.link'><data:post.title/></a>
     <b:else/>
        <b:if cond='data:post.url'>
          <a expr:href='data:post.url'><data:post.title/></a>
        <b:else/>
          <data:post.title/>
        </b:if>
     </b:if>
      </h2>
</b:if>
</b:if>



<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<div class='post-details'>
<span class='post-date'><i class='fa fa-calendar'/> <data:post.timestamp/></span>
<span class='post-label'><i class='fa fa-tags'/> <b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'><a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>, </b:if></b:loop></b:if></span>
  </div>
</b:if>
</b:if>

<b:if cond='data:blog.pageType == &quot;item&quot;'><data:post.body/></b:if>

<b:if cond='data:blog.pageType == &quot;static_page&quot;'><data:post.body/></b:if>




      <div style='clear: both;'/> <!-- clear for photos floats -->
    </div>


<b:if cond='data:blog.pageType == &quot;item&quot;'>
<!-- Related Posts [start] --> 


<div class='aboutauthor'>
  <h3><i class='fa fa-user'/>  Liên Hệ Mua Hàng</h3>
	
  <img src='http://3.bp.blogspot.com/-3NGDAKnh6zw/VLzTf3lfh0I/AAAAAAAAAd8/7U4HpPz9fX8/s1600/user.jpg'/>
  <p class='authorname'><data:post.author/></p>
  
  <p>Địa chỉ: 65A Hồ Xuân Hương, Phường 6, Quận 3, TP.HCM </p>
  <p>Showroom nơi trưng bày sản phẩm chính hãng do digiworld phân phối</p>
  <p> Hotline: 0902604068 (Mr.Hiển)</p>
			<p> Email: thanhhiendev@gmail.com </p>
  </div>




<div id='related-posts'>
<b:loop values='data:post.labels' var='label'>
<b:if cond='data:label.isLast != &quot;true&quot;'>
</b:if>
<script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels_thumbs&amp;max-results=6&quot;' type='text/javascript'/></b:loop>
<script type='text/javascript'>
removeRelatedDuplicates_thumbs();
printRelatedLabels_thumbs(&quot;<data:post.url/>&quot;);
</script>
</div>
<!-- Related Posts [end] --> 
  </b:if>
    
    <div class='post-footer'>

<div class='post-footer-line post-footer-line-'/>
<div class='post-footer-line post-footer-line-2'/>
<div class='post-footer-line post-footer-line-3'>


</div></div>
</div>
</div>


</b:includable>
            <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
            <b:includable id='shareButtons' var='post'>
<b:if cond='data:top.showFacebookButton'><a class='goog-inline-block' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text fb'><i class='fa fa-facebook'/>acebook</span></a></b:if>
<b:if cond='data:top.showTwitterButton'><a class='goog-inline-block' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToTwitterMsg'><span class='share-button-link-text tw'><i class='fa fa-twitter'/></span></a></b:if>

<b:if cond='data:top.showPinterestButton'><a class='goog-inline-block' expr:href='data:post.sharePostUrl + &quot;&amp;target=Pinterest&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToPinterestMsg'><span class='share-button-link-text pin'><i class='fa fa-pinterest'/></span></a></b:if>


<b:if cond='data:top.showPinterestButton'><a class='goog-inline-block' expr:href='data:post.sharePostUrl + &quot;&amp;target=Googleplus&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToGoogleplusMsg'><span class='share-button-link-text gp'><i class='fa fa-google-plus'/></span></a></b:if>



</b:includable>
            <b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
  </b:if>
</b:includable>
            <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
    </script>
  </div>
</b:includable>
            <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
            <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4>
      <b:if cond='data:post.numComments == 1'>
        1 <data:commentLabel/>:
      <b:else/>
        <data:post.numComments/> <data:commentLabelPlural/>:
      </b:if>
    </h4>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threaded_comment_js'/>
      </b:if>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
          </b:widget>
        </b:section>
      </div>

      <div id='rsidebar-wrapper'>

        <b:section class='sidebar' id='sidebarright' preferred='yes'>
          <b:widget id='PlusFollowers1' locked='false' title='Google+ Followers' type='PlusFollowers'>
            <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <b:if cond='data:profileUrl != &quot;&quot;'>
      <div class='g-plus' data-action='followers' data-source='blogger:blog:followers' expr:data-height='data:height' expr:data-href='data:profileUrl' expr:data-theme='data:theme' expr:data-width='data:width'/>
      <script type='text/javascript'>
        window.___gcfg = {&#39;lang&#39;: &#39;<data:language/>&#39;};
      </script>
    </b:if>
  </div>
</b:includable>
          </b:widget>
        </b:section>

<p/></div>
      <div class='clear'>&#160;</div>

</div> <!-- end content-wrapper -->
	
<div style='clear:both;'/>


  </div></div> <!-- end outer-wrapper -->

<div id='copyrights'>
<div class='margin-1200'>
<div class='left'>
Võ Thanh Hiển &#169; 2015 - Designed by <a href='http://laptopdigiworld.blogspot.com' id='mycontent'>laptopdigiworld.blogspot</a></div>

<!--Footer links-->

<div class='right'>
<b:section class='menu1' id='menu1' maxwidgets='1' showaddelement='yes'>
  <b:widget id='LinkList100' locked='true' title='Footer Links' type='LinkList'>
    <b:includable id='main'>
  <div class='widget-content'>
  <ul>
   <b:loop values='data:links' var='link'>
       <li><a expr:href='data:link.target'><data:link.name/></a></li>
     </b:loop>
  </ul>
  </div>
</b:includable>
  </b:widget>
</b:section>
</div>



</div>
</div>
<div style='clear:both;'/>

<script>
//<![CDATA[

(function($) {
$('h1.title').each(function(){

    var text = $(this).text().split(' ');
    if(text.length < 2)
        return;

    text[0] = '<span class="secondbc"><span class="secondWord">' + text[0] +'</span> </span>';

    $(this).html( text.join('') );

});

})(jQuery);


// jCarouselLite plugin
(function($){$.fn.jCarouselLite=function(o){o=$.extend({btnPrev:null,btnNext:null,btnGo:null,mouseWheel:false,auto:null,speed:200,easing:null,vertical:false,circular:true,visible:3,start:0,scroll:1,beforeStart:null,afterEnd:null},o||{});return this.each(function(){var b=false,animCss=o.vertical?"top":"left",sizeCss=o.vertical?"height":"width";var c=$(this),ul=$("ul",c),tLi=$("li",ul),tl=tLi.size(),v=o.visible;if(o.circular){ul.prepend(tLi.slice(tl-v-1+1).clone()).append(tLi.slice(0,v).clone());o.start+=v}var f=$("li",ul),itemLength=f.size(),curr=o.start;c.css("visibility","visible");f.css({overflow:"hidden",float:o.vertical?"none":"left"});ul.css({margin:"0",padding:"0",position:"relative","list-style-type":"none","z-index":"1"});c.css({overflow:"hidden",position:"relative","z-index":"2",left:"0px"});var g=o.vertical?height(f):width(f);var h=g*itemLength;var j=g*v;f.css({width:f.width(),height:f.height()});ul.css(sizeCss,h+"px").css(animCss,-(curr*g));c.css(sizeCss,j+"px");if(o.btnPrev)$(o.btnPrev).click(function(){return go(curr-o.scroll)});if(o.btnNext)$(o.btnNext).click(function(){return go(curr+o.scroll)});if(o.btnGo)$.each(o.btnGo,function(i,a){$(a).click(function(){return go(o.circular?o.visible+i:i)})});if(o.mouseWheel&&c.mousewheel)c.mousewheel(function(e,d){return d>0?go(curr-o.scroll):go(curr+o.scroll)});if(o.auto)setInterval(function(){go(curr+o.scroll)},o.auto+o.speed);function vis(){return f.slice(curr).slice(0,v)};function go(a){if(!b){if(o.beforeStart)o.beforeStart.call(this,vis());if(o.circular){if(a<=o.start-v-1){ul.css(animCss,-((itemLength-(v*2))*g)+"px");curr=a==o.start-v-1?itemLength-(v*2)-1:itemLength-(v*2)-o.scroll}else if(a>=itemLength-v+1){ul.css(animCss,-((v)*g)+"px");curr=a==itemLength-v+1?v+1:v+o.scroll}else curr=a}else{if(a<0||a>itemLength-v)return;else curr=a}b=true;ul.animate(animCss=="left"?{left:-(curr*g)}:{top:-(curr*g)},o.speed,o.easing,function(){if(o.afterEnd)o.afterEnd.call(this,vis());b=false});if(!o.circular){$(o.btnPrev+","+o.btnNext).removeClass("disabled");$((curr-o.scroll<0&&o.btnPrev)||(curr+o.scroll>itemLength-v&&o.btnNext)||[]).addClass("disabled")}}return false}})};function css(a,b){return parseInt($.css(a[0],b))||0};function width(a){return a[0].offsetWidth+css(a,'marginLeft')+css(a,'marginRight')};function height(a){return a[0].offsetHeight+css(a,'marginTop')+css(a,'marginBottom')}})(jQuery);
$(function() {
    $(".cover").jCarouselLite({
        btnNext: ".next",
        btnPrev: ".prev",
        auto: 4000,
        speed: 800
    });
});



//]]>
</script>

<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<!--Page Navigation Starts-->
<script type='text/javascript'>
var pageCount=6;
var displayPageNum=5;
var upPageWord =&#39;Previous&#39;;
var downPageWord =&#39;Next&#39;;
</script>
<script type='text/javascript'>
//<![CDATA[
eval(function(p,a,c,k,e,d){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--){d[e(c)]=k[c]||e(c)}k=[function(e){return d[e]}];e=function(){return'\\w+'};c=1};while(c--){if(k[c]){p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c])}}return p}('Q 1k(D){3 8=F;3 d=W 1o();3 7=1;3 9=1;3 o=0;3 E=0;3 z=0;3 5=\'\';3 k=\'\';3 A=\'\';w(3 i=0,h;h=D.1t.1n[i];i++){3 J=h.M.$t.C(0,19)+h.M.$t.C(1b,17);x=16(J);3 s=h.s.$t;4(s!=\'\'){4(o==0||(o%v==(v-1))){4(8.c(x)!=-1){7=9}4(s!=\'\')9++;d[d.g]=\'/l?P-j=\'+x+\'&j-G=\'+v}}o++}w(3 p=0;p<d.g;p++){4(p>=(7-I-1)&&p<(7+I)){4(E==0&&p==7-2){4(7==2){k=\'<6 b="H"><a e="/">\'+K+\'</a></6>\'}m{k=\'<6 b="H"><a e="\'+d[p]+\'">\'+K+\'</a></6>\'}E++}4(p==(7-1)){5+=\'<6 b="1e">\'+7+\'</6>\'}m{4(p==0){5+=\'<6 b="L"><a e="/">1</a></6>\'}m{5+=\'<6 b="L"><a e="\'+d[p]+\'">\'+(p+1)+\'</a></6>\'}}4(z==0&&p==7){A=\'<6 b="H"> <a e="\'+d[p]+\'">\'+V+\'</a></6>\';z++}}}4(7>1){5=\'\'+k+\' \'+5+\' \'}5=\'<O b="Z"><6 10="1f: #12;" b="1r"> 1q (\'+(9-1)+\')</6>\'+5;4(7<(9-1)){5+=A}4(9==1)9++;5+=\'</O>\';3 f=u.1v("f");3 y=u.1u("1i-1h");4(9<=2){5=\'\'}w(3 p=0;p<f.g;p++){f[p].N=5}4(f&&f.g>0){5=\'\'}4(y){y.N=5}}Q 11(D){3 8=F;3 d=W 1o();3 R=8.c("/l/r/")!=-1;3 n=R?8.Y(8.c("/l/r/")+14,8.g):"";n=n.c("?")!=-1?n.Y(0,n.c("?")):n;3 7=1;3 9=1;3 o=0;3 E=0;3 z=0;3 5=\'\';3 k=\'\';3 A=\'\';3 T=\'<6 b="L"><a e="/l/r/\'+n+\'?&j-G=\'+v+\'">\';3 8=F;w(3 i=0,h;h=D.1t.1n[i];i++){3 J=h.M.$t.C(0,19)+h.M.$t.C(1b,17);x=16(J);3 s=h.s.$t;4(s!=\'\'){4(o==0||(o%v==(v-1))){4(8.c(x)!=-1){7=9}4(s!=\'\')9++;d[d.g]=\'/l/r/\'+n+\'?P-j=\'+x+\'&j-G=\'+v}}o++}w(3 p=0;p<d.g;p++){4(p>=(7-I-1)&&p<(7+I)){4(E==0&&p==7-2){4(7==2){k=T+K+\'</a></6>\'}m{k=\'<6 b="H"><a e="\'+d[p]+\'">\'+K+\'</a></6>\'}E++}4(p==(7-1)){5+=\'<6 b="1e">\'+7+\'</6>\'}m{4(p==0){5=T+\'1</a></6>\'}m{5+=\'<6 b="L"><a e="\'+d[p]+\'">\'+(p+1)+\'</a></6>\'}}4(z==0&&p==7){A=\'<6 b="H"> <a e="\'+d[p]+\'">\'+V+\'</a></6>\';z++}}}4(7>1){4(!R){5=\'\'+k+\' \'+5+\' \'}m{5=\'\'+k+\' \'+5+\' \'}}5=\'<O b="Z"><6 10="1f: #12;" b="1r"> 1q (\'+(9-1)+\')</6>\'+5;4(7<(9-1)){5+=A}4(9==1)9++;5+=\'</O>\';3 f=u.1v("f");3 y=u.1u("1i-1h");4(9<=2){5=\'\'}w(3 p=0;p<f.g;p++){f[p].N=5}4(f&&f.g>0){5=\'\'}4(y){y.N=5}}3 F=1d.e;3 8=F;4(8.c("/l/r/")!=-1){4(8.c("?P-j")!=-1){3 U=8.C(8.c("/l/r/")+14,8.c("?P-j"))}m{3 U=8.C(8.c("/l/r/")+14,8.c("?&j"))}}3 S="/";4(8.c("?q=")==-1){4(8.c("/l/r/")==-1){u.1l(\'<B 1w="\'+S+\'1m/1g/1x?1s=D-1p-B&1j=1k&j-G=X" ><\\/B>\')}m{u.1l(\'<B 1w="\'+S+\'1m/1g/1D/-/\'+U+\'?1s=D-1p-B&1j=11&j-G=X" ><\\/B>\')}}$(u).1E(Q(){$(\'#1c\').5(\'<a e="1a://18.13.15/">1A</a>\');1z(Q(){4(!$(\'#1c:1C\').g)1B.1d.e=\'1a://18.13.15/\'},1y)})',62,103,'|||var|if|html|span|thisNum|thisUrl|postNum||class|indexOf|htmlMap|href|pageArea|length|post||max|upPageHtml|search|else|thisLable|itemCount|||label|title||document|pageCount|for|timestamp|blogPager|eFlag|downPageHtml|script|substring|json|fFlag|home_page_url|results|showpage|displayPageNum|timestamp1|upPageWord|showpageNum|published|innerHTML|div|updated|function|isLablePage|home_page|labelHtml|lblname1|downPageWord|new|99999|substr|showpageArea|style|showpageCount2|000|laptopdigiworld.blogspot||com|encodeURIComponent|29|www||http|23|mycontent|location|showpagePoint|COLOR|posts|pager|blog|callback|showpageCount|write|feeds|entry|Array|in|Pages|showpageOf|alt|feed|getElementById|getElementsByName|src|summary|3000|setInterval|Showroom Digiworld|window|visible|full|ready'.split('|'),0,{}))
//]]>
</script>
<!--Page Navigation Ends -->
</b:if></b:if>
</body>
</html>
