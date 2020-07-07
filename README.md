# Git
Witget
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>

<link href='http://fonts.googleapis.com/css?family=Open+Sans+Condensed:700' rel='stylesheet' type='text/css'/>
<link href='//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css' rel='stylesheet'/>
<link href='https://www.blogger.com/static/v1/widgets/2674880080-widget_css_2_bundle.css' rel='stylesheet' type='text/css'/>

<!--[if lt IE 9]>
<script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"> </script>
<![endif]-->
<meta content='width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1' name='viewport'/>
<meta content='text/html;charset=UTF-8' http-equiv='Content-Type'/>
<meta content='IE=edge,chrome=1' http-equiv='X-UA-Compatible'/> 
<b:include data='blog' name='all-head-content'/>

<!-- SEO Meta Tag -->
<b:if cond='data:blog.homepageUrl == data:blog.url'><meta expr:content='data:blog.title' name='keywords'/></b:if>	   
<b:if cond='data:blog.pageType == &quot;item&quot;'><meta expr:content='data:blog.pageName' name='keywords'/></b:if>
<b:if cond='data:blog.pageType == &quot;index&quot;'><b:if cond='data:blog.searchLabel'><meta content='noindex,nofollow' name='robots'/></b:if></b:if>
<b:if cond='data:blog.pageType == &quot;archive&quot;'><meta content='noindex,nofollow' name='robots'/></b:if>
<b:if cond='data:blog.isMobile'><meta content='noindex,nofollow' name='robots'/></b:if>

<meta content='Belajar Blog dan SEO Bagi Pemula, Tips Optimasi Blog, Cara Membuat Blog Di Blogger, Template Blogger SEO Friendly, SEO Onpage, SEO Offpage, Backlink, Ping, Konten Berkualitas, Blog Terkenal, Cara Jadi Nomor Satu Di Google, Banyak Trafik Pengunjung, Membuat Template Blogger' name='keywords'/>
<meta content='Blog Personal tentang tips Blogging, Optimasi SEO, Sosial Media, Tips Internet dan Belajar Blog' name='description'/>
<meta content='Indonesia' name='geo.placename'/>
<meta content='Muhamad Budiman' name='Author'/>
<meta content='general' name='rating'/>
<meta content='id' name='geo.country'/>
<!-- SEO Title Tag -->
<b:if cond='data:blog.url == data:blog.homepageUrl'><title><data:blog.title/></title></b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'><title><data:blog.pageName/> | <data:blog.title/></title></b:if>
<b:if cond='data:blog.pageType == &quot;archive&quot;'><title>Archive for <data:blog.pageName/></title></b:if>
<b:if cond='data:blog.pageType == &quot;static_page&quot;'><title><data:blog.pageName/></title></b:if>
<b:if cond='data:blog.pageType == &quot;index&quot;'><b:if cond='data:blog.searchLabel'><title><data:blog.title/> - <data:blog.pageName/></title></b:if></b:if>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'><title>Page Not Found</title></b:if>
<b:if cond='data:blog.pageType == &quot;index&quot;'><b:if cond='data:blog.url != data:blog.homepageUrl'><title><data:blog.pageTitle/> - All Post</title></b:if></b:if>

<meta content='YOUR_APPLICATION_ID' property='fb:app_id'/>
<link href='http://fonts.googleapis.com/css?family=Fjalla+One' rel='stylesheet' type='text/css'/>
<link href='//netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css' rel='stylesheet'/>

<b:skin><![CDATA[/*
-----------------------------------------------
Blogger Template Style
Name:     Evo Magz v2.5 Template
Designer: Mas Sugeng Baik Hati dan Suka Menabung
URL:      http://www.mas-sugeng.com http://www.evotemplates.net

Thanks to :

- http://www.blogger.com
- http://www.dte.web.id
- http://fortawesome.github.io/Font-Awesome/
- https://github.com/tessalt/dropdowns
- https://github.com/matthewhall/matt-tabs
- http://meyerweb.com/eric/tools/css/reset/
- http://hontap.blogspot.com/2010/04/page-navigation-voi-phong-cach-wp.html

----------------------------------------------- */

/* Variable definitions
   ====================
   <Variable name="keycolor" description="Main Color" type="color" default="#66bbdd" value="#787878"/>

   <Group description="Page Text" selector="body">
     <Variable name="body.font" description="Font" type="font"
         default="normal normal 14px Arial, sans-serif" value="normal normal 14px Arial, sans-serif"/>
     <Variable name="body.text.color" description="Main Text Color" type="color" default="#333333" value="#333333"/>
   </Group>

   <Group description="Main Backgrounds" selector=".body-fauxcolumns-outer">
     <Variable name="body.background.color" description="Body Background" type="color" default="#dddddd" value="#F0F0F0"/>
     <Variable name="wrapper.background.color" description="Wrapper Background" type="color" default="#f9f9f9" value="#f9f9f9"/>
   </Group>
   
   <Variable name="body.background" description="Body Background" type="background"
       color="$(body.background.color)" default="$(color) none repeat scroll top left" value="$(color) none repeat scroll top left"/>
   <Variable name="body.background.override" description="Body Background Override" type="string" default="" value=""/>
   
   <Group description="Links" selector=".main-outer">
     <Variable name="link.color" description="Link Color" type="color" default="#EE3322" value="#EE3322"/>
     <Variable name="link.visited.color" description="Visited Color" type="color" default="#EE3322" value="#EE3322"/>
     <Variable name="link.hover.color" description="Hover Color" type="color" default="#0072C6" value="#0072C6"/>
   </Group>

   <Group description="Blog Title" selector=".header h1.title, .header p.title">
     <Variable name="header.font" description="Font" type="font"
         default="normal bold 24px Fjalla One, Arial, Helvetica, sans-serif" value="normal bold 24px Fjalla One, Arial, Helvetica, sans-serif"/>
     <Variable name="header.text.color" description="Title Color" type="color" default="#333333"  value="#333333"/>
   </Group>

   <Group description="Blog Description" selector=".header .description">
     <Variable name="description.text.color" description="Description Color" type="color" default="#555555" value="#555555"/>
   </Group>

   <Group description="Primary Navigation Menu" selector=".menu">
     <Variable name="menu1.font" description="Font" type="font"
        default="normal normal 12px Arial, sans-serif" value="normal normal 12px Arial, sans-serif"/>
     <Variable name="menu1.background.color" description="Background Color" type="color" default="#ffffff" value="#ffffff"/>
	 <Variable name="menu1.text.color" description="Text Color" type="color" default="#666666" value="#666666"/>
	 <Variable name="menu1.hover.color" description="Hover Color" type="color" default="#f5f5f5" value="#f5f5f5"/>
	 <Variable name="menu1.border.color" description="Border Color" type="color" default="#e5e5e5" value="#e5e5e5"/>
   </Group>

   <Group description="Secondary Navigation Menu" selector="#nav">
     <Variable name="menu.font" description="Font" type="font"
        default="normal bold 12px Arial, sans-serif" value="normal bold 12px Arial, sans-serif"/>
     <Variable name="menu.background.color" description="Background Color" type="color" default="#333333" value="#333333"/>
	 <Variable name="menu.navigation.text.color" description="Text Color" type="color" default="#ffffff" value="#ffffff"/>
	 <Variable name="menu.navigation.hover.color" description="Hover Color" type="color" default="#222222" value="#222222"/>
	 <Variable name="menu.navigation.border.color" description="Border Color" type="color" default="#E73138" value="#E73138"/>
   </Group>
   
   <Group description="Search Box" selector="#search-form">
     <Variable name="input.background.color" description="Input Background Color" type="color" default="#ffffff" value="#ffffff"/>
	 <Variable name="button.background.color" description="Button Background Color" type="color" default="#E73037" value="#E73037"/>
     <Variable name="input.color" description="Input Color" type="color" default="#666666" value="#666666"/>
	 <Variable name="button.color" description="Button Color" type="color" default="#ffffff" value="#ffffff"/>
   </Group>
   
   <Group description="Post" selector=".post">
     <Variable name="post.background.color" description="Background Color" type="color" default="#ffffff"  value="#ffffff"/>
	 <Variable name="post.border.color" description="Border Color" type="color" default="#e5e5e5"  value="#e5e5e5"/>
   </Group>   
   
   <Group description="Post Title" selector="h2.post-title, .comments h4, h1.post-title">
     <Variable name="post.title.font" description="Font" type="font"
         default="normal normal 20px Fjalla One, Helvetica, Arial, sans-serif" value="normal normal 20px Fjalla One, Helvetica, Arial, sans-serif"/>
	 <Variable name="post.title.color" description="Text Color" type="color" default="#EE3322" value="#EE3322"/>
   </Group>

   <Group description="Post Footer" selector=".post-info, span.lebel-thumb-footer">
     <Variable name="post.footer.background.color" description="Background Color" type="color"
         default="transparent" value="transparent"/>
     <Variable name="post.footer.text.color" description="Text Color" type="color" default="#8D8D8D" value="#666666"/>
   </Group>
   
   <Group description="Recent Post" selector=".recent-post-one-thumb .widget-content">
     <Variable name="recentpost.background.color" description="Background Color" type="color" default="#ffffff"  value="#ffffff"/>
	 <Variable name="recentpost.border.color" description="Border Color" type="color" default="#e5e5e5"  value="#e5e5e5"/>
   </Group>

   <Group description="Recent Post Widget Title" selector=".recent-post-title h2">
     <Variable name="recentpost.title.font" description="Title Font" type="font"
        default="normal bold 14px Arial, sans-serif" value="normal bold 14px Arial, sans-serif"/>
     <Variable name="recentpost.title.text.color" description="Title Color" type="color" default="#ffffff" value="#ffffff"/>
     <Variable name="recentpost.title.background.color" description="Background Color" type="color" default="#E73138" value="#E73138"/>
   </Group>
   
   <Group description="Recent Post Title" selector="span.label-thumb-title">
     <Variable name="recent.post.title.font" description="Font" type="font"
         default="normal normal 16px Fjalla One, Helvetica, Arial, sans-serif" value="normal normal 16px Fjalla One, Helvetica, Arial, sans-serif"/>
	 <Variable name="recent.post.title.color" description="Text Color" type="color" default="#EE3322" value="#EE3322"/>
   </Group>
   
   <Group description="Sidebar Widget Title" selector=".sidebar h2, .tabs-menu">
     <Variable name="sidebar.title.font" description="Title Font" type="font"
        default="normal bold 12px Arial, sans-serif" value="normal bold 12px Arial, sans-serif"/>
     <Variable name="sidebar.title.text.color" description="Title Color" type="color" default="#333333" value="#333333"/>
     <Variable name="sidebar.title.border.color" description="Border Color" type="color" default="#E73138" value="#E73138"/>
   </Group>
   
   <Group description="Bottombar" selector="#bottombar">
	 <Variable name="bottombar.background.color" description="Background" type="color" default="#454545" value="#454545"/>
     <Variable name="bottombar.color" description="Color" type="color" default="#dddddd" value="#dddddd"/>
	 <Variable name="bottombar.link.color" description="Link Color" type="color" default="#dddddd" value="#dddddd"/>
	 <Variable name="bottombar.hover.color" description="Hover Color" type="color" default="#ffffff" value="#ffffff"/>
	 <Variable name="bottombar.border.color" description="Border Color" type="color" default="#e5e5e5" value="#e5e5e5"/>
   </Group>
   
   <Group description="Bottombar Widget Title" selector="#bottombar h2">
     <Variable name="bottombar.title.font" description="Title Font" type="font"
        default="normal bold 16px Open Sans Condensed,Arial,sans-serif, sans-serif" value="normal bold 16px Open Sans Condensed,Arial,sans-serif"/>
     <Variable name="bottombar.title.text.color" description="Title Color" type="color" default="#eeeeee" value="#eeeeee"/>
     <Variable name="bottombar.title.border.color" description="Border Color" type="color" default="#eeeeee" value="#eeeeee"/>
   </Group>
   
   <Group description="Footer" selector="#footer-wrapper">
	 <Variable name="footer.background.color" description="Background" type="color" default="#333333" value="#333333"/>
     <Variable name="footer.color" description="Color" type="color" default="#eeeeee" value="#eeeeee"/>
	 <Variable name="footer.link.color" description="Link Color" type="color" default="#eeeeee" value="#eeeeee"/>
	 <Variable name="footer.hover.color" description="Hover Color" type="color" default="#ffffff" value="#ffffff"/>
   </Group>
   
   <Group description="Read More" selector="a.readmore, .label-size">
	 <Variable name="readmore.background.color" description="Background Color" type="color" default="#ffffff" value="#ffffff"/>
	 <Variable name="readmore.color" description="Color" type="color" default="#333333" value="#333333"/>
	 <Variable name="readmore.border.color" description="Border Color" type="color" default="#dddddd" value="#dddddd"/>
	 <Variable name="readmore.hover.color" description="Hover Color" type="color" default="#aaaaaa" value="#aaaaaa"/>
   </Group>

   <Group description="Back to Top" selector="#back-to-top"> 
     <Variable name="backtp.background.color" description="Background" type="color" default="#E73037" value="#E73037"/>
	 <Variable name="backtp.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
   </Group>

   <Group description="Label Cloud" selector=".label-size"> 
     <Variable name="label.background.color" description="Background" type="color" default="#E73037" value="#E73037"/>
	 <Variable name="label.color" description="Color" type="color" default="#ffffff" value="#ffffff"/>
	 <Variable name="label.hover.color" description="Hover Color" type="color" default="#333333" value="#333333"/>
	 <Variable name="label.count.color" description="Label Count" type="color" default="#333333" value="#333333"/>
   </Group>   
 
*/

/**
* Eric Meyer&#39;s Reset CSS v2.0 (http://meyerweb.com/eric/tools/css/reset/)
* http://cssreset.com
*/
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline;}
/* HTML5 display-role reset for older browsers */
article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block;}body{line-height:1;display:block;}*{margin:0;padding:0;}html{display:block;}ol,ul{list-style:none;}blockquote,q{quotes:none;}blockquote:before,blockquote:after,q:before,q:after{content:&#39;&#39;;content:none;}table{border-collapse:collapse;border-spacing:0;}

/* FRAMEWORK */
.navbar,.post-feeds,.feed-links{display:none;
}
.section,.widget{margin:0 0 0 0;padding:0 0 0 0;
}
strong,b{font-weight:bold;
}
cite,em,i{font-style:italic;
}
a:link{color:$(link.color);text-decoration:none;outline:none;transition:all 0.25s;-moz-transition:all 0.25s;-webkit-transition:all 0.25s;
}
a:visited{color:$(link.visited.color);text-decoration:none;
}
a:hover{color:$(link.hover.color);text-decoration:none;
}
a img{border:none;border-width:0;outline:none;
}
abbr,acronym{border-bottom:1px dotted;cursor:help;
}
sup,sub{vertical-align:baseline;position:relative;top:-.4em;font-size:86%;
}
sub{top:.4em;}small{font-size:86%;
}
kbd{font-size:80%;border:1px solid #999;padding:2px 5px;border-bottom-width:2px;border-radius:3px;
}
mark{background-color:#ffce00;color:black;
}
p,blockquote,pre,table,figure,hr,form,ol,ul,dl{margin:1.5em 0;
}
hr{height:1px;border:none;background-color:#666;
}
/* heading */
h1,h2,h3,h4,h5,h6{font-weight:bold;line-height:normal;margin:0 0 0.6em;
}
h1{font-size:200%
}
h2{font-size:180%
}
h3{font-size:160%
}
h4{font-size:140%
}
h5{font-size:120%
}
h6{font-size:100%
}
/* list */
ol,ul,dl{margin:.5em 0em .5em 3em
}
ol{list-style:decimal outside
}
ul{list-style:disc outside
}
li{margin:.5em 0
}
dt{font-weight:bold
}
dd{margin:0 0 .5em 2em
}
/* form */
input,button,select,textarea{font:inherit;font-size:100%;line-height:normal;vertical-align:baseline;
}
textarea{display:block;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;
}
/* code blockquote */
pre,code{font-family:&quot;Courier New&quot;,Courier,Monospace;color:inherit;
}
pre{white-space:pre;word-wrap:normal;overflow:auto;
}
blockquote{background:#f0f0f0;margin-left:2em;margin-right:2em;padding:1em 1em;font-style:italic;font-size:110%;
}
blockquote:before {
    content: "\f10d"; 
    font-family: FontAwesome;
    font-style: normal;
    font-weight: normal;
    text-decoration: inherit;
    padding-right:4px;
	color:#666;
}
/* blockquote:after{
    content: "\f10e"; 
    font-family: FontAwesome;
    font-style: normal;
    font-weight: normal;
    text-decoration: inherit;
    padding-left:4px;
} */
/* table */
.post-body table[border=&quot;1&quot;] th, .post-body table[border=&quot;1&quot;] td, .post-body table[border=&quot;1&quot;] caption{border:1px solid;padding:.2em .5em;text-align:left;vertical-align:top;
}
.post-body table.tr-caption-container {border:1px solid #e5e5e5;
}
.post-body th{font-weight:bold;
}
.post-body table[border=&quot;1&quot;] caption{border:none;font-style:italic;
}
.post-body table{
}
.post-body td, .post-body th{vertical-align:top;text-align:left;font-size:13px;padding:3px 5px;border:1px solid #e5e5e5;
}
.post-body th{background:#f0f0f0;
}
.post-body table.tr-caption-container td {border:none;padding:8px;
}
.post-body table.tr-caption-container, .post-body table.tr-caption-container img, .post-body img {max-width:100%;height:auto;
}
.post-body td.tr-caption {color:#666;font-size:80%;padding:0px 8px 8px !important;
}
img {
	max-width:100%;
	height:auto;
	border:0;
}
table {
	max-width:100%;
}

body#layout #wrapper, body#layout .post-container, body#layout .sidebar-container {
	padding:0 0 0 0;
}
body#layout #header-wrapper {
	margin-top:60px;
}
body#layout .panel {
	float:left;
	width:79px;
}

