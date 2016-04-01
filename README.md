

/* Resets
--------------------------------------------------------------------------------*/

ul, ol, li, h1, h2, h3, h4, h5, h6, pre, form, body, html, p, blockquote, 
fieldset, input {
	margin: 0;
	padding: 0;
}

a img {
	border: 0;
}

a {
	text-decoration: none;
}

/* General Styling and Structure
--------------------------------------------------------------------------------*/

body {
	font-family: 'Open Sans', Helvetica, sans-serif;
	background:#242424;
}

.container {
	margin: 0 auto;
	width: 960px;
}

#header-wrap,
#banner-wrap,
#nav-wrap,
#main-wrap,
#footer-wrap,
#total-wrapper
{
        width:100%;
		min-width:960px;
}

#banner-wrap,
#main-wrap,
#footer-wrap,
#total-wrapper
{
		background:#fff;
}

p a, h2 a, .blog-comments-bottom a {
	color: #6d8c5f;
	border-bottom:1px solid #a4be99;
}

p a:hover, h2 a:hover, .blog-comments-bottom a:hover {
	color: #375529;
	border-bottom:1px solid #859f7a;
}

h2 {
	font-size:17px ;
	padding: .5em 0 0.8em 0;
	letter-spacing:1px;
	line-height: 1.2;
	font-weight:600;
	color: #373737;
}

h2 a {
	color: #373737;
}

p {
	font-size: 13px;
	line-height: 180%;
	color:#464646;
	padding: .5em 0;
}
blockquote {
	font-style:italic;
	border-left:4px solid #161F14;
	margin:10px 0 10px 0;
	padding-left:20px;
	line-height:1.8;
	font-size:13px;
	color:#999;
}
#wsite-content {
	min-height:500px;
}

/* Header
--------------------------------------------------------------------------------*/

.top-background {
	background: #161F14;
	width:100%;
	height:500px;
	position:relative;
	min-width:960px;
	
	background-image: url(forest.jpg); 
	background-position:50% 0;
	background-repeat:no-repeat;
	background-attachment: fixed;
}

#icontent .top-background, /* in the editor */
.wsite-custom-background.top-background { /* custom background */
	background-attachment: scroll;
}

.wsite-custom-background .top-background-image {
	display: none !important;
	visibility: hidden !important;
}

.cross {
	width:700px;
	height:500px;
	background:url(cross.png) no-repeat;
	position:absolute;
	left:50%;
	margin-left:-350px;
	z-index:0;
}

#header-wrap {}

#logo,
#logo a {
    color:#fff;
	font:500 50px 'Open Sans', sans-serif;
	text-transform:uppercase;
	letter-spacing:5px;
	z-index:2;
	position:relative;
}

#logo a:hover {}

#header {
	border-collapse: collapse;
	border-spacing: 0;
	width:100%;
	float:left;
	height:40px;
	margin-top:5px;
	position:relative;
	z-index:4;}

#header td {
	vertical-align: middle;
	text-align: left;
}

#logo {
	text-align:center;
}

#header-right {}

#header-right table {
	float: right;
	width: 1px;
}

#header-right td {
	padding: 0;
}


/* Centered header
--------------------------------------------------------------------------------*/

.header-align-outer {
	display: table; 
	#position: relative; 
	overflow: hidden;
	height:485px;
	padding-bottom:15px;
}

.header-align-mid {
	#position: absolute; 
	#top: 50%;
	display: table-cell; 
	vertical-align: middle;
}

.header-align-inner {
	#position: relative; 
	#top: -50%;
}
/* Header: Phone Number
--------------------------------------------------------------------------------*/

#header-right .phone-number .wsite-text {
	color: #fff;
	font-size: 14px;
	font-weight: 600;
	display: block;
	white-space: nowrap;
	position:relative;
}

#header-right .phone-number .wsite-text a {}
#header-right .phone-number .wsite-text a:hover {}

/* Social Links
--------------------------------------------------------------------------------*/


.wsite-social-item {
	width: 23px;
	height: 23px;
	margin: 0 0 0 3px;
	background-image:url(social-light.png);
}
#footer-wrap .wsite-social-item {
	background-image:url(social-black.png);
}
.wsite-social-facebook {background-position:0 0;}
	.wsite-social-facebook:hover {background-position:0 -23px;}
	.wsite-social-facebook:active {background-position:0 -46px;}
.wsite-social-pinterest {background-position:-23px 0;}
	.wsite-social-pinterest:hover {background-position:-23px -23px;}
	.wsite-social-pinterest:active {background-position:-23px -46px;}
.wsite-social-twitter {background-position:-46px 0;}
	.wsite-social-twitter:hover {background-position:-46px -23px;}
	.wsite-social-twitter:active {background-position:-46px -46px;}
.wsite-social-linkedin {background-position:-69px 0;}
	.wsite-social-linkedin:hover {background-position:-69px -23px;}
	.wsite-social-linkedin:active {background-position:-69px -46px;}
.wsite-social-mail {background-position:-92px 0;}
	.wsite-social-mail:hover {background-position:-92px -23px;}
	.wsite-social-mail:active {background-position:-92px -46px;}
.wsite-social-rss {background-position:-115px 0;}
	.wsite-social-rss:hover {background-position:-115px -23px;}
	.wsite-social-rss:active {background-position:-115px -46px;}
.wsite-social-flickr {background-position:-138px 0;}
	.wsite-social-flickr:hover {background-position:-138px -23px;}
	.wsite-social-flickr:active {background-position:-138px -46px;}
.wsite-social-plus {background-position:-161px 0;}
	.wsite-social-plus:hover {background-position:-161px -23px;}
	.wsite-social-plus:active {background-position:-161px -46px;}
.wsite-social-vimeo {background-position:-184px 0;}
	.wsite-social-vimeo:hover {background-position:-184px -23px;}
	.wsite-social-vimeo:active {background-position:-184px -46px;}
.wsite-social-yahoo {background-position:-207px 0;}
	.wsite-social-yahoo:hover {background-position:-207px -23px;}
	.wsite-social-yahoo:active {background-position:-207px -46px;}
.wsite-social-youtube {background-position:-230px 0;}
	.wsite-social-youtube:hover {background-position:-230px -23px;}
	.wsite-social-youtube:active {background-position:-230px -46px;}

#header-right .wsite-social {
	vertical-align: middle;
	margin-left:10px ;
}

#header-right .wsite-social-item {
	width: 32px;
	height: 32px;
	margin: 0 0 0 3px;
	background-image:url(social.png);
  -webkit-transition: background 0.5s ease-out;  /* Safari 3.2+, Chrome */
     -moz-transition: background 0.5s ease-out;  /* Firefox 4-15 */
       -o-transition: background 0.5s ease-out;  /* Opera 10.5–12.00 */
          transition: background 0.5s ease-out;  /* Firefox 16+, Opera 12.50+ */
}

#header-right .wsite-social-rss {background-position:-158px 0;}
#header-right .wsite-social-linkedin {background-position:-79px 0;}
#header-right .wsite-social-facebook {background-position:0px 0; }
#header-right .wsite-social-twitter {background-position:-40px 0;}
#header-right .wsite-social-mail {background-position:-119px 0;}
#header-right .wsite-social-pinterest {background-position:-277px 0;}
#header-right .wsite-social-youtube {background-position:-395px 0;}
#header-right .wsite-social-plus {background-position:-237px 0;}
#header-right .wsite-social-flickr {background-position:-198px 0;}
#header-right .wsite-social-vimeo {background-position:-316px 0;}
#header-right .wsite-social-yahoo {background-position:-356px 0;}