.clear {
	clear:both;
}
.clear:after {
	visibility:hidden;
	display:block;
	font-size:0;
	content:" ";
	clear:both;
	height:0;
}

body { 
	background:$(body.background);
	margin:0 0 0 0;
	padding:0 0 0 0;
	color:$(body.text.color);
	font:$(body.font);
	text-align:left;
}

/* WRAPPER */
#wrapper {
	background:#FFF none repeat scroll 0% 0%;
	max-width:1000px;
	margin:20px auto;
	padding:28px;
	overflow:hidden;
}
	
/* NAVIGATION MENU */
.menu {
font:normal normal 13px Open Sans Condensed, Arial, sans-serif;
padding:0 0;
background:#ffffff;
margin:0 auto;
height:38px;
border:1px solid #f0f0f0;
overflow:hidden;
text-transform:uppercase;
}
.nav-menu {
list-style-type:none;
margin:0 0 0 0;
padding:0 0 0 0;
}
.nav-menu li {
display:block;
float:left;
line-height:38px;
margin:0 0 0 0;
padding:0 0 0 0;
border-right:1px solid #f0f0f0;
}
.nav-menu li a {
background:#ffffff;
color:#8D8D8D;
display:block;
padding:0 8px;
}
.nav-menu li a:hover {
background:#f5f5f5;
}
ul.nav-social {
height:38px;
margin:0 0 0 0;
padding:0 0;
float:right;
}
ul.nav-social li {
display:inline-block;
list-style-type:none;
float:right;
margin:0 0;
padding:0 0;
border-right:none;
border-left:1px solid #f0f0f0;
}
ul.nav-social li a {
display:inline-block;
line-height:38px;
height:38px;
padding:0 8px;
margin:0 0 0 0;
color:#8D8D8D;
}
ul.nav-social li a i {
line-height:38px;
}
ul.nav-social li a:hover {
color:#fff;
}
ul.nav-social li a.fcb:hover {
background:#3B5A9B;
}
ul.nav-social li a.gpl:hover {
background:#DD4B39;
}
ul.nav-social li a.twt:hover {
background:#1BB2E9;
}
ul.nav-social li a.ytb:hover {
background:#ED3F41;
}
/* HEADER WRAPPER */
#header-wrapper {
	margin:0 auto;
	overflow:hidden;
}
.header {
	float:left;
	width:25.7%;
	max-width:257px;
	margin:15px 0;
}
.header h1.title,.header p.title {
	font:$(header.font);
	margin:0 0 0 0;
	text-transform:uppercase;
}
.header .description {
	color:$(description.text.color);
}
.header a {
	color:$(header.text.color);
}
.header a:hover {
	color:#999;
}
.header img {
	display:block;
}

.header-right {
	float:right;
	padding:0;
	overflow:hidden;
	margin:15px 0;
	width:72.8%;
	max-width:728px;
}
.header-right img {
	display:block;
}


/* NAVIGATION MENU 2 */
.toggleMenu {
    display:none;
    background:$(menu.navigation.border.color);
    padding:0 15px;
	height:48px;
	line-height:48px;
    color: #fff !important;
}
#nav {
	font:bold 14px Open Sans Condensed,Arial,sans-serif;
	background:$(menu.background.color);
	text-transform:uppercase;
	height:48px;
	line-height:48px;
}
.nav-menu2 {
	background:$(menu.background.color);
    list-style: none;
	margin:0 0 0 0;
     *zoom: 1;
	float:left;  
}
.nav-menu2:before,
.nav-menu2:after {
    content: " "; 
    display: table; 
}
.nav-menu2:after {
    clear: both;
}
.nav-menu2 ul {
    list-style: none;
	margin:0 0 0 0;
    width:12em;
}
.nav-menu2 a {
	display:block;
    padding:0 15px;
}
.nav-menu2 li {
    position: relative;
	margin:0 0;
}
.nav-menu2 > li {
    float: left;
}
.nav-menu2 > li > a {
    display: block;
	height:48px;
	line-height:48px;
	color:$(menu.navigation.text.color);
	box-shadow: 0 4px 0 $(menu.background.color) inset;
}
.nav-menu2 > li > a.active {
	background:$(menu.navigation.hover.color);
	box-shadow: 0 4px 0 $(menu.navigation.border.color) inset;
}
.nav-menu2 > li:hover > a {
	background:$(menu.navigation.hover.color);
	box-shadow: 0 4px 0 $(menu.navigation.border.color) inset;
}
.nav-menu2 li ul {
	background:#fff;
	display:block;
	position:absolute;
	left:0;
	z-index:10;
	visibility:hidden;
	opacity:0;
    -webkit-transition:all .25s ease-out;
       -moz-transition:all .25s ease-out;
        -ms-transition:all .25s ease-out;
         -o-transition:all .25s ease-out;
            transition:all .25s ease-out;
	border: 1px solid #d9d9d9;
	border: 1px solid rgba(217,217,217,1);
	box-shadow:0 0 2px rgba(0,0,0,0.2);
}
.nav-menu2 li li ul {
	left:100%;
	top:-1px;
}
.nav-menu2 > li.hover > ul {
	visibility:visible;
	opacity:10;
}
.nav-menu2 > li > ul:before {
	content:"";
	width:0px;
	height:0px;
	position:absolute;
	bottom:100%;
	left:20px;
	border-width:8px;
	border-style:solid;
	border-color:transparent transparent #fff transparent;
	display:block;
}

.nav-menu2 li li.hover ul {
	visibility:visible;
	opacity:10;
}
.nav-menu2 li li a {
    display: block;
	color:#333;
    position: relative;
    z-index:100;
	line-height:32px;
}
.nav-menu2 li li a:hover {
	background:#f0f0f0;
}
.nav-menu2 li li li a {
    background:#fff;
    z-index:20;
	color:#333;
}
.nav-menu2 li .parent:after {
    content: "\f107"; 
    font-family: FontAwesome;
    font-style: normal;
    font-weight: normal;
    text-decoration: inherit;
    padding-left:6px;
}



#search-form {
	background:$(menu.background.color);
	float:right;
	margin:0 0;
	width:200px;
}
#search-form table {
	width:100%;
	margin:0 0 0 0;
}
#search-form td.search-box {
	padding-right:30px;
}

#search-form input#search-box[type="text"] {
	background:$(input.background.color);
	height:36px;
	line-height:36px;
	margin:5px 0 5px 10px;
	padding:0 10px;
	width:99%;
	color:$(input.color);
	border:none;
}
#search-form input#search-button[type="submit"] {
	font-family: FontAwesome;
	background:$(button.background.color);
	color:$(button.color);
	height:36px;
	line-height:36px;
	margin:5px 10px 5px 0;
	padding:0 12px;
	border:none;
	outline:none;
	transition:all 0.25s;
	-moz-transition:all 0.25s;
	-webkit-transition:all 0.25s;
}
#search-form input#search-button[type="submit"]:hover{
	background:$(menu.navigation.hover.color);
	cursor:pointer;
}
#search-form input#search-box[type="text"]:focus {
	background:#eee;
	outline:none;
}

/* CONTENT WRAPPER */
#content-wrapper {
	background-color:transparent;
	background-image:url(http://2.bp.blogspot.com/-yNE4A_H3C2o/U1E6RPYNEpI/AAAAAAAADRQ/UOP1mUKaxGE/s1600/line.png);
	background-repeat:repeat-x;
	background-position:top center;
	margin:0 auto;
	padding:5px 0 0;
	word-wrap:break-word;
}
.largebanner {
	background:#fff;
	border-right:1px solid #e5e5e5;
	border-bottom:1px solid #e5e5e5;
	border-left:1px solid #e5e5e5;
	
}
.largebanner .widget {
	padding:15px 14px;
	overflow:hidden;
}
.largebanner img, .largebanner iframe{
	display:block;
	max-width:100%;
	border:none;
	overflow:hidden;
}


/* POST WRAPPER */
#post-wrapper {
	background:transparent;
	float:left;
	width:70%;
	max-width:700px;
	margin:0 0 10px;
}
.post-container {
	padding:15px 15px 0 0;
}
.breadcrumbs {
	font-size:11px;
	color:#666;
	padding:15px;
	margin:0 0 15px;
	background:$(post.background.color);
	border:1px solid $(post.border.color);
}
.post {
	background:$(post.background.color);
	border:1px solid $(post.border.color);
	margin:0 0 15px;
	padding:15px;
}
.post-body {
	line-height:1.6em;
}
h2.post-title, h1.post-title {
font:22px Open Sans Condensed,Helvetica,Arial,sans-serif;
}
h2.post-title a, h1.post-title a, h2.post-title, h1.post-title {
	color:$(post.title.color);
}
h2.post-title a:hover, h1.post-title a:hover {
	color:$(link.hover.color);
}
.img-thumbnail {
	background:#fbfbfb url(http://3.bp.blogspot.com/-ltyYh4ysBHI/U04MKlHc6pI/AAAAAAAADQo/PFxXaGZu9PQ/w200-h140-c/no-image.png) no-repeat center center;
	position:relative;
	float:left;
	width:200px;
	height:150px;
	margin:0 15px 0 0;
}
.img-thumbnail img {
	width:200px;
	height:150px;
}
span.rollover {
	opacity:0;
	-o-transition:all 1s;
	-moz-transition:all 1s;
	-webkit-transition:all 1s;
	background:#333;
	cursor: pointer;
	position: absolute;
	top:0;
	right:0;
	bottom:0;
	left:0;
	z-index: 1;
	opacity: 0;
}
span.rollover:before {
	content:"";
	position: absolute;
	background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAADx0RVh0QUxUVGFnAFRoaXMgaXMgdGhlIGljb24gZnJvbSBHZW50bGVmYWNlLmNvbSBmcmVlIGljb25zIHNldC4g2GvoxAAAAB90RVh0Q29weXJpZ2h0AFJPWUFMVFkgRlJFRSBMSUNFTlNFIN7Zi2kAAABFaVRYdERlc2NyaXB0aW9uAAAAAABUaGlzIGlzIHRoZSBpY29uIGZyb20gR2VudGxlZmFjZS5jb20gZnJlZSBpY29ucyBzZXQuILwR+BoAAAAjaVRYdENvcHlyaWdodAAAAAAAUk9ZQUxUWSBGUkVFIExJQ0VOU0UgJ10KSgAAAidJREFUeNqsVUuO2kAQtROQBomFhZBAIIRBYh3nBuMbMCcI3IAbZOYEmTkBzAnMMjvmBrBnkUYgxD9e8QfnlVVGlmVsQ6akJ7e6X326uqosSTfI+XxWgGfgj+UR7BnAo3SvHI/H6ul0+gtYITDAVRw9OYrxw+FQw6fp2hKyLL/TF1BxgW/4Vl3nPUCPx+NmqPHdbqft93vLhYYfD/sq0HV40DMipWa73XYAi1GNwO+6+MFvsl6vtc1mYzGaUQICT3V0oG98CSIjt1VUhsR4ieIgkUgIcFukQ/qxEAeXdTKZFFErDnoDZx0LqfuiUzU39ouI6sCJRL3RwYUf9gaC0kRYrVa1Gxz8YD0R5qANsskP9nOxWChhxpfLZQNclQvjPdBBKpUyQX7jaKhjjfl8ftUJzmrg/GI+6b4GOphOpw3MFiq5Ht/iEehivwYoLp46m82aOGu6yrqeTqdN31k0mUwUnj3UuSbmzneKHmvNQxV+BQB+PZPJtGj91Xs4Ho8VGOtg6bT5A41h7Ok0mtjJA5950/UBPGWz2d++03Q0Ginw3vGJlKSdz+efKAC+mTfydi6X63mVLn0wHA41TsO1mrebB0ZoBLeilqx9g8FgoHHkvhWCs5dCofB8z49KFkJQOoKM14vFYku6U2L8oNdqu66q6t3G7VFBg8lVuw6oSfRSqfRfxm0HZMg9c7gD9XK5/CF9gtiP3O/3NU4V5VyvVCo96ZPknwADAKtR4YfNlLm3AAAAAElFTkSuQmCC) 50% 50% no-repeat;
	width:24px;
	height:24px;
	margin:-12px;
	top:50%;
	left:50%;
}
span.rollover:hover {
	opacity: .7;
	-o-transition:all 1s;
	-moz-transition:all 1s;
	-webkit-transition:all 1s;
}
.post-info {
background:transparent;
margin:0 0 10px;
color:#8D8D8D;
font-size:11px;
font-weight:bold;
text-transform:uppercase;
}
.post-info a {
display:inline-block;
color:#8D8D8D;
}
.post-info abbr {
border-bottom:none;
}
.author-info, .time-info, .comment-info, .label-info, .review-info {
margin-right:12px;
display:inline;
}
a.readmore {
display:inline-block;
margin:15px 0 0;
background-color:#ffffff;
border:1px solid #EE4B3D;
padding:0px 10px;
line-height:26px;
color:#EE4B3D;
font-size:11px;
font-weight:bold;
text-transform:uppercase;
}
a.readmore:hover  {
border:1px solid #333333;
}
/* Page Navigation */
#blog-pager {
	margin:0 0;
	clear:both !important;
	padding:0 0;
	font-size:12px;
	font-weight:normal;
}
a.home-link, #blog-pager-newer-link a, #blog-pager-older-link a {
	background-color:$(readmore.background.color);
	border: 1px solid $(readmore.border.color);
	padding:0px 12px;
	line-height:28px;
	color:$(readmore.color);
}
#blog-pager-newer-link a {
	float:left;
	display:block;
}
#blog-pager-older-link a {
	float:right;
	display:block;
}
a.home-link {
	display:inline-block;
}
#blog-pager-older-link a:hover, #blog-pager-newer-link a:hover, a.home-link:hover {
	border: 1px solid $(readmore.hover.color);
}

/* Page Navigation */
.pagenavi {
	clear:both;
	margin:-5px 0 10px;
	text-align:center;
	font-size:11px;
	font-weight:bold;
	text-transform:uppercase;
}
.pagenavi span,.pagenavi a {
	padding:6px 10px;
	margin-right:3px;
	display:inline-block;
	color:$(readmore.color);
	background-color:$(readmore.background.color);
	border: 1px solid $(readmore.border.color);
}
.pagenavi .current, .pagenavi .pages, .pagenavi a:hover {
	border: 1px solid $(readmore.hover.color);
}
.pagenavi .pages {
	display:none;
}

/* SIDEBAR WRAPPER */
#sidebar-wrapper {
	background:transparent;
	float:right;
	width:30%;
	max-width:300px;
	margin:0 auto;
}
.sidebar-container {
	padding:15px 0;
}
.sidebar h2, .panel h2 {
	font:$(sidebar.title.font);
	color:$(sidebar.title.text.color);
	margin:0 0 10px 0;
	padding:6px 0;
	border-bottom:2px solid #e5e5e5;
	text-transform:uppercase;
	position:relative;
}
.sidebar h2:after, .panel h2:after {
	content: " ";
	width:90px;
	height: 0px;
	position: absolute;
	left: 0;
	bottom: -2px;
	border-bottom:2px solid $(sidebar.title.border.color);
}
.sidebar .widget {
	margin:0 0 15px;
}
.sidebar ul, .sidebar ol {
	list-style-type:none;
	margin:0 0 0 0;
	padding:0 0 0 0;
}
.sidebar li {
	margin:5px 0;
	padding:0 0 0 0;
}


/* Recent Post */
.recent-post-title {
	background:#fff url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABYAAAAaCAYAAACzdqxAAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAABiwAAAYsB4dDSvAAAABl0RVh0U29mdHdhcmUAd3d3Lmlua3NjYXBlLm9yZ5vuPBoAAATySURBVEiJbZV9jFRnFYef887szrpi2qXazUp3mfe9Y20xIaHYhETj8iVGaKCBUC0tVoQoGvwgITRKiGCU+hGxwaCGRE0gUtLSFlCIQHddmsa0icSmJhuWzL13d9yATSMbTAu7Ozv3+MeeC8PH/DVvTs7z/s457z0/UVUBFCCO450i8iOmf4NZli2sVCrvASRJ8mngNeAeYBx4LITQBzA0NPSRYrF4RkQWWO7PRVWxxGeBn1pgSER6vffvAlSr1XnOuT6gA5hwzq0ql8unAQYHB2e0tbX9FfiM5T4fQthaNOjWJmi1paVlcXd397sAaZrOdc69ZtBJYE0OvXz5cnupVPpLE3R/CGErgEvTdAuwF0BEkizLFnV3d18ypZ9S1T5gJlDPsuyJEMJJgNHR0Q9dv379zyLSa7kHQgjftguQOI4zQIARK38EYGRk5OFGozEA3A9MiciT3vujdmHJOXcCWGacP4YQNjbN6jvOoKOFQmFRDk2S5MFGo9Fn0Iaqrs+hg4ODrc65V3Koqh4KIWzKoUmSfFNEfuVU9ZKqLpo9e3ZqaiKgH+gCMhHZEEXREYDz58+3lEqll4DlpvRIFEUbgMzmsQnYD9Sdc25xFEVVK9875/4GzDIFm7z3hwAGBgaKHR0dR0RkpUGP1mq19UDDyv+qqh7IO9D83HqA14HZ0xXq5iiKDhikEMfxYRF5wgZ1/MqVK2vnz59ft9yngIOAs7Z+TlSVarX6QKFQOKeqwRK3eO/3G9QlSXIIWGfnk+Pj46vnzJkzaUq/JCJ/AgqqegnojaKoKrVa7eP1en0A+IQlbg0hPJ9D0zT9g6o+Y4M6raqrKpXKhCldAxwBisB/RGSh934IwNXr9f4cqqrbm6CSJMmBHAr0FQqFx3NotVpdBbxg0PeyLFuSQy9evDirCHzSyt8RQvhFE/Q3wEa78Fx7e/vKrq6ucVO6wjn3ItAiIv9V1SWVSmXQHkBXsVjsLxpol/d+j/0njuN9IrLZjm/MmDFjRWdn5zWA4eHhLwAvA63AmIgs9d7/CyBN005V7Qe8U9U9IYTdOTRJkr0issWUvlmv15d3dnZ+YLElWZYdA0rAVWBZuVx+21rzMfv8HwKyG8/NEn8GbLfjP4ClIYSrprQ3y7JTQDvwP+fcsnK5/BbAhQsX7mttbe0H5uZtzVtBHMc/FpHtFvhnoVBY1tPTc9Uu/Cxw0qDvq+oXc2itVusolUpnVXWuoXZ77/c4S/yhiOywwDsTExOf7+npGTOlC4BTwIeBayKyIoqiv1vePVNTU6dVdZ7lPhdC2JVP/weq+hML3O4ajwJnmXaN66r6WBRF/XCna6jqL6Mo2pZ3QOI4zpt8u2s8Yq5xLzAhIiu992fgTtcQkX3e++82tXVn3uO7ucZZg04Cq3PoXVzjd83QJEm+LyK7iiKSNBqNW1zDlM4E6iKy1nt/CqZdY3Jy8oZrAL8PIXwrh6Zpug3YA0wUgcWVSmXUBvWQQT8KTAFf9t6fsAtLzrljwGIr/6D3/uvcXPDfA/Ivd7h5bT4IDDC94Bsiss57/6L1tLWtre1Vbi74F0IIT3NzwW9R1V/nwlW115maW1wD+EoOvYtrHA0hrM+hcRx/Q1X3WaxmxvFvNzw8XHbO9TPtGpmqfi2EcBjudA0ROT42NrYOc400TTeKyG8x12g0GovK5fIwwP8B3DF1BfTENDEAAAAASUVORK5CYII=) repeat-x;
	margin:0 0 15px;
	padding:0;
	position:relative;
}

.recent-post-title h2 {
	font:$(recentpost.title.font);
	height:26px;
	line-height:26px;
	margin:0 0;
	padding:0 10px;
	background:$(recentpost.title.background.color);
	color:$(recentpost.title.text.color);
	display:inline-block;
	border-right:5px solid #fff;
}
.recent-post-title h2 a {
	color:$(recentpost.title.text.color);
}
.recent-post-title h2 a:after {
    content: "\f18e"; 
    font-family: FontAwesome;
    font-style: normal;
    font-weight: normal;
    text-decoration: inherit;
    padding-left:6px;
}
.recent-post-one-thumb {
	float:left;
	width:50%;
	margin:0 0;
}
.recent-post-one-thumb .widget {
	padding:0 15px 15px 0;
}
.recent-post-one-thumb .widget-content {
	background:$(recentpost.background.color);
	border:1px solid $(recentpost.border.color);
	padding:15px;
}
.recent-post-one-thumb ul {
	list-style-type:none;
	margin:0 0 0 0;
	padding:0 0 0 0;
}


/* Recent Post */
ul.rp_thumbs {
	margin:0 0 0 0;
}

ul.rp_thumbs li {
	font-size:12px;
	min-height:68px;
	margin:0 0 8px;
	padding:0 0 8px;
	border-bottom:1px dotted #e5e5e5;
}
ul.rp_thumbs .rp_thumb {
	position:relative;
	background:#fbfbfb;
	margin:3px 0 10px 0;
	width:100%;
	height:0;
	padding-bottom:46%;
	overflow:hidden;
}
ul.rp_thumbs .rp_thumb img {
	height:auto;
	width:100%;
}


ul.rp_thumbs2 {
	font-size:13px;
}
ul.rp_thumbs2 li {
	padding:0 0;
	min-height:66px;
	font-size:11px;
	margin: 0 0 8px;
	padding: 0 0 8px;
	border-bottom:1px dotted #e5e5e5;
}
ul.rp_thumbs2 .rp_thumb2 {
	background:#fbfbfb;
	float:left;
	margin:3px 8px 0 0;
	height:60px;
	width:60px;
}
ul.rp_thumbs2 .rp_thumb2 img {
	height:60px;
	width:60px;
}

span.rp_title {
font:normal normal 18px Open Sans Condensed, Helvetica, Arial, sans-serif;
display:block;
margin:0 0 5px;
line-height:1.4em;
}
span.rp_title2 {
font-size:14px;
}
span.rp_summary {
display:block;
margin:6px 0 0;
}
span.rp_meta {
background:transparent;
display:block;
font-size:11px;
font-weight:bold;
color:#8D8D8D;
text-transform:uppercase;
}
span.rp_meta a {
color:#8D8D8D !important;
display:inline-block;
}
span.rp_meta_date, span.rp_meta_comment, span.rp_meta_more  {
display:inline-block;
margin-right:8px;
}
span.rp_meta_date:before {
content: "\f073";
font-family: FontAwesome;
font-style: normal;
font-weight: normal;
text-decoration: inherit;
padding-right:4px;
}
span.rp_meta_comment:before  {
content: "\f086";
font-family: FontAwesome;
font-style: normal;
font-weight: normal;
text-decoration: inherit;
padding-right:4px;
}
span.rp_meta_more:before {
content: "\f0a9";
font-family: FontAwesome;
font-style: normal;
font-weight: normal;
text-decoration: inherit;
padding-right:4px;
}
ul.rp_thumbs2 li a:hover, ul.rp_thumbs li a:hover {
color:#0072C6;
}

/* BOTTOMBAR */
#bottombar {
	background:$(bottombar.background.color);
	overflow:hidden;
	margin:0 auto;
	padding:15px;
	color:$(bottombar.color);
}
#bottombar .left {
	float:left;
	width:34%;
}
#bottombar .center {
	float:left;
	width:34%;
}
#bottombar .right {
	float:right;
	width:32%;
}
#bottombar .left .widget, #bottombar .center .widget {
	margin:0 15px 15px 0;
}
#bottombar .right .widget {
	margin:0 0 15px 0;
}
#bottombar h2 {
	font:$(bottombar.title.font);
	margin:0 0 10px 0;
	padding:6px 0;
	border-bottom:2px solid #555;
	text-transform:uppercase;
	position:relative;
	color:$(bottombar.title.text.color);
}
#bottombar h2:after {
	content:" ";
	width:90px;
	height:0px;
	position:absolute;
	left:0;
	bottom:-2px;
	border-bottom:2px solid $(bottombar.title.border.color);
}
#bottombar ul, #bottombar ol {
	list-style-type:none;
	margin:0 0 0 0;
	padding:0 0 0 0;
}
#bottombar li {
	margin:5px 0;
	padding:0 0 0 0;
}
#bottombar ul li:before {
	color:$(bottombar.title.text.color) !important;
}
#bottombar a {
	color:$(bottombar.link.color);
}
#bottombar a:hover {
	color:$(bottombar.hover.color);
}

/* FOOTER */
#footer-wrapper {
	background:$(footer.background.color);
	margin:0 auto;
	padding:20px 5px;
	overflow:hidden;
	color:$(footer.color);
	font-size:11px;
}
.footer-left {
	float:left;
	margin:10px;
}
.footer-right {
	float:right;
	margin:10px;
}
#footer-wrapper a {
	color:$(footer.link.color);
}
#footer-wrapper a:hover {
	color:$(footer.hover.color);
}

/* CUSTOM WIDGET */

.widget ul {
	line-height:1.4em;
}

/* Tab Menu */
.set, .panel {
	margin: 0 0;
}
.tabs .panel {
	padding:0 0;
}
.tabs-menu {
	border-bottom:3px solid $(sidebar.title.border.color);
	padding: 0 0;
	margin:0 0;
}
.tabs-menu li {
	font:$(sidebar.title.font);
	display: inline-block;
	*display: inline;
	zoom: 1;
	margin: 0 3px 0 0;
	padding:10px;
	background:#fff;
	border:1px solid #e5e5e5;
	border-bottom:none !important;
	color:$(sidebar.title.text.color);
	cursor:pointer;
	position:relative;
}
.tabs-menu .active-tab {
	background:$(sidebar.title.border.color);
	border:1px solid #E73138;
	border-bottom:none !important;
	color:#fff;
}
.tabs-content {
	padding:10px 0;
}
.tabs-content .widget li {
	float:none !important;
	margin:5px 0;
}
.tabs-content .widget ul {
	overflow:visible;
}


/* label */
.label-size-1,.label-size-2,.label-size-3,.label-size-4,.label-size-5 {
	font-size:100%;
	filter:alpha(100);
	opacity:10
}
.cloud-label-widget-content{
	text-align:left
}
.label-size {
	background:$(label.background.color);
	display:block;
	float:left;
	margin:0 3px 3px 0;
	color:$(label.color);
	font-size:11px;
	text-transform:uppercase;
}
.label-size a,.label-size span{
	display:inline-block;
	color:$(label.color) !important;
	padding:6px 8px;
	font-weight:bold;
}
.label-size:hover {
	background:$(label.hover.color);
}

.label-count {
	white-space:nowrap;
	padding-right:3px;
	margin-left:-3px;
	background:$(label.count.color);
	color:#fff !important;
}
.label-size {
	line-height:1.2
}