#header-right .wsite-social-rss:hover {background-position:-158px -40px;}
#header-right .wsite-social-linkedin:hover {background-position:-79px -40px;}
#header-right .wsite-social-facebook:hover {background-position:0px -40px; }
#header-right .wsite-social-twitter:hover {background-position:-40px -40px;}
#header-right .wsite-social-mail:hover {background-position:-119px -40px;}
#header-right .wsite-social-pinterest:hover {background-position:-277px -40px;}
#header-right .wsite-social-youtube:hover {background-position:-395px -40px;}
#header-right .wsite-social-plus:hover {background-position:-237px -40px;}
#header-right .wsite-social-flickr:hover {background-position:-198px -40px;}
#header-right .wsite-social-vimeo:hover {background-position:-316px -40px;}
#header-right .wsite-social-yahoo:hover {background-position:-356px -40px;}



/* Header: Search Box
--------------------------------------------------------------------------------*/

#header-right .search {}

#header-right .wsite-search {
	margin-left:15px;
	vertical-align: middle;
}

#header-right .wsite-search-input {
	width: 200px;
	border:0 ;
	line-height:20px;
	height:20px;
	border-radius:4px;
	font-family: ;
	color: #fff;
	background:url(opaque-white.png);
}

#header-right .wsite-search-button {
	position: absolute;
	width: 13px;
	height: 13px;
	top:7px;
	right:7px;
	background:url(search.png) no-repeat ;
}

/* Navigation
--------------------------------------------------------------------------------*/

#nav-wrap {position:absolute; top:0;}

#nav-wrap .nav-container {
	float:right;
	position:relative;
	left:-50%;
	text-align:left;
	margin-top:10px;
	z-index:2;
}

#nav-wrap .nav-container  ul{
	list-style:none; 
	position:relative;
	left:50%;
	z-index:2;
}

#nav-wrap .nav-container  li{float:left;position:relative;}

#nav-wrap .nav-container a{
	text-decoration:none;
	font:bold 18px 'Josefin Sans', sans-serif;
	text-transform:uppercase;
	margin:10px 15px;
	float:left;
	color:#fff;
	padding:1px 2px;
	text-align:center;
	white-space:nowrap;

}
#nav-wrap .nav-container a:hover{border-bottom:1px dashed #fff; padding-bottom:0;}
#nav-wrap .nav-container li#active a {border-bottom:1px solid #fff; padding-bottom:0;}
#nav-wrap {overflow:hidden}/* hide horizontal scrollbar*/

/* Navigation Submenu's
--------------------------------------------------------------------------------*/


#wsite-menus .wsite-menu {
	background:#fff;
}

#wsite-menus .wsite-menu li {
	border:none;
}

#wsite-menus .wsite-menu li a {
	border-left:none;
	border-right:none;
}

#wsite-menus .wsite-menu li a:hover {
	color: #6d8c5f;
	background:#fff ;
}

/* Main Content
--------------------------------------------------------------------------------*/

#main-wrap .container {
	padding:50px 0;
}

.blog-post .blog-separator {display:none;}

.blog-post .blog-header {
	margin-bottom:20px !important;
}

.blog-sidebar h2 {
	padding:1em 0 .3em;
}

.blog-sidebar h2.blog-author-title {
	padding:0 0 0.3em;
}

h2.blog-title, .blog-post .blog-header h2.blog-title {padding-bottom:5px !important;}
h2.blog-title a, .blog-post .blog-header h2.blog-title a { border:none;}



/* Universal banner
--------------------------------------------------------------------------------*/

#banner-wrap {
	background:#f2f2f2;
	padding:30px 0;
}

/* Page type: Tall header
--------------------------------------------------------------------------------*/

.tall-header-page #banner {}

.tall-header-page .wsite-header {
	width: 960px;
	height: 300px;
	background: url(banner-tall.jpg) no-repeat;
}

/* Page type: Short header
--------------------------------------------------------------------------------*/

.short-header-page #banner {}

.short-header-page .wsite-header {
	width: 960px;
	height: 200px;
	background: url(banner-short.jpg) no-repeat;
}

/* Page type: No header
--------------------------------------------------------------------------------*/

.no-header-page .wsite-header  {
        display:none;
}

/* Page type: Landing page
--------------------------------------------------------------------------------*/