/* Custom CSS for Blogger Popular Post Widget */
.PopularPosts ul,
.PopularPosts li,
.PopularPosts li img,
.PopularPosts li a,
.PopularPosts li a img {
margin:0 0;
padding:0 0;
list-style:none;
border:none;
background:none;
outline:none;
}
.PopularPosts ul {
margin:.5em 0;
list-style:none;
color:black;
counter-reset:num;
}
.PopularPosts ul li img {
display:block;
margin:0 .5em 0 0;
width:50px;
height:50px;
float:left;
}
.PopularPosts ul li {
background-color:#eee;
margin:0 0 0.4em 0 !important;
padding:.5em 1.5em .5em .5em !important;
counter-increment:num;
position:relative;
}
.PopularPosts ul li:before,
.PopularPosts ul li .item-title a, .PopularPosts ul li a {
font-weight:bold;
color:#000 !important;
text-decoration:none;
}
.PopularPosts ul li:before {
content:counter(num) !important;
font-family:arial, sans-serif !important;
font-size:12px;
font-weight:bold !important;
display:block;
position:absolute;
top:-3px;
right:-3px;
border-radius:12px;
background-color:#333;
color:#fff !important;
width:24px;
height:24px;
line-height:24px;
text-align:center;
padding-right:0px !important;
box-shadow: -1px 1px 0px #fff;
}
/* Set color and level */
.PopularPosts ul li:nth-child(1) {background-color:#A51A5D;
}
.PopularPosts ul li:nth-child(2) {background-color:#F53477;
}
.PopularPosts ul li:nth-child(3) {background-color:#FD7FAA;
}
.PopularPosts ul li:nth-child(4) {background-color:#FF9201;
}
.PopularPosts ul li:nth-child(5) {background-color:#FDCB01;
}
.PopularPosts ul li:nth-child(6) {background-color:#DEDB00;
}
.PopularPosts ul li:nth-child(7) {background-color:#89C237;
}
.PopularPosts ul li:nth-child(8) {background-color:#44CCF2;
}
.PopularPosts ul li:nth-child(9) {background-color:#01ACE2;
}
.PopularPosts ul li:nth-child(10) {background-color:#94368E;
}
.PopularPosts .item-thumbnail {
margin:0 0 0 0;
}
.PopularPosts .item-snippet {
font-size:11px;
}
.profile-img{
display:inline;
opaciry:10;
margin:0 6px 3px 0;
}
/* back to top */
#back-to-top {
background:#FF4F4F;
color:#ffffff;
padding:8px 10px;
font-size:24px;
}
.back-to-top {
position:fixed !important;
position:absolute;
bottom:20px;
right:20px;
z-index:999;
}
/* ==== Related Post Widget Start ==== */
.related-post {
margin:15px 0 0;
border-top:1px solid #f0f0f0;
padding:15px 0 0;
}
.related-post h4 {
font-size:14px;
margin:0 0 .5em;
text-transform:uppercase;
}
.related-post-style-2 {
margin:0 0 0 0 !important;
padding:0 0 0 0 !important;
list-style:none;
}
.related-post-style-2 li {
margin:0 0 0 0;
padding:0 0 0 0;
}
.related-post-style-2 li {
padding:5px 0 !important;
border-top:1px solid #eee;
overflow:hidden;
}
.related-post-style-2 li:first-child {border-top:none}
.related-post-style-2 .related-post-item-thumbnail {
width:60px;
height:60px;
max-width:none;
max-height:none;
background-color:transparent;
border:none;
padding:0;
float:left;
margin:2px 8px 0 0;
}
.related-post-style-2 .related-post-item-title {
font:normal normal 18px Open Sans Condensed, Helvetica, Arial, sans-serif;
}
.related-post-style-2 .related-post-item-summary {
display:block;
overflow:hidden;
}
.related-post-style-2 .related-post-item-more {}
/* share buttons */
.share-buttons-box {
height: 67px;
background: url(http://3.bp.blogspot.com/-moj4-jk-UB0/U1qCkCPaGQI/AAAAAAAADTY/tixmak8NHV8/s1600/share.png) no-repeat 330px 10px;
margin:20px 0 15px;
overflow:hidden;
}
.share-buttons {
margin:0 0;
height:67px;
float:left;
}
.share-buttons .share {
float:left;
margin-right:10px;
display:inline-block;
}
/* error and search */
.status-msg-wrap {
font-size:120%;
font-weight:bold;
width:100%;
margin:0px auto;
}
.status-msg-body {
padding:20px 2%;
width:96%;
}
.status-msg-border {
border:1px solid #f0f0f0;
opacity:10;
width:auto;
}
.status-msg-bg {
background-color:#ffffff;
}
.status-msg-hidden {
padding:20px 2%;
}
.tabs-content .widget ul li:before, .sidebar ul li:before, #bottombar ul li:before {
content:"\f061";
font-family: FontAwesome;
font-style: normal;
font-weight: normal;
text-decoration: inherit;
padding-right:4px;
color:#666;
}
#ArchiveList ul li:before {
content:"" !important;
padding-right:0px !important;
}
/* facebook comments */
.fbbox-comments {
box-sizing: border-box;
-moz-box-sizing: border-box;
background:#fff;
border:1px solid #f0f0f0;
margin: 0 0 20px;
}
.fb-comments{width: 100% !important;}
.fb-comments iframe[style]{width: 100% !important;}
.fb-like-box{width: 100% !important;}
.fb-like-box iframe[style]{width: 100% !important;}
.fb-comments span{width: 100% !important;}
.fb-comments iframe span[style]{width: 100% !important;}
.fb-like-box span{width: 100% !important;}
.fb-like-box iframe span[style]{width: 100% !important;
}
.rich-snippet {
padding:10px;
margin:15px 0 0;
border:3px solid #eee;
font-size:12px;
}
.berlangganan-box {
background:#F8f8f8;
padding:15px;
border:1px solid #ededed;
margin:10px 0 20px;
text-align:center;
}
.quickedit{display:none;}
.berlangganan-box input.email-address[type="text"] {
width:60%;
padding:10px;
border:1px solid #ddd;
text-align:center;
border-radius: 4px;
outline:none;
}
.berlangganan-box input.submit-email[type="submit"] {
transition:all 0.5s;-moz-transition:all 0.5s;-webkit-transition:all 0.5s;
padding:10px 15px;
background:#07ACEC;
border-radius: 4px;
color:#fff;
border:none;
font-weight:bold;
border-bottom: 3px solid #0D9AD0;
outline:none;
}
.berlangganan-box input.submit-email[type="submit"]:hover {
background:#0D9AD0;
cursor:pointer;
}
.berlangganan-box input.email-address[type="text"]:focus {
box-shadow:0 0 2px #106FE4;
}
/* MEDIA QUERY */
@media only screen and (max-width:1066px){
	#wrapper {
		margin:0 auto;
	}
}
@media only screen and (max-width:768px){
	#wrapper {
		padding:0 12px;
	}
	#post-wrapper, #sidebar-wrapper, .nav {
		float:none;
		width:100%;
		max-width:100%
	}
    .active {
        display: block;
    }
	#search-form {
		width:100%;
		margin:0 0 0 0 !important;
	}
	.nav li ul:before { 
		display:none;
	}
    .nav > li {
        float: none;
		overflow:hidden;
    }
    .nav ul {
        display: block;
        width: 100%;
		float:none;
    }
	.nav-menu2 li ul {
		background:#eee;
		border:none;
		box-shadow:none;
	}
	.nav-menu2 li li ul {
		background:#f5f5f5;
	}
	.nav-menu2 li li a:hover {
		background:#ddd;
	}
    .nav > li.hover > ul , .nav li li.hover ul {
        position: static;
    }
	#search-form {
		width:100%;
		background:#444;
	}
	#search-form td.search-box {
		padding:0 10px !important;
	}
	#search-form td.search-button {
		padding:0 10px;
		width:1%;
	}
	#search-form input#search-box[type="text"] {
		margin:0 0 0 0;
	}
	#search-form input#search-button[type="submit"] {
		margin:0 0 0 0;
	}
	.post-body img {
		max-width:90%;
	}
	.img-thumbnail {
		margin:0 10px 0 0;
	}
	.recent-post-one-thumb .widget {
		padding:0 0 10px 0;
	}
	#recent-post-one-thumb-1 .widget, #recent-post-one-thumb-3 .widget, #recent-post-one-thumb-5 .widget {
		padding:0 5px 10px 0;
	}
	#recent-post-one-thumb-2 .widget, #recent-post-one-thumb-4 .widget, #recent-post-one-thumb-6 .widget {
		padding:0 0 10px 5px;
	}
	.sidebar-container, .post-container {
		padding:15px 0 0px;
	}
}

@media only screen and (max-width:640px){
	#wrapper {
		padding:0 10px;
	}
	#post-wrapper, #sidebar-wrapper, #bottombar .left, #bottombar .center, #bottombar .right {
		float:none;
		width:100%;
		max-width:100%
	}
	.header, .header-right {
		margin:10px 0;
	}
	.sidebar-container, .post-container{
		padding:10px 0 0px;
	}
	.largebanner .widget, #bottombar {
		padding:10px;
	}
	.post, .breadcrumbs {
		margin:0 0 10px;
		padding:10px;
	}
	.pagenavi {
		margin: 6px 0 10px;
	}
	.recent-post-one-thumb .widget-content {
		padding:10px;
	}
	#bottombar .left .widget, #bottombar .center .widget, #bottombar .right .widget, .sidebar .widget {
		margin:0 0 10px 0;
	}

}

@media only screen and (max-width:480px){
	#wrapper {
		padding:0 8px;
	}
	.header, .header-right, .recent-post-one-thumb {
		float:none;
		width:100%;
		max-width:100%
	}
	.header img {
		max-width:160px;
	}
	.largebanner .widget, #bottombar {
		padding:8px;
	}
	.post, .breadcrumbs {
		margin:0 0 8px;
		padding:8px;
	}
	.recent-post-one-thumb .widget-content {
		padding:8px;
	}
	h2.post-title, h1.post-title {
		font-size:16px;
	}
	.img-thumbnail, .img-thumbnail img {
		width:120px;
		height:90px;
	}
	.img-thumbnail {
		margin:0 8px 0 0;
	}
	#recent-post-one-thumb-1 .widget, #recent-post-one-thumb-3 .widget,	#recent-post-one-thumb-2 .widget, #recent-post-one-thumb-4 .widget, #recent-post-one-thumb-5 .widget, #recent-post-one-thumb-6 .widget {
		padding:0 0 8px 0;
	}
	.comments .comment-block, .comments .comments-content .inline-thread {
		padding:10px !important;
	}
	.comment .comment-thread.inline-thread .comment {
		margin: 0 0 0 0 !important;
	}
	.footer-left, .footer-right {
		float:none;
		text-align:center;
	}
}

@media screen and (max-width:320px){
	#wrapper {
		padding:0 6px;
	}
	.post, .breadcrumbs {
		padding:6px;
	}
	.recent-post-one-thumb .widget-content {
		padding:6px;
	}
	.img-thumbnail, .img-thumbnail img {
		width:100px;
		height:80px;
	}
}

]]></b:skin>

<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
<style type='text/css'>
.status-msg-body:after, .status-msg-hidden:after {
	content:&quot;404&quot;;
	font-size:120px;
	display:block;
	margin:20px 0;
	font-weight:bold;
	color:#E73037;
	text-shadow:6px 6px #ddd;
}
.recent-post-one-thumb, #blog-pager {
	display:none;
}
</style>
</b:if>

<b:if cond='data:blog.isMobile'>

<style type='text/css'>
.mobile #wrapper {
	float:none;
	width:auto;
	max-width:728px;
	padding:0 8px;
}
.mobile .widget {
	margin:0 0 0 0;
}
.mobile .navigation-menu, .mobile .header, .mobile #content-wrapper, .mobile #post-wrapper, .mobile #sidebar-wrapper, .mobile #footer-wrapper, .mobile .header-right {
	float:none;
	width:auto;
	max-width:728px;
	width:100%;
	padding:0 0 0 0;
	margin:0 0 0 0;
}
.mobile #content-wrapper {
	padding-top:5px !important;
}
.mobile .post-container, .mobile .sidebar-container, .mobile .header {
	padding:8px 0 !important;
}
.mobile .header-right {
	padding:0 0 8px !important;
}
.mobile .post-body, .mobile  #blog-pager, .mobile .header .description, .mobile-index-contents .post-body {
	font-size:13px;
}
.mobile .post-body {
	line-height:1.5;
}
.mobile .post-info {
	margin:0 0 0;
}
.post, .breadcrumbs {
	margin:0 0 8px;
	padding:8px;
}
.recent-post-one-thumb .widget-content {
	padding:8px;
}
.mobile .mobile-date-outer {
	background:#fff;
	border:1px solid #e5e5e5;
	margin:0 0 8px;
	padding:8px;
}
.mobile-index-title {
	margin-top:0px;
	margin-bottom:8px;
}	
.mobile h3.mobile-index-title, .mobile h3.mobile-post-title {
	font:normal bold 14px Arial, sans-serif;
	width:auto;
	max-width:728px;
}
.mobile span.rp_title {
	font:normal bold 14px Arial, sans-serif;
	text-transform:none;
}
.mobile .mobile-index-thumbnail {
	width:48px;
	height:48px;
	float: left;
	margin:0 8px 0 0 !important;
}
.mobile .mobile-index-thumbnail img {
	width:48px !important;
	height:48px !important;
}
.mobile img, .mobile iframe {
	max-width:100%;
}
.mobile .header img {
	width:auto;
	max-width:140px;
}
.mobile .recent-post-one-thumb, #bottombar .left, #bottombar .center, #bottombar .right {
	float:none !important;
	width:100% !important;
}
.mobile ul.rp_thumbs li, .mobile ul.rp_thumbs2 li {
	min-height:48px !important;
	padding:0 0 8px !important;
}
.mobile ul.rp_thumbs .rp_thumb, .mobile ul.rp_thumbs2 .rp_thumb2 {
	background:#fbfbfb;
	float:left;
	margin:3px 8px 0 0 !important;
	height:48px !important;
	width:48px !important;
	padding-bottom:0px !important;
}
.mobile ul.rp_thumbs .rp_thumb img, .mobile ul.rp_thumbs2 .rp_thumb2 img {
	height:48px !important;
	width:48px !important;
}
span.rp_summary {
	display:none;
}
.mobile #recent-post-one-thumb-1 .widget, .mobile #recent-post-one-thumb-3 .widget,	.mobile #recent-post-one-thumb-2 .widget, .mobile #recent-post-one-thumb-4 .widget, .mobile #recent-post-one-thumb-5 .widget, .mobile #recent-post-one-thumb-6 .widget {
	padding:0 0 8px 0 !important;
}
.mobile #bottombar, .largebanner .widget {
	padding:8px !important;
}
.mobile #bottombar .left .widget, .mobile #bottombar .center .widget, .mobile #bottombar .right .widget {
	margin:0 0 8px 0 !important;
}
.mobile #blog-pager {
	margin:0 0 0 0 !important;
	padding:0 !important;
}
.mobile .blog-pager-older-link, .mobile .home-link, .mobile .blog-pager-newer-link {
	width:auto;
}
.mobile a.home-link {
	line-height:20px !important;
}
.mobile .mobile-desktop-link {
	display:none;
}
.mobile .sidebar .widget {
	padding: 0 0 8px !important;
}
.mobile .comment-form {
	max-width:728px;
}
.mobile #comment-editor {
	display:block !important;
}
.mobile .comments .avatar-image-container {
	display:none;
}
.mobile .comments .comment-block,.mobile .comments .comments-content .comment-replies,.mobile .comments .comment-replybox-single {
	margin-left:10px !important;
}
.mobile .PopularPosts .item-thumbnail {
    margin: 0px 6px 0px 0px;
    display: inline;
    float: left;
}
.mobile .PopularPosts .item-thumbnail a img {
    display: block;
    margin: 0px;
    padding: 0px;
    height: 48px;
    width: 48px;
}
.mobile #related-posts-mobile {
	text-align:left;
	margin:10px 0;
	padding:0;
}
.mobile #related-posts-mobile  ol {
	list-style-type:none;
	margin:0 0 0 0 !important;
}
.mobile #related-posts-mobile  ol li {
	padding:3px;
	border-bottom:1px dotted #ddd;
}
.mobile #related-posts-mobile  ol li:last-child {
	border-bottom:none !important
}
.mobile #related-posts-mobile  h3{
	color:#333;
	font-weight:bold;
	padding:0 0 6px 0;
	margin:0;
	font-size:15px;
}

#share-buttons-mobile {
	margin:15px 0 5px;
	padding:0;
}
#share-buttons-mobile p{
	float:left;
	display:block;
	padding:3px 0px !important;
	margin:0 3px 3px 0;
}
#share-buttons-mobile a{
	position:relative;
	float:left;
	display:block;
	color:#fafafa;
	padding:3px 8px;
	margin:0 3px 3px;
}
#share-buttons-mobile a:hover{
	text-decoration:underline;
}

/* NAVIGASI */
.mobile #mobile-nav {
	background:#117AC9;
	font-size:13px;
	font-weight:bold;
	color:#fff;
	text-align:center;
	width:auto;
	overflow:hidden;
	margin:0;
	padding:10px 6px;
}
.mobile #mobile-nav span a{
	color:#fff;
	padding:3px 0;
	margin:0
}
.mobile #mobile-nav span a:hover{
	text-decoration:underline;
}

</style>
<script>
//<![CDATA[
var relatedTitles=new Array();var relatedTitlesNum=0;var relatedUrls=new Array();function related_results_labels(json){for(var i=0;i<json.feed.entry.length;i++){var entry=json.feed.entry[i];relatedTitles[relatedTitlesNum]=entry.title.$t;for(var k=0;k<entry.link.length;k++){if(entry.link[k].rel=='alternate'){relatedUrls[relatedTitlesNum]=entry.link[k].href;relatedTitlesNum++;break;}}}}
function removeRelatedDuplicates(){var tmp=new Array(0);var tmp2=new Array(0);for(var i=0;i<relatedUrls.length;i++){if(!contains(tmp,relatedUrls[i])){tmp.length+=1;tmp[tmp.length-1]=relatedUrls[i];tmp2.length+=1;tmp2[tmp2.length-1]=relatedTitles[i];}}
relatedTitles=tmp2;relatedUrls=tmp;} function contains(a,e){for(var j=0;j<a.length;j++)if(a[j]==e)return true;return false;}
function printRelatedLabels(){var r=Math.floor((relatedTitles.length-1)*Math.random());var i=0;document.write('<ol>');while(i<relatedTitles.length&&i<20){document.write('<li><a href="'+relatedUrls[r]+'">'+relatedTitles[r]+'</a></li>');if(r<relatedTitles.length-1){r++;}else{r=0;}
i++;}
document.write('</ol>');document.write();}//]]>
</script>
</b:if>

<b:if cond='data:blog.pageType != &quot;index&quot;'>
<style type='text/css'>
/* COMMENT */

.comment-form {
	overflow:hidden;
}
.comments h3 {
	line-height:normal;
	text-transform:uppercase;
	color:#333;
	font-weight:bold;
	margin:0 0 20px 0;
	font-size:14px;
	padding:0 0 0 0;
}
h4#comment-post-message {
	display:none;
	margin:0 0 0 0;
}
.comments{
	clear:both;
	margin-top:10px;
	margin-bottom:0
}
.comments .comments-content{
	font-size:13px;
	margin-bottom:8px
}
.comments .comments-content .comment-thread ol{
	text-align:left;
	margin:13px 0;
	padding:0
}

.comments .avatar-image-container {
	background:#fff;
	border:1px solid #e5e5e5;
	overflow:hidden;
	padding:6px;
}
.comments .comment-block{
	position:relative;
	background:#fff;
	padding:15px;
	margin-left:60px;
	border-left:3px solid #e5e5e5;
	border-top:1px solid #e5e5e5;
	border-right:1px solid #e5e5e5;
	border-bottom:1px solid #e5e5e5;
}
.comments .comment-block:before {
	content:&quot;&quot;;
	width:0px;
	height:0px;
	position:absolute;
	right:100%;
	top:14px;
	border-width:10px;
	border-style:solid;
	border-color:transparent #e5e5e5 transparent transparent;
	display:block;
}
.comments .comments-content .comment-replies{
	margin:8px 0;
	margin-left:60px
}
.comments .comments-content .comment-thread:empty{
	display:none
}
.comments .comment-replybox-single {
	background:#fff;
	box-shadow:inset 1px 1px 0 #e5e5e5, inset -1px -1px 0 #e5e5e5;
	padding:0;
	margin:8px 0;
	margin-left:60px
}
.comments .comment-replybox-thread {
	background:#fff;
	box-shadow:inset 1px 1px 0 #e5e5e5, inset -1px -1px 0 #e5e5e5;
	margin:8px 0 0 0;
	padding:0;
}


.comments .comments-content .comment{
	margin-bottom:6px;
	padding:0
}
.comments .comments-content .comment:first-child {
	padding:0;
	margin:0
}
.comments .comments-content .comment:last-child {
	padding:0;
	margin:0
}
.comments .comment-thread.inline-thread .comment, .comments .comment-thread.inline-thread .comment:last-child {
	margin:0px 0px 5px 30%
}
.comment .comment-thread.inline-thread .comment:nth-child(6) {
	margin:0px 0px 5px 25%;
}
.comment .comment-thread.inline-thread .comment:nth-child(5) {
	margin:0px 0px 5px 20%;
}
.comment .comment-thread.inline-thread .comment:nth-child(4) {
	margin:0px 0px 5px 15%;
}
.comment .comment-thread.inline-thread .comment:nth-child(3) {
	margin:0px 0px 5px 10%;
}
.comment .comment-thread.inline-thread .comment:nth-child(2) {
	margin:0px 0px 5px 5%;
}
.comment .comment-thread.inline-thread .comment:nth-child(1) {
	margin:0px 0px 5px 0;
}

.comments .comments-content .comment-thread{
	margin:0;
	padding:0
}
.comments .comments-content .inline-thread{
	background:#fff;
	border:1px solid #e5e5e5;
	padding:15px;
	margin:0
}
.comments .comments-content .icon.blog-author {
	display:inline;
}
.comments .comments-content .icon.blog-author:after {
	content:&quot;Admin&quot;;
	background:#E73037;
	color:#fff;
	font-size:11px;
	padding:2px 5px;
	border-radius:3px;
}
.comment-header {
	text-transform:uppercase;
	font-size:12px;
}
.comments .comments-content .datetime {
	margin-left: 6px;
}
.comments .comments-content .datetime a {
	color:#888;
}

.comments .comment .comment-actions a {
	display:inline-block;
	color:#333;
	font-weight:bold;
	font-size:10px;
	line-height:15px;
	margin:4px 8px 0 0;
}
.comments .continue a {
	color:#333;
	display:inline-block;
	font-size:10px;
}
.comments .comment .comment-actions a:hover, .comments .continue a:hover{
	text-decoration:underline;
}
.pesan-komentar p {
	background:#666;
	position:relative;
	color:#fff;
	padding:10px 15px;
	margin:8px;
}
.pesan-komentar p {
	line-height:normal;
	margin:0 0;
}
.pesan-komentar p:before {
	content:&quot;&quot;;
	width:0px;
	height:0px;
	position:absolute;
	top:100%;
	left:30px;
	border-width:10px;
	border-style:solid;
	border-color:#666 transparent transparent transparent;
	display:block;
}
.fb-comments{width: 100% !important;}
.fb-comments iframe[style]{width: 100% !important;}
.fb-like-box{width: 100% !important;}
.fb-like-box iframe[style]{width: 100% !important;}
.fb-comments span{width: 100% !important;}
.fb-comments iframe span[style]{width: 100% !important;}
.fb-like-box span{width: 100% !important;}
.fb-like-box iframe span[style]{width: 100% !important;}
.fotleft{float:left}
.fotright{float:right;text-align:right;}

</style>
</b:if>


<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'> 
<script type='text/javascript'>
//<![CDATA[
function labelthumbs(json) {
    for (var i = 0; i < numposts; i++) {
        var entry = json.feed.entry[i];
        var posttitle = entry.title.$t;
        var posturl;
        if (i == json.feed.entry.length) break;
        for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'replies' && entry.link[k].type == 'text/html') {
                var commenttext = entry.link[k].title;
                var commenturl = entry.link[k].href;
            }
            if (entry.link[k].rel == 'alternate') {
                posturl = entry.link[k].href;
                break;
            }
        }
        var thumburl;	
        try {
            thumburl = entry.media$thumbnail.url;
			thumburl = thumburl.replace("/s72-c/","/w"+thumb_width+"-h"+thumb_height+"-c/");
        } catch (error) {
            s = entry.content.$t;
            a = s.indexOf("<img");
            b = s.indexOf("src=\"", a);
            c = s.indexOf("\"", b + 5);
            d = s.substr(b + 5, c - b - 5);
            if ((a != -1) && (b != -1) && (c != -1) && (d != "")) {
                thumburl = d;
            } else thumburl = no_thumb;
        }
        var postdate = entry.published.$t;
        var cdyear = postdate.substring(0, 4);
        var cdmonth = postdate.substring(5, 7);
        var cdday = postdate.substring(8, 10);
		document.write('<ul class="rp_thumbs">');
        document.write('<li>');
        if (showpostthumbnails == true)
            document.write('<a href="' + posturl + '"><div class="rp_thumb"><span class="rollover"></span><img width="' + thumb_width + '" height="' + thumb_height + '" alt="' + posttitle + '" src="' + thumburl + '"/></div></a>');
        document.write('<span class="rp_title"><a href="' + posturl + '" target ="_top">' + posttitle + '</a></span>');
        var towrite = '';
        document.write('<span class="rp_meta">');
        if (showpostdate == true) {
            towrite = towrite + '<span class="rp_meta_date">' + cdday + '/' + cdmonth + '/' + cdyear + '</span>';
        }
        if (showcommentnum == true) {
            if (commenttext == '1 Comments') commenttext = '1 Comment';
            if (commenttext == '0 Comments') commenttext = 'No Comments';
            commenttext = '<span class="rp_meta_comment"><a href="' + commenturl + '" target ="_top">' + commenttext + '</a></span>';
            towrite = towrite + commenttext;
        }
        if (displaymore == true) {
            towrite = towrite + '<span class="rp_meta_more"><a href="' + posturl + '" class="url" target ="_top">Read More...</a></span>';
        }
        document.write(towrite);
		document.write('</span>');
		document.write('<span class="rp_summary">');
        if ("content" in entry) {
            var postcontent = entry.content.$t;
        } else
        if ("summary" in entry) {
            var postcontent = entry.summary.$t;
        } else var postcontent = "";
        var re = /<\S[^>]*>/g;
        postcontent = postcontent.replace(re, "");
        if (showpostsummary == true) {
            if (postcontent.length < numchars) {
                document.write('');
                document.write(postcontent);
                document.write('');
            } else {
                document.write('');
                postcontent = postcontent.substring(0, numchars);
                var quoteEnd = postcontent.lastIndexOf(" ");
                postcontent = postcontent.substring(0, quoteEnd);
                document.write(postcontent + '...');
                document.write('');
            }
        }
		document.write('</span>');
        document.write('</li>');
		document.write('</ul>');	
    }
    document.write('<ul class="rp_thumbs2">');
    for (var i = 1; i < numposts2; i++) {
        var entry = json.feed.entry[i];
        var posttitle = entry.title.$t;
        var posturl;
        if (i == json.feed.entry.length) break;
        for (var k = 1; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'replies' && entry.link[k].type == 'text/html') {
                var commenttext = entry.link[k].title;
                var commenturl = entry.link[k].href;
            }
            if (entry.link[k].rel == 'alternate') {
                posturl = entry.link[k].href;
                break;
            }
        }
        var thumburl2;	
        try {
            thumburl2 = entry.media$thumbnail.url.replace("/s72-c/","/w"+thumb_width2+"-h"+thumb_height2+"-c/");
        } catch (error) {
            s = entry.content.$t;
            a = s.indexOf("<img");
            b = s.indexOf("src=\"", a);
            c = s.indexOf("\"", b + 5);
            d = s.substr(b + 5, c - b - 5);
            if ((a != -1) && (b != -1) && (c != -1) && (d != "")) {
                thumburl2 = d;
            } else thumburl2 = no_thumb2;
        }
        var postdate = entry.published.$t;
        var cdyear = postdate.substring(0, 4);
        var cdmonth = postdate.substring(5, 7);
        var cdday = postdate.substring(8, 10);
		if (showpostthumbnails2 == true)
            document.write('<a href="' + posturl + '"><div class="rp_thumb2"><img width="' + thumb_width2 + '" height="' + thumb_height2 + '" alt="' + posttitle + '" src="' + thumburl2 + '"/></div></a>');
		document.write('<li>');
		document.write('<span class="rp_title rp_title2"><a href="' + posturl + '" target ="_top">' + posttitle + '</a></span>');
        var towrite = '';
        document.write('<span class="rp_meta rp_meta2">');
        if (showpostdate2 == true) {
            towrite = towrite + '<span class="rp_meta_date rp_meta_date2">' + cdday + '/' + cdmonth + '/' + cdyear + '</span>';
        }
        if (showcommentnum2 == true) {
            if (commenttext == '1 Comments') commenttext = '1 Comment';
            if (commenttext == '0 Comments') commenttext = 'No Comments';
            commenttext = '<span class="rp_meta_comment rp_meta_comment2"><a href="' + commenturl + '" target ="_top">' + commenttext + '</a></span>';
            towrite = towrite + commenttext;
        }
        if (displaymore2 == true) {
            towrite = towrite + '<span class="rp_meta_more rp_meta_more2"><a href="' + posturl + '" class="url" target ="_top">Read More...</a></span>';
        }
        document.write(towrite);
		document.write('</span>');
		document.write('</li>');
    }
    document.write("</ul>")
}
//]]>
</script>

<script type='text/javascript'>
var numposts = 1;
var numposts2 = 4;
var showpostthumbnails = true;
var showpostthumbnails2 = true;
var displaymore = true;
var displaymore2 = false;
var showcommentnum = true;
var showcommentnum2 = true;
var showpostdate = true;
var showpostdate2 = true;
var showpostsummary = true;
var numchars = 100;
var thumb_width = 300;
var thumb_height = 140;
var thumb_width2 = 60;
var thumb_height2 = 60;
var no_thumb = &#39;http://1.bp.blogspot.com/-7vDs5hMaDho/U268E2ecF4I/AAAAAAAADY8/RBHVTTuJrxc/w300-h140-c/no-image.png&#39;
var no_thumb2 = &#39;http://3.bp.blogspot.com/-ltyYh4ysBHI/U04MKlHc6pI/AAAAAAAADQo/PFxXaGZu9PQ/s60-c/no-image.png&#39;
</script>

<script type='text/javascript'>
//<![CDATA[
function bp_thumbnail_resize(image_url,post_title)
{
var image_width=200;
var image_height=150;
image_tag='<img width="'+image_width+'" height="'+image_height+'" src="'+image_url.replace('/s72-c/','/w'+image_width+'-h'+image_height+'-c/')+'" alt="'+post_title.replace(/"/g,"")+'" title="'+post_title.replace(/"/g,"")+'"/>';
if(post_title!="") return image_tag; else return ""; 
}
//]]>
</script>

</b:if>
</b:if>
<script src='http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js'/>

<script type='text/javascript'>
$(function() {
$(&quot;.set-1&quot;).mtabs();                                
});
</script>

<b:include data='blog' name='google-analytics'/>
</head>

  <body expr:class='&quot;loading&quot; + data:blog.mobileClass'>
<div id='fb-root'/>
<script>
//<![CDATA[
window.fbAsyncInit = function() {
FB.init({
appId : 'YOUR_APPLICATION_ID',
status : true, // check login status
cookie : true, // enable cookies to allow the server to access the session
xfbml : true // parse XFBML
});
};
(function() {
var e = document.createElement('script');
e.src = document.location.protocol + '//connect.facebook.net/en_US/all.js';
e.async = true;
document.getElementById('fb-root').appendChild(e);
}());
//]]>
</script> 

  <!-- navbar menu start -->
  <b:section class='navbar' id='navbar' maxwidgets='1' showaddelement='no'>
    <b:widget id='Navbar1' locked='true' title='Navbar' type='Navbar'>
      <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/plusone.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
        gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
          if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
            gapi.iframes.getContext().openChild({
                url: &#39;https://www.blogger.com/navbar.g?targetBlogID\0751323262214572446451\46blogName\75Evo+Magz+v2.5\46publishMode\75PUBLISH_MODE_BLOGSPOT\46navbarType\75LIGHT\46layoutType\75LAYOUTS\46searchRoot\75http://evomagzv25.blogspot.com/search\46blogLocale\75in\46v\0752\46homepageUrl\75http://evomagzv25.blogspot.com/\46vt\75-4839673752360134507&#39;,
                where: document.getElementById(&quot;navbar-iframe-container&quot;),
                id: &quot;navbar-iframe&quot;
            });
          }
        });
      &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
    </b:widget>
  </b:section>
  <!-- navbar menu end -->

  <!-- wrapper start -->
  <div id='wrapper'>
  
  <b:if cond='data:blog.isMobile'>
  <b:else/>
  
  <div id='nav-wrap'>
	    <nav class='menu'>
		  <!-- primary navigation menu start -->
	      <ul class='nav-menu'>
			  <li><a href='#'>About</a></li>
			  <li><a href='#'>Contact Us</a></li>
			  <li><a href='#'>Privacy Policy</a></li>
			  <li><a href='#'>Disclaimer</a></li>
	      </ul>
		  <!-- primary navigation menu end -->  
		  
		  <!-- social media button start -->
		  <ul class='nav-social'>
			  <li><a class='fcb' href='https://www.facebook.com/evotemplatesnet' rel='nofollow'><i class='fa fa-facebook-square fa-2x'/></a>
			  </li>  
			  <li><a class='gpl' href='https://plus.google.com/+SugengRiyadi' rel='nofollow'><i class='fa fa-google-plus-square fa-2x'/></a>
			  </li>
			  <li><a class='twt' href='https://twitter.com/blogmassugeng' rel='nofollow'><i class='fa fa-twitter-square fa-2x'/></a> 
			  </li>
			  <li><a class='ytb' href='https://www.youtube.com' rel='nofollow'><i class='fa fa-youtube fa-2x'/></a> 
			  </li>
		  </ul>
		  <!-- social media button end -->
		  
		</nav>
		<div class='clear'/>
  </div>
  </b:if>
  
  <!-- header wrapper start -->
  <header id='header-wrapper'>  
  <b:section class='header' id='header' maxwidgets='1' showaddelement='no'>
      <b:widget id='Header1' locked='true' title='Evo Magz v2.5 (Header)' type='Header'>
        <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
          <div id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
              <h1 class='title' style='background: transparent; border-width: 0px'>
                <b:include name='title'/>
              </h1>
            </div>
            <b:include name='description'/>
          </div>
        <b:else/>
          <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                        + &quot;background-position: &quot;                        + data:backgroundPositionStyleStr + &quot;; &quot;                        + data:widthStyleStr                        + &quot;min-height: &quot; + data:height                        + &quot;_height: &quot; + data:height                        + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
              <h1 class='title' style='background: transparent; border-width: 0px'>
                <b:include name='title'/>
              </h1>
            </div>
            <b:include name='description'/>
          </div>
        </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
	    <b:if cond='data:blog.pageType != &quot;item&quot;'>
		  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
            <h1 style='text-indent:-9999px;margin:0 0 0 0;padding:0 0 0 0;height:0px;'><b:include name='title'/></h1>
          </b:if>
		</b:if>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
		  <b:if cond='data:blog.pageType != &quot;item&quot;'>
		    <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
              <h1 style='text-indent:-9999px;margin:0 0 0 0;padding:0 0 0 0;height:0px;'><b:include name='title'/></h1>
		    </b:if>
		  </b:if>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>  	
        <b:if cond='data:blog.pageType != &quot;item&quot;'>
		  <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
             <p class='title'><b:include name='title'/></p>
		   <b:else/>
		     <h1 class='title'><b:include name='title'/></h1>
		   </b:if>
		<b:else/>
          <p class='title'><b:include name='title'/></p>
		</b:if>
	    <b:include name='description'/>
      </div>
	</div>
  </b:if>