.landing-page #banner {
	padding: 0;
}

#bannerleft {
	float: right;
	width: 400px;
}

.landing-page .wsite-header {
	width: 400px;
	height: 300px;
	background: url(banner-landing.jpg) no-repeat;
}

#bannerright {
	float:left ;
	width: 500px;
	height:300px;
}

#bannerright h2 {
	font-size:25px; 
	font-weight:300;
	padding: 0px;
	line-height: 25px;
}

#bannerright p {
	padding: 20px 0px;
	line-height: 140%;
}

#bannerright .wsite-button {}

.landing-banner-outer {
	display: table; 
	#position: relative; 
	overflow: hidden;
}

.landing-banner-mid {
	#position: absolute; 
	#top: 50%;
	display: table-cell; 
	vertical-align: middle;
}

.landing-banner-inner {
	#position: relative; 
	#top: -50%;
}

/* Footer
--------------------------------------------------------------------------------*/

#footer-wrap {
	background:#242424;
	padding:50px 0;
	color:#eee;
	float:left;
}

#footer-wrap .container {}

#footer-wrap .container h2 {
	color: #fff;
}

#footer-wrap .container p {
	color:#ccc;
}

#footer-wrap a {border-bottom:none;}

#footer-wrap blockquote {border-left-color:#666;}

#footer-wrap .container  .wsite-form-container {
	margin-top:0 !important;
}

#footer-wrap .container .weebly-footer, #footer-wrap .container .weebly-footer a, #weeblyfootertext {color:#fff; text-align:right;}
#footer-wrap .container .weebly-footer, #weeblyfootertext {float:right; text-transform:uppercase; font-size:14px; font-weight:600;}

#footer-wrap .container .wsite-form-input, #footer-wrap .container .wsite-search-element-input  {
	border:1px #333 solid;
	background:#222;
	color:#fff;
}

/* Form Customization
--------------------------------------------------------------------------------*/

.wsite-form-label {
	display: inline-block;
	font-size: 14px;
}

.form-radio-container {
	font-size: 13px;
}

.wsite-form-input, .wsite-search-element-input {
	border:1px #ccc solid;
	background:none;
	border-radius:2px;
	padding:7px 5px !important;
}

.form-select {}

/* Buttons
--------------------------------------------------------------------------------*/

/* Small structure & regular style */

.wsite-button {
	display: inline-block;
	padding: 7px 12px;
	background: #333;
	text-transform:uppercase;
	border-radius:2px;
}

.wsite-button:hover {
	background: #000;
}

.wsite-button:active {
	background: #222;
}

.wsite-button-inner {
	color: #fff !important;
	padding: 0;
	background: none !important;
	font: 500 18px 'Open Sans', sans-serif;
	height:auto;
	letter-spacing:1px;
}

/* Large structure & regular style  */

.wsite-button-large {
	color: #fff !important;
	padding: 5px 20px;
}

.wsite-button-large:hover {
	background: #000;
}

.wsite-button-large:active {
	background: #222;
}

.wsite-button-large .wsite-button-inner {
	background: none !important;
	padding:0;
	height:auto;
}

.wsite-button-large:hover .wsite-button-inner {
	background: none !important;
}

.wsite-button-large:active .wsite-button-inner {
	background: none !important;
}


/* Highlighted styles */

.wsite-button-highlight {
	background: #161F14;
}

.wsite-button-highlight:hover {
	background: #6d8c5f;
}

.wsite-button-highlight .wsite-button-inner {
	background: none;
}

.wsite-button-large .wsite-button-highlight {
	background: #161F14;
}

.wsite-button-large .wsite-button-highlight .wsite-button-inner {
	background: none;
}

.wsite-button-large.wsite-button-highlight {
	background: #161F14;
}

.wsite-button-large.wsite-button-highlight:hover {
	background: #6d8c5f;
}

.wsite-button-highlight:active {
	background: #375529;
}

.wsite-button-large.wsite-button-highlight:active {
	background: #375529;
}