</b:includable>
        <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
        <b:includable id='title'>
  <b:if cond='data:blog.url == data:blog.homepageUrl'>
    <data:title/>
  <b:else/>
    <a expr:href='data:blog.homepageUrl'><data:title/></a>
  </b:if>
</b:includable>
      </b:widget>
    </b:section>
	
	<b:section class='header-right' id='header-right' maxwidgets='1' showaddelement='yes'>
<b:widget id='HTML1' locked='false' title='' type='HTML'>
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
	
	<div class='clear'/>
  </header>
  <!-- header wrapper end -->

  <b:if cond='data:blog.isMobile'>
  <!-- mobile navigation menu start -->
	<div id='mobile-nav'>
		<span><a expr:href='data:blog.homepageUrl'>Beranda</a></span> &#183; 
		<span><a href='#'>Teknologi</a></span> &#183; 
		<span><a href='#'>Olahraga</a></span> &#183; 
		<span><a href='#'>Entertainment</a></span> &#183; 
		<span><a href='#'>Gaya Hidup</a></span>
	</div>
  <!-- mobile navigation menu end -->
  <b:else/>
<nav id='nav'>
<a class='toggleMenu' href='#'><i class='fa fa-th-list'/> Menu</a>
<!-- secondary navigation menu start -->
<ul class='nav nav-menu2'>
<li><a class='active' href='/'><i class='fa fa-home'/> Home</a></li>
<li><a href='#'>Menu 1</a>
<ul>
<li><a href='#'>SubMenu 1</a></li>
<li><a href='#'>SubMenu 2</a></li>
<li><a href='#'>SubMenu 3</a></li>
</ul>
</li>
<li><a href='#'>Menu 2</a>
<ul>
<li><a href='#'>SubMenu 1</a></li>
<li><a href='#'>SubMenu 2</a></li>
<li><a href='#'>SubMenu 3</a></li>
</ul>
</li>
<li><a href='#'>Menu 3</a></li>
<li><a href='#'>Menu 4</a></li>
</ul>
<!-- secondary navigation menu end -->
<form action='/search' id='search-form' method='get'><table><tbody><tr><td class='search-box'><input id='search-box' name='q' onblur='if(this.value==&apos;&apos;)this.value=this.defaultValue;' onfocus='if(this.value==this.defaultValue)this.value=&apos;&apos;;' type='text' value='Search...' vinput=''/></td>
<td class='search-button'><input id='search-button' type='submit' value='?'/></td></tr></tbody></table></form>
<div class='clear'/>
<!-- secondary navigation menu end -->
  </nav>
  
  </b:if>
  
  <div class='clear'/>
  <!-- secondary navigation menu end -->
  
  <!-- content wrapper start -->
  <div id='content-wrapper'>
  
  <b:section class='largebanner' id='largebanner' maxwidgets='1' showaddelement='yes'>
    <b:widget id='HTML2' locked='false' title='' type='HTML'>
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
  
  <!-- post wrapper start -->
  <div id='post-wrapper'>
  <div class='post-container'>
  <b:section class='main' id='main' showaddelement='no'>
    <b:widget id='Blog1' locked='true' title='Posting Blog' type='Blog'>
      <b:includable id='main' var='top'>
	  <b:include data='posts' name='breadcrumb'/>
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
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-posts&quot;&gt;
        </b:if>
        <div class='post-outer'>
        <b:include data='post' name='post'/>
        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:include data='post' name='comment_picker'/>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:include data='post' name='comment_picker'/>
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

    <!-- navigation -->
	<b:if cond='data:blog.pageType == &quot;index&quot;'>
		<b:include name='page-navi'/>
    <b:else/>
    <b:if cond='data:blog.pageType == &quot;archive&quot;'>
        <b:include name='page-navi'/>
	<b:else/>
		<b:include name='nextprev'/>
	</b:if>
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
    <dl class='comments-block' id='comments-block'>
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
      <b:includable id='breadcrumb' var='posts'>
      <b:if cond='data:blog.homepageUrl != data:blog.url'> 
      <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
        <div class='breadcrumbs'><span><a expr:href='data:blog.homepageUrl' rel='nofollow'>Home</a></span> &#187; <span><data:blog.pageName/></span>
	    </div>
      <b:else/>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
        <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.labels'>
        <div class='breadcrumbs'><span itemscope='' itemtype='http://data-vocabulary.org/Breadcrumb'><a expr:href='data:blog.homepageUrl' itemprop='url'><span itemprop='title'>Home</span></a></span> &#187; <b:loop values='data:post.labels' var='label'><span itemscope='' itemtype='http://data-vocabulary.org/Breadcrumb'><a expr:href='data:label.url + &quot;?&amp;max-results=8&quot;' itemprop='url'><span itemprop='title'><data:label.name/></span></a></span><b:if cond='data:label.isLast != &quot;true&quot;'> &#187; </b:if> </b:loop> &#187; <span><data:post.title/></span>
        </div>
        <b:else/>
        <div class='breadcrumbs'><span><a expr:href='data:blog.homepageUrl' rel='nofollow'>Home</a></span> &#187; <span>Uncategories</span> &#187; <span><data:post.title/></span></div>
	    </b:if>
        </b:loop>
      <b:else/>
        <b:if cond='data:blog.pageType == &quot;archive&quot;'>
        <div class='breadcrumbs'> <span><a expr:href='data:blog.homepageUrl' rel='nofollow'>Home</a></span> &#187; <span>Archive for <data:blog.pageName/></span> 
	    </div> 
      <b:else/>
        <b:if cond='data:blog.searchQuery'>
        <div class='breadcrumbs'><span><a expr:href='data:blog.homepageUrl' rel='nofollow'>Home</a></span> &#187; <span><data:blog.pageName/></span>
	    </div>
      <b:else/>
        <b:if cond='data:blog.pageType == &quot;index&quot;'> 
        <div class='breadcrumbs'>
	    <b:if cond='data:blog.pageName == &quot;&quot;'> <span><a expr:href='data:blog.homepageUrl' rel='nofollow'>Home</a></span> &#187; <span>All post</span>
        <b:else/>
        <span><a expr:href='data:blog.homepageUrl' rel='nofollow'>Home</a></span> &#187; <span><data:blog.pageName/></span> 
        </b:if>
        </div>
      </b:if>
      </b:if>
      </b:if>
      </b:if>
      </b:if>
      </b:if>
</b:includable>
      <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <div class='pesan-komentar'><p><data:blogCommentMessage/></p></div>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <div class='pesan-komentar'><p><data:blogCommentMessage/></p></div>
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
      <h3><b:if cond='data:post.numComments == 0'> 0 Response to &quot;<data:blog.pageName/>&quot;</b:if> <b:if cond='data:post.numComments == 1'> 1 Response to &quot;<data:blog.pageName/>&quot; </b:if> <b:if cond='data:post.numComments &gt; 1'> <data:post.numComments/> Responses to &quot;<data:blog.pageName/>&quot; </b:if></h3>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
              &#160;
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
              &#160;
          </b:if>

          <data:post.commentRangeText/>

          <b:if cond='data:post.hasNewerLinks'>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
          </b:if>
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
<!-- MOBILE INDEX POST HERE -->
  <div class='mobile-date-outer date-outer'>

    <div class='mobile-post-outer'>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
			<b:else/>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
				<img expr:alt='data:post.title' expr:title='data:post.title' src='http://3.bp.blogspot.com/-ltyYh4ysBHI/U04MKlHc6pI/AAAAAAAADQo/PFxXaGZu9PQ/s66-c/no-image.png'/>
              </div>
            </div>
          </b:if>

      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title' itemprop='name'>
          <data:post.title/>
        </h3>
	  </a>		  

          <div class='post-body'>

		    <div class='post-info'>
				<b:if cond='data:top.showAuthor'>
					<b:if cond='data:post.authorProfileUrl'>
					  <span class='author-info'>
					  <i class='fa fa-user'/>
					  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
						<meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
						<a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
						  <span itemprop='name'><data:post.author/></span>
						</a>
					  </span>
					  </span>
					<b:else/>
					  <span class='author-info'>
					  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
						<span itemprop='name'><data:post.author/></span>
					  </span>
					  </span>
					</b:if>
				</b:if> 
				<b:if cond='data:top.showTimestamp'>
				<b:if cond='data:post.url'>
				  <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
				  <span class='time-info'>
				  <i class='fa fa-calendar'/> <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published updated' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
				  </span>
				</b:if>
				</b:if> 
				<b:if cond='data:blog.pageType != &quot;item&quot;'>
				  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
					<b:if cond='data:post.allowComments'>
					  <span class='comment-info'>
					  <i class='fa fa-comments'/> <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'> <b:if cond='data:post.numComments == 0'> Add Comment </b:if> <b:if cond='data:post.numComments == 1'> 1 Comment </b:if> <b:if cond='data:post.numComments &gt; 1'> <data:post.numComments/> Comments </b:if> 
					  </a>
					  </span>
					</b:if>
				  </b:if>
				</b:if>	
			</div>

          </div>
        </div>

        <div style='clear: both;'/>

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
<!-- MOBILE PAGE NAVIGATION LINKS HERE -->
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
<!-- MOBILE ITEM POST HERE -->
  <div class='date-outer'>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
          <b:if cond='data:post.thumbnailUrl'>
            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
          </b:if>
          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
          <meta expr:content='data:post.id' itemprop='postId'/>

          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <h3 class='mobile-post-title entry-title' itemprop='name'>
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

		  <div class='post-info' style='margin-bottom:15px;'>
				<b:if cond='data:top.showAuthor'>
					<b:if cond='data:post.authorProfileUrl'>
					  <span class='author-info'>
					  <i class='fa fa-user'/>
					  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
						<meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
						<a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
						  <span itemprop='name'><data:post.author/></span>
						</a>
					  </span>
					  </span>
					<b:else/>
					  <span class='author-info'>
					  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
						<span itemprop='name'><data:post.author/></span>
					  </span>
					  </span>
					</b:if>
				</b:if> 
				<b:if cond='data:top.showTimestamp'>
				<b:if cond='data:post.url'>
				  <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
				  <span class='time-info'>
				  <i class='fa fa-calendar'/> <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published updated' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
				  </span>
				</b:if>
				</b:if> 
				<b:if cond='data:blog.pageType != &quot;item&quot;'>
				  <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
					<b:if cond='data:post.allowComments'>
					  <span class='comment-info'>
					  <i class='fa fa-comments'/> <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'> <b:if cond='data:post.numComments == 0'> Add Comment </b:if> <b:if cond='data:post.numComments == 1'> 1 Comment </b:if> <b:if cond='data:post.numComments &gt; 1'> <data:post.numComments/> Comments </b:if> 
					  </a>
					  </span>
					</b:if>
				  </b:if>
				</b:if>	
			</div>		  
		  
          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
		  <!-- IKLAN BAWAH JUDUL VERSI MOBILE -->
		  
            <data:post.body/>
			
            <div style='clear: both;'/> 
			
				<div id='share-buttons-mobile'>
				<p>Share : </p>
				<a expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:blog.url' rel='nofollow' style='background:#3b5998;'>Facebook</a>
				<a expr:href='&quot;http://plus.google.com/share?url=&quot; + data:blog.url' rel='nofollow' style='background:#c0361a;'>Google+</a>
				<a expr:href='&quot;https://twitter.com/intent/tweet?url=&quot; + data:blog.url + &quot;&amp;text=&quot; + data:post.title + &quot;&amp;lang=id&quot;' rel='nofollow' style='background:#4099ff;'>Twitter</a>
				<div class='clear'/>
				</div>
				<div id='related-posts-mobile'>
				<h3>Related Posts :</h3>
				<b:loop values='data:post.labels' var='label'> <b:if cond='data:label.isLast != &quot;true&quot;'/> <b:if cond='data:blog.pageType == &quot;item&quot;'> <script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels&amp;max-results=5&quot;' type='text/javascript'/></b:if> </b:loop> <script type='text/javascript'> removeRelatedDuplicates(); printRelatedLabels(); </script>
				</div>
				
          </div>
		  
        </div>

        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:include data='post' name='comment_picker'/>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:include data='post' name='comment_picker'/>
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

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
      <b:includable id='page-navi'>
    <div class='pagenavi'>
        <script type='text/javascript'>
        var pageNaviConf = {
            perPage: 5,
            numPages: 9,
            firstText: &quot;First&quot;,
            lastText: &quot;Last&quot;,
            nextText: &quot;Next&quot;,
            prevText: &quot;Prev&quot;
        }
        </script>
		<script type='text/javascript'>
		//<![CDATA[
		function pageNavi(o){var m=location.href,l=m.indexOf("/search/label/")!=-1,a=l?m.substr(m.indexOf("/search/label/")+14,m.length):"";a=a.indexOf("?")!=-1?a.substr(0,a.indexOf("?")):a;var g=l?"/search/label/"+a+"?updated-max=":"/search?updated-max=",k=o.feed.entry.length,e=Math.ceil(k/pageNaviConf.perPage);if(e<=1){return}var n=1,h=[""];l?h.push("/search/label/"+a+"?max-results="+pageNaviConf.perPage):h.push("/?max-results="+pageNaviConf.perPage);for(var d=2;d<=e;d++){var c=(d-1)*pageNaviConf.perPage-1,b=o.feed.entry[c].published.$t,f=b.substring(0,19)+b.substring(23,29);f=encodeURIComponent(f);if(m.indexOf(f)!=-1){n=d}h.push(g+f+"&max-results="+pageNaviConf.perPage)}pageNavi.show(h,n,e)}pageNavi.show=function(f,e,a){var d=Math.floor((pageNaviConf.numPages-1)/2),g=pageNaviConf.numPages-1-d,c=e-d;if(c<=0){c=1}endPage=e+g;if((endPage-c)<pageNaviConf.numPages){endPage=c+pageNaviConf.numPages-1}if(endPage>a){endPage=a;c=a-pageNaviConf.numPages+1}if(c<=0){c=1}var b='<span class="pages">Pages '+e+' of '+a+"</span> ";if(c>1){b+='<a href="'+f[1]+'">'+pageNaviConf.firstText+"</a>"}if(e>1){b+='<a href="'+f[e-1]+'">'+pageNaviConf.prevText+"</a>"}for(i=c;i<=endPage;++i){if(i==e){b+='<span class="current">'+i+"</span>"}else{b+='<a href="'+f[i]+'">'+i+"</a>"}}if(e<a){b+='<a href="'+f[e+1]+'">'+pageNaviConf.nextText+"</a>"}if(endPage<a){b+='<a href="'+f[a]+'">'+pageNaviConf.lastText+"</a>"}document.write(b)};(function(){var b=location.href;if(b.indexOf("?q=")!=-1||b.indexOf(".html")!=-1){return}var d=b.indexOf("/search/label/")+14;if(d!=13){var c=b.indexOf("?"),a=(c==-1)?b.substring(d):b.substring(d,c);document.write('<script type="text/javascript" src="/feeds/posts/summary/-/'+a+'?alt=json-in-script&callback=pageNavi&max-results=99999"><\/script>')}else{document.write('<script type="text/javascript" src="/feeds/posts/summary?alt=json-in-script&callback=pageNavi&max-results=99999"><\/script>')}})();
		//]]>
		</script>
        <div class='clear'/>
    </div>
	</b:includable>
      <b:includable id='post' var='post'>
  <article class='post hentry' itemprop='blogPost' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
    <b:if cond='data:post.firstImageUrl'>
      <meta expr:content='data:post.firstImageUrl' itemprop='image'/>
	</b:if>
	
	<b:if cond='data:blog.pageType != &quot;item&quot;'>
	<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
	<b:if cond='data:post.thumbnailUrl'>
		<a expr:href='data:post.url'><div class='img-thumbnail'><span class='rollover'/><script type='text/javascript'>
		document.write(bp_thumbnail_resize(&quot;<data:post.thumbnailUrl/>&quot;,&#39;<data:post.title/>&#39;));
		</script></div>
		</a>
	<b:else/>
		<b:if cond='data:post.firstImageUrl'>
		<a expr:href='data:post.url'><div class='img-thumbnail'><span class='rollover'/><img expr:alt='data:post.title' expr:src='data:post.firstImageUrl' expr:title='data:post.title'/></div>
		</a>
	<b:else/>
		<a expr:href='data:post.url'><div class='img-thumbnail'><span class='rollover'/><img expr:alt='data:post.title' expr:title='data:post.title' src='http://3.bp.blogspot.com/-ltyYh4ysBHI/U04MKlHc6pI/AAAAAAAADQo/PFxXaGZu9PQ/w200-h150-c/no-image.png'/></div>
		</a>
	</b:if> 
    </b:if>
	</b:if> 
    </b:if>
	
    <a expr:name='data:post.id'/>
    <b:if cond='data:post.title'>
	  <b:if cond='data:blog.pageType != &quot;item&quot;'>
	    <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <h1 class='post-title entry-title' itemprop='name'>
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
          </h1>
	    <b:else/>
          <h2 class='post-title entry-title' itemprop='name'>
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
          </h2>
		</b:if>
	  <b:else/>
        <h1 class='post-title entry-title' itemprop='name'>
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
        </h1>
	  </b:if>
    </b:if>

	<div class='post-info'>
		<b:if cond='data:top.showAuthor'>
            <b:if cond='data:post.authorProfileUrl'>
			  <span class='author-info'>
              <i class='fa fa-user'/>
			  <span class='vcard'>
			  <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                  <span itemprop='name'><data:post.author/></span>
                </a>
              </span>
			  </span>
			  </span>
            <b:else/>
			  <span class='author-info'>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <span itemprop='name'><data:post.author/></span>
              </span>
			  </span>
            </b:if>
        </b:if> 
		<b:if cond='data:top.showTimestamp'>
        <b:if cond='data:post.url'>
          <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
		  <span class='time-info'>
          <i class='fa fa-calendar'/> <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published updated' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
		  </span>
        </b:if>
        </b:if> 
        <b:if cond='data:blog.pageType != &quot;item&quot;'>
          <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
            <b:if cond='data:post.allowComments'>
			  <span class='comment-info'>
              <i class='fa fa-comments'/> <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'> <b:if cond='data:post.numComments == 0'> Add Comment </b:if> <b:if cond='data:post.numComments == 1'> 1 Comment </b:if> <b:if cond='data:post.numComments &gt; 1'> <data:post.numComments/> Comments </b:if> 
			  </a>
			  </span>
            </b:if>
          </b:if>
        </b:if>	
        <b:if cond='data:post.labels'>
		  <span class='label-info'>
          <i class='fa fa-tags'/> 
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
          </b:loop>
		  </span>
        </b:if>
		<b:include data='post' name='postQuickEdit'/>
	</div>
	
    <div class='post-header'>
    <div class='post-header-line-1'/>
    </div>

	<b:if cond='data:blog.pageType != &quot;item&quot;'>

    <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
      <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody description'>
        <data:post.body/>
        <div style='clear: both;'/> 
      </div>
    <b:else/>
	
	  
		<div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody description'>
			<div>
			<data:post.snippet/>
			</div>
			<a class='readmore' expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'>Read More <i class='fa fa-caret-right'/></a>
			<div style='clear: both;'/> 	
		</div>	
    </b:if>
	
	<b:else/>
	
	  <!-- Then use the post body as the schema.org description, for good G+/FB snippeting. -->
      <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='description articleBody'>
		
		<!-- IKLAN BAWAH JUDUL VERSI DESKTOP -->
	  	  
        <data:post.body/>
		
        <div style='clear: both;'/> 
		
		<div class='share-buttons-box'>
		<div class='share-buttons'>
			<div class='share gplus'><div class='g-plusone' data-size='tall' expr:data-href='data:post.url'/></div>
			<div class='share like'><div class='fb-like' data-action='like' data-layout='box_count' data-share='false' data-show-faces='false' expr:data-href='data:post.url'/></div>
			<div class='share fbshare'><div class='fb-share-button' data-type='box_count' expr:data-href='data:post.url'/></div>
			<div class='share tweet'><a class='twitter-share-button' data-count='vertical' data-lang='en' data-size='normal' expr:data-url='data:post.url' href='https://twitter.com/share'>Tweet</a></div>
			<div class='share linkedin'><script src='//platform.linkedin.com/in.js' type='text/javascript'>
			lang: en_US </script><script data-counter='top' expr:data-url='data:post.url' type='IN/Share'/></div>
		</div>
		</div>
			<div class='berlangganan-box'>
<form action='https://feedburner.google.com/fb/a/mailverify' method='post' onsubmit='window.open(&apos;https://feedburner.google.com/fb/a/mailverify?uri=Competitiv&apos;, &apos;popupwindow&apos;, &apos;scrollbars=yes,width=550,height=520&apos;);return true' target='popupwindow'>
  <p>Sign up here with your email address to receive updates from this blog in your inbox.</p><p><input class='email-address' name='email' placeholder='Your Email Address...' type='text'/></p><input name='uri' type='hidden' value='Competitiv'/>
<input name='loc' type='hidden' value='en_US'/>
<p><input class='submit-email' type='submit' value='Subscribe'/></p>
</form>
</div>
		<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?&#39;http&#39;:&#39;https&#39;;if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+&#39;://platform.twitter.com/widgets.js&#39;;fjs.parentNode.insertBefore(js,fjs);}}(document, &#39;script&#39;, &#39;twitter-wjs&#39;);</script>
		<div style='clear: both;'/>
			
			<!-- Related Post Widget Start -->
			  <div class='related-post' id='related-post'/>
			  <script type='text/javascript'>
			  var labelArray = [<b:if cond='data:post.labels'><b:loop values='data:post.labels' var='label'>
					  &quot;<data:label.name/>&quot;<b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
				  </b:loop></b:if>];
			  var relatedPostConfig = {
				  homePage: &quot;<data:blog.homepageUrl/>&quot;,
				  widgetTitle: &quot;&lt;h4&gt;Related Posts :&lt;/h4&gt;&quot;,
				  numPosts: 5,
				  summaryLength: 140,
				  titleLength: &quot;auto&quot;,
				  thumbnailSize: 60,
				  noImage: &quot;http://3.bp.blogspot.com/-ltyYh4ysBHI/U04MKlHc6pI/AAAAAAAADQo/PFxXaGZu9PQ/w60-h60-c/no-image.png&quot;,
				  containerId: &quot;related-post&quot;,
				  newTabLink: false,
				  moreText: &quot;Read More...&quot;,
				  widgetStyle: 2,
				  callBack: function() {}
			  };
			  </script>
			<!-- Related Post Widget End -->

      </div>

	</b:if>	
	
  </article>

  <!-- facebook comments responsive JS -->
  <b:if cond='data:blog.pageType == &quot;item&quot;'>
	<script>
	//<![CDATA[
	$(window).bind("load", function(){    
	  var container_width = $('.fbbox-comments').width();    
	  var fburl=(window.location.href);
	  var fbfix=fburl.indexOf('?');
	  var fburlfix = fburl.substring(0, fbfix != -1 ? fbfix : fburl.length); 
		$('.fbbox-comments').html('<div class="fb-comments" ' + 
		'data-href="' + fburlfix + '"' +
		' data-width="' + container_width + '" data-num-posts="5"></div>');
		FB.XFBML.parse( );    
	}); 
	//]]>
	</script>
	<div class='fbbox-comments' style='width:100%;margin-top:20px'>
	<div class='fb-comments' data-num-posts='2' data-width='680' expr:data-href='data:blog.url'/>
	</div>
  </b:if>
  
</b:includable>
      <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <!-- <img alt='' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/> -->
		<b style='color:#EE3322;'><i class='fa fa-pencil'/> Edit</b>
      </a>
    </span>
  </b:if>
</b:includable>
      <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showOrkutButton'><a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToOrkutMsg/></span></a></b:if><b:if cond='data:top.showDummy'><div class='goog-inline-block dummy-container'><data:post.dummyTag/></div></b:if>
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
      <div class='pesan-komentar'><p><data:blogCommentMessage/></p></div>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <div class='pesan-komentar'><p><data:blogCommentMessage/></p></div>
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
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
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
          document.getElementById(domId).insertBefore(replybox.parentNode, null);
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
      <h3><b:if cond='data:post.numComments == 0'> 0 Response to &quot;<data:blog.pageName/>&quot;</b:if> <b:if cond='data:post.numComments == 1'> 1 Response to &quot;<data:blog.pageName/>&quot; </b:if> <b:if cond='data:post.numComments &gt; 1'> <data:post.numComments/> Responses to &quot;<data:blog.pageName/>&quot; </b:if></h3>

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
  
   
<b:if cond='data:blog.pageType == &quot;index&quot;'>
<b:if cond='data:blog.searchLabel'><b:else/>
<b:section class='recent-post-one-thumb' id='recent-post-one-thumb-1' maxwidgets='1' preferred='yes' showaddelement='no'>
  <b:widget id='HTML80' locked='false' mobile='yes' title='Label 1' type='HTML'>
    <b:includable id='main'> 
	<div class='widget-content recent-posts'>
	  <script>
	  document.write(&#39;&lt;div class=&quot;recent-post-title&quot;&gt;&lt;h2&gt;&lt;a href=&quot;/search/label/<data:content/>?max-results=10&quot;&gt;<data:title/>&lt;/a&gt;&lt;/h2&gt;&lt;/div&gt;&#39;);
	  document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?orderby=updated&amp;alt=json-in-script&amp;callback=labelthumbs\&quot;&gt;&lt;\/script&gt;&quot;);
	  </script>

	</div>
	</b:includable>
  </b:widget>
</b:section>
  
<b:section class='recent-post-one-thumb' id='recent-post-one-thumb-2' maxwidgets='1' preferred='yes' showaddelement='no'>
  <b:widget id='HTML81' locked='false' mobile='yes' title='Label 2' type='HTML'>
    <b:includable id='main'> 
	<div class='widget-content recent-posts'>
	  <script>
	  document.write(&#39;&lt;div class=&quot;recent-post-title&quot;&gt;&lt;h2&gt;&lt;a href=&quot;/search/label/<data:content/>?max-results=10&quot;&gt;<data:title/>&lt;/a&gt;&lt;/h2&gt;&lt;/div&gt;&#39;);
	  document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?orderby=updated&amp;alt=json-in-script&amp;callback=labelthumbs\&quot;&gt;&lt;\/script&gt;&quot;);
	  </script>

	</div>
	</b:includable>
  </b:widget>
</b:section>

<div class='clear'/>

<b:section class='recent-post-one-thumb' id='recent-post-one-thumb-3' maxwidgets='1' preferred='yes' showaddelement='no'>
  <b:widget id='HTML82' locked='false' mobile='yes' title='Label 3' type='HTML'>
    <b:includable id='main'> 
	<div class='widget-content recent-posts'>
	  <script>
	  document.write(&#39;&lt;div class=&quot;recent-post-title&quot;&gt;&lt;h2&gt;&lt;a href=&quot;/search/label/<data:content/>?max-results=10&quot;&gt;<data:title/>&lt;/a&gt;&lt;/h2&gt;&lt;/div&gt;&#39;);
	  document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?orderby=updated&amp;alt=json-in-script&amp;callback=labelthumbs\&quot;&gt;&lt;\/script&gt;&quot;);
	  </script>

	</div>
	</b:includable>
  </b:widget>
</b:section>
  
<b:section class='recent-post-one-thumb' id='recent-post-one-thumb-4' maxwidgets='1' preferred='yes' showaddelement='no'>
  <b:widget id='HTML83' locked='false' mobile='yes' title='Label 4' type='HTML'>
    <b:includable id='main'> 
	<div class='widget-content recent-posts'>
	  <script>
	  document.write(&#39;&lt;div class=&quot;recent-post-title&quot;&gt;&lt;h2&gt;&lt;a href=&quot;/search/label/<data:content/>?max-results=10&quot;&gt;<data:title/>&lt;/a&gt;&lt;/h2&gt;&lt;/div&gt;&#39;);
	  document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?orderby=updated&amp;alt=json-in-script&amp;callback=labelthumbs\&quot;&gt;&lt;\/script&gt;&quot;);
	  </script>

	</div>
	</b:includable>
  </b:widget>
</b:section>
<div class='clear'/>

<b:section class='recent-post-one-thumb' id='recent-post-one-thumb-5' maxwidgets='1' preferred='yes' showaddelement='no'>
  <b:widget id='HTML84' locked='false' mobile='yes' title='Label 5' type='HTML'>
    <b:includable id='main'> 
	<div class='widget-content recent-posts'>
	  <script>
	  document.write(&#39;&lt;div class=&quot;recent-post-title&quot;&gt;&lt;h2&gt;&lt;a href=&quot;/search/label/<data:content/>?max-results=10&quot;&gt;<data:title/>&lt;/a&gt;&lt;/h2&gt;&lt;/div&gt;&#39;);
	  document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?orderby=updated&amp;alt=json-in-script&amp;callback=labelthumbs\&quot;&gt;&lt;\/script&gt;&quot;);
	  </script>

	</div>
	</b:includable>
  </b:widget>
</b:section>
  
<b:section class='recent-post-one-thumb' id='recent-post-one-thumb-6' maxwidgets='1' preferred='yes' showaddelement='no'>
  <b:widget id='HTML85' locked='false' mobile='yes' title='Label 6' type='HTML'>
    <b:includable id='main'> 
	<div class='widget-content recent-posts'>
	  <script>
	  document.write(&#39;&lt;div class=&quot;recent-post-title&quot;&gt;&lt;h2&gt;&lt;a href=&quot;/search/label/<data:content/>?max-results=10&quot;&gt;<data:title/>&lt;/a&gt;&lt;/h2&gt;&lt;/div&gt;&#39;);
	  document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/<data:content/>?orderby=updated&amp;alt=json-in-script&amp;callback=labelthumbs\&quot;&gt;&lt;\/script&gt;&quot;);
	  </script>

	</div>
	</b:includable>
  </b:widget>
</b:section>

</b:if>
</b:if>  
<div class='clear'/>
  
  
  </div>
  <!-- post wrapper end -->

  
  <!-- sidebar wrapper start -->
  <aside id='sidebar-wrapper'>
  <div class='sidebar-container'>
  
  <div class='set set-1'>
    <b:section class='panel panel-1' id='panel-1' maxwidgets='1' preferred='yes'>
      <b:widget id='PopularPosts1' locked='false' title='Entri Populer' type='PopularPosts'>
        <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='!data:showThumbnails'>
          <b:if cond='!data:showSnippets'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
          <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
            <b:if cond='data:post.thumbnail'>
              <div class='item-thumbnail'>
                <a expr:href='data:post.href' target='_blank'>
                  <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                </a>
              </div>
            </b:if>
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <b:if cond='data:showSnippets'>
              <div class='item-snippet'><data:post.snippet/></div>
            </b:if>
          </div>
          <div style='clear: both;'/>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
      </b:widget>
    </b:section>
	<b:section class='panel panel-2' id='panel-2' maxwidgets='1' preferred='yes'>
<b:widget id='Label1' locked='false' title='Label' type='Label'>
  <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <b:if cond='data:blog.url == data:label.url'>
              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
            <b:else/>
              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
            </b:if>
            <b:if cond='data:showFreqNumbers'>
              <span dir='ltr'>(<data:label.count/>)</span>
            </b:if>
          </li>
        </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
</b:widget>
</b:section>
	<b:section class='panel panel-3' id='panel-3' maxwidgets='1' preferred='yes'>
<b:widget id='BlogArchive1' locked='false' title='Arsip Blog' type='BlogArchive'>
  <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div class='widget-content'>
  <div id='ArchiveList'>
  <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
    <b:include cond='data:style == &quot;HIERARCHY&quot;' data='data' name='interval'/>
    <b:include cond='data:style == &quot;FLAT&quot;' data='data' name='flat'/>
    <b:include cond='data:style == &quot;MENU&quot;' data='data' name='menu'/>
  </div>
  </div>
  <b:include name='quickedit'/>
  </div>
</b:includable>
  <b:includable id='flat' var='data'>
  <ul class='flat'>
    <b:loop values='data:data' var='i'>
      <li class='archivedate'>
        <a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
      </li>
    </b:loop>
  </ul>
</b:includable>
  <b:includable id='interval' var='intervalData'>
  <b:loop values='data:intervalData' var='i'>
      <ul class='hierarchy'>
        <li expr:class='&quot;archivedate &quot; + data:i.expclass'>
          <b:include data='i' name='toggle'/>
          <a class='post-count-link' expr:href='data:i.url'><data:i.name/></a>
            <span class='post-count' dir='ltr'>(<data:i.post-count/>)</span>
          <b:include cond='data:i.data' data='i.data' name='interval'/>
          <b:include cond='data:i.posts' data='i.posts' name='posts'/>
        </li>
      </ul>
  </b:loop>
</b:includable>
  <b:includable id='menu' var='data'>
  <select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
    <option value=''><data:title/></option>
    <b:loop values='data:data' var='i'>
      <option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
    </b:loop>
  </select>
</b:includable>
  <b:includable id='posts' var='posts'>
  <ul class='posts'>
    <b:loop values='data:posts' var='i'>
      <li><a expr:href='data:i.url'><data:i.title/></a></li>
    </b:loop>
  </ul>
</b:includable>
  <b:includable id='toggle' var='interval'>
  <b:if cond='data:interval.toggleId'>
  <b:if cond='data:interval.expclass == &quot;expanded&quot;'>
    <a class='toggle' href='javascript:void(0)'>
      <span class='zippy toggle-open'>&#9660;&#160;</span>
    </a>
  <b:else/>
    <a class='toggle' href='javascript:void(0)'>
      <span class='zippy'>
        <b:if cond='data:blog.languageDirection == &quot;rtl&quot;'>
          &#9668;&#160;
        <b:else/>
          &#9658;&#160;
        </b:if>
      </span>
    </a>
  </b:if>
 </b:if>
</b:includable>
</b:widget>
</b:section>
  </div>
  <div class='clear'/>
  
  <b:section class='sidebar' id='sidebar' preferred='yes'>
    <b:widget id='HTML3' locked='false' title='' type='HTML'>
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
  </div>
  </aside>
  <!-- sidebar wrapper end -->
  
  </div>
  <!-- content wrapper end -->
  <div class='clear'/>

    <aside id='bottombar'>
	<b:section class='left' id='left' preferred='yes'>
<b:widget id='Label2' locked='false' title='Label' type='Label'>
  <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <b:if cond='data:blog.url == data:label.url'>
              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
            <b:else/>
              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
            </b:if>
            <b:if cond='data:showFreqNumbers'>
              <span dir='ltr'>(<data:label.count/>)</span>
            </b:if>
          </li>
        </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
</b:widget>
</b:section>
		
    <b:section class='center' id='center' preferred='yes'>
      <b:widget id='PopularPosts2' locked='false' title='Popular Posts' type='PopularPosts'>
        <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='!data:showThumbnails'>
          <b:if cond='!data:showSnippets'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
          <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
            <b:if cond='data:post.thumbnail'>
              <div class='item-thumbnail'>
                <a expr:href='data:post.href' target='_blank'>
                  <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                </a>
              </div>
            </b:if>
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <b:if cond='data:showSnippets'>
              <div class='item-snippet'><data:post.snippet/></div>
            </b:if>
          </div>
          <div style='clear: both;'/>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
      </b:widget>
    </b:section>
	
	<b:section class='right' id='right' preferred='yes'>
<b:widget id='Label3' locked='false' title='Label' type='Label'>
  <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <b:if cond='data:blog.url == data:label.url'>
              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
            <b:else/>
              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
            </b:if>
            <b:if cond='data:showFreqNumbers'>
              <span dir='ltr'>(<data:label.count/>)</span>
            </b:if>
          </li>
        </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
</b:widget>
</b:section>
    </aside>  
 
  <!-- footer wrapper start -->
  <footer id='footer-wrapper'>
	<div class='footer-left'>
		Copyright 2015 <a expr:href='data:blog.homepageUrl' rel='copyright'><data:blog.title/></a>
	</div>
	<div class='footer-right'>
		Powered by <a href='http://www.blogger.com/' title='Blogger'>Blogger.com</a>
	</div>	
  </footer>
  <!-- footer wrapper end --> 
  
  </div>
  <!-- wrapper end -->

<div class='back-to-top'><a href='#' id='back-to-top' title='back to top'>
    <i class='fa fa-chevron-up'/> 
</a></div>

<script>            
$(window).scroll(function() {
    if($(this).scrollTop() &gt; 200) {
        $(&#39;#back-to-top&#39;).fadeIn();
    } else {
        $(&#39;#back-to-top&#39;).fadeOut();
    }
});

$(&#39;#back-to-top&#39;).hide().click(function() {
    $(&#39;html, body&#39;).animate({scrollTop:0}, 1000);
    return false;
});
</script>  
  
<script type='text/javascript'>
//<![CDATA[
var ww=document.body.clientWidth;$(document).ready(function(){$(".nav li a").each(function(){if($(this).next().length>0){$(this).addClass("parent")}});$(".toggleMenu").click(function(e){e.preventDefault();$(this).toggleClass("active");$(".nav").toggle()});adjustMenu()});$(window).bind("resize orientationchange",function(){ww=document.body.clientWidth;adjustMenu()});var adjustMenu=function(){if(ww<768){$(".toggleMenu").css("display","inline-block");if(!$(".toggleMenu").hasClass("active")){$(".nav").hide()}else{$(".nav").show()}$(".nav li").unbind("mouseenter mouseleave");$(".nav li a.parent").unbind("click").bind("click",function(e){e.preventDefault();$(this).parent("li").toggleClass("hover")})}else if(ww>=768){$(".toggleMenu").css("display","none");$(".nav").show();$(".nav li").removeClass("hover");$(".nav li a").unbind("click");$(".nav li").unbind("mouseenter mouseleave").bind("mouseenter mouseleave",function(){$(this).toggleClass("hover")})}}
//]]>
</script>
<script type='text/javascript'>
//<![CDATA[
/*! Matt Tabs v2.2.1 | https://github.com/matthewhall/matt-tabs */
!function(a){"use strict";var b=function(b,c){var d=this;d.element=b,d.$element=a(b),d.tabs=d.$element.children(),d.options=a.extend({},a.fn.mtabs.defaults,c),d.current_tab=0,d.init()};b.prototype={init:function(){var a=this;a.tabs.length&&(a.build(),a.buildTabMenu())},build:function(){var b=this,c=b.options,d=c.tab_text_el,e=c.container_class;b.tab_names=[],b.$wrapper=b.$element.wrapInner('<div class="'+e+'" />').find("."+e),b.tabs.wrapAll('<div class="'+c.tabs_container_class+'" />'),b.tabs.each(function(c,e){var f,g=a(e),h=d;f=g.find(h).filter(":first").hide().text(),b.tab_names.push(f)}),a.isFunction(c.onReady)&&c.onReady.call(b.element)},buildTabMenu:function(){for(var b,c=this,d=c.options,e=d.tabsmenu_el,f=c.tab_names,g="<"+e+' class="'+d.tabsmenu_class+'">',h=0,i=f.length,j=function(){var a=arguments;return d.tmpl.tabsmenu_tab.replace(/\{[0-9]\}/g,function(b){var c=Number(b.replace(/\D/g,""));return a[c]||""})};i>h;h++)g+=j(h+1,f[h]);g+="</"+e+">",c.$tabs_menu=a(g).prependTo(c.$wrapper),b=c.$tabs_menu.find(":first")[0].nodeName.toLowerCase(),c.$tabs_menu.on("click",b,function(b){var d=a(this),e=d.index();c.show(e),b.preventDefault()}).find(":first").trigger("click")},show:function(b){var c=this,d=c.options,e=d.active_tab_class;c.tabs.hide().filter(":eq("+b+")").show(),c.$tabs_menu.children().removeClass(e).filter(":eq("+b+")").addClass(e),a.isFunction(d.onTabSelect)&&b!==c.current_tab&&d.onTabSelect.call(c.element,b),c.current_tab=b},destroy:function(){var a=this,b=a.options.tab_text_el;a.$tabs_menu.remove(),a.tabs.unwrap().unwrap(),a.tabs.removeAttr("style"),a.tabs.children(b+":first").removeAttr("style"),a.$element.removeData("mtabs")}},a.fn.mtabs=function(c,d){return this.each(function(){var e,f=a(this),g=f.data("mtabs");e="object"==typeof c&&c,g||f.data("mtabs",g=new b(this,e)),"string"==typeof c&&g[c](d)})},a.fn.mtabs.defaults={container_class:"tabs",tabs_container_class:"tabs-content",active_tab_class:"active-tab",tab_text_el:"h1, h2, h3, h4, h5, h6",tabsmenu_class:"tabs-menu",tabsmenu_el:"ul",tmpl:{tabsmenu_tab:'<li class="tab-{0}"><span>{1}</span></li>'},onTabSelect:null}}(window.jQuery,window,document);
//]]>
</script>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<script type='text/javascript'>
//<![CDATA[			  
/*! Related Post Widget for Blogger by Taufik Nurrohman => http://gplus.to/tovic */
var randomRelatedIndex,showRelatedPost;(function(n,m,k){var d={widgetTitle:"<h4>Artikel Terkait:</h4>",widgetStyle:1,homePage:"http://www.dte.web.id",numPosts:7,summaryLength:370,titleLength:"auto",thumbnailSize:72,noImage:"data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAIAAACQd1PeAAAAA3NCSVQICAjb4U/gAAAADElEQVQImWOor68HAAL+AX7vOF2TAAAAAElFTkSuQmCC",containerId:"related-post",newTabLink:false,moreText:"Baca Selengkapnya",callBack:function(){}};for(var f in relatedPostConfig){d[f]=(relatedPostConfig[f]=="undefined")?d[f]:relatedPostConfig[f]}var j=function(a){var b=m.createElement("script");b.type="text/javascript";b.src=a;k.appendChild(b)},o=function(b,a){return Math.floor(Math.random()*(a-b+1))+b},l=function(a){var p=a.length,c,b;if(p===0){return false}while(--p){c=Math.floor(Math.random()*(p+1));b=a[p];a[p]=a[c];a[c]=b}return a},e=(typeof labelArray=="object"&&labelArray.length>0)?"/-/"+l(labelArray)[0]:"",h=function(b){var c=b.feed.openSearch$totalResults.$t-d.numPosts,a=o(1,(c>0?c:1));j(d.homePage.replace(/\/$/,"")+"/feeds/posts/summary"+e+"?alt=json-in-script&orderby=updated&start-index="+a+"&max-results="+d.numPosts+"&callback=showRelatedPost")},g=function(z){var s=document.getElementById(d.containerId),x=l(z.feed.entry),A=d.widgetStyle,c=d.widgetTitle+'<ul class="related-post-style-'+A+'">',b=d.newTabLink?' target="_blank"':"",y='<span style="display:block;clear:both;"></span>',v,t,w,r,u;if(!s){return}for(var q=0;q<d.numPosts;q++){if(q==x.length){break}t=x[q].title.$t;w=(d.titleLength!=="auto"&&d.titleLength<t.length)?t.substring(0,d.titleLength)+"&hellip;":t;r=("media$thumbnail" in x[q]&&d.thumbnailSize!==false)?x[q].media$thumbnail.url.replace(/\/s[0-9]+(\-c)?/,"/s"+d.thumbnailSize+"-c"):d.noImage;u=("summary" in x[q]&&d.summaryLength>0)?x[q].summary.$t.replace(/<br ?\/?>/g," ").replace(/<.*?>/g,"").replace(/[<>]/g,"").substring(0,d.summaryLength)+"&hellip;":"";for(var p=0,a=x[q].link.length;p<a;p++){v=(x[q].link[p].rel=="alternate")?x[q].link[p].href:"#"}if(A==2){c+='<li><img alt="" class="related-post-item-thumbnail" src="'+r+'" width="'+d.thumbnailSize+'" height="'+d.thumbnailSize+'"><a class="related-post-item-title" title="'+t+'" href="'+v+'"'+b+">"+w+'</a><span class="related-post-item-summary"><span class="related-post-item-summary-text">'+u+'</span> <a href="'+v+'" class="related-post-item-more"'+b+">"+d.moreText+"</a></span>"+y+"</li>"}else{if(A==3||A==4){c+='<li class="related-post-item" tabindex="0"><a class="related-post-item-title" href="'+v+'"'+b+'><img alt="" class="related-post-item-thumbnail" src="'+r+'" width="'+d.thumbnailSize+'" height="'+d.thumbnailSize+'"></a><div class="related-post-item-tooltip"><a class="related-post-item-title" title="'+t+'" href="'+v+'"'+b+">"+w+"</a></div>"+y+"</li>"}else{if(A==5){c+='<li class="related-post-item" tabindex="0"><a class="related-post-item-wrapper" href="'+v+'" title="'+t+'"'+b+'><img alt="" class="related-post-item-thumbnail" src="'+r+'" width="'+d.thumbnailSize+'" height="'+d.thumbnailSize+'"><span class="related-post-item-tooltip">'+w+"</span></a>"+y+"</li>"}else{if(A==6){c+='<li><a class="related-post-item-title" title="'+t+'" href="'+v+'"'+b+">"+w+'</a><div class="related-post-item-tooltip"><img alt="" class="related-post-item-thumbnail" src="'+r+'" width="'+d.thumbnailSize+'" height="'+d.thumbnailSize+'"><span class="related-post-item-summary"><span class="related-post-item-summary-text">'+u+"</span></span>"+y+"</div></li>"}else{c+='<li><a title="'+t+'" href="'+v+'"'+b+">"+w+"</a></li>"}}}}}s.innerHTML=c+="</ul>"+y;d.callBack()};randomRelatedIndex=h;showRelatedPost=g;j(d.homePage.replace(/\/$/,"")+"/feeds/posts/summary"+e+"?alt=json-in-script&orderby=updated&max-results=0&callback=randomRelatedIndex")})(window,document,document.getElementsByTagName("head")[0]);
//]]>			  
</script>
</b:if>

  </body>
</html>
