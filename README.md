* {
	box-sizing: border-box;
}

html,
body {
	height: 100%;
}

body {
	margin: 0px;
	padding: 0px;
	background: #404040;
	font-family: 'Quicksand', sans-serif;
	font-size: 12pt;
	font-weight: 400;
	color: #000000;
}


h1,
h2,
h3 {
	margin: 0;
	padding: 0;
	color: #404040;
}

p,
ol,
ul {
	margin-top: 0;
}

ol,
ul {
	padding: 0;
	list-style: none;
}

p {
	line-height: 180%;
}


a {
	color: #ff8a0e;
}

a:hover {
	text-decoration: none;
}

img {
	max-width: 100%;
	height: auto;
}


.container {
	margin: 0px auto;
	width: 1200px;
}

.title {
	margin-bottom: 3em;
}

.title h2 {
	font-size: 2.8em;
}

#header-wrapper {
	overflow: hidden;
	padding: 10em 0em 10em 0em;
	background: url(../images/bg01.jpg) repeat-x center top;
	border-bottom: 20px solid rgba(0, 0, 0, .5);
}

#logo h1 {
	display: inline-block;
	margin-bottom: 0.20em;
	padding: 0.20em 0.9em;
	background: #000;
	font-size: 3.5em;
	color: #ff8a0e;
}

#logo a {
	text-decoration: none;
	color: #FFF;
}

a.downloadnow-btn {
	display: inline-block;
	padding: 1.3em 1.5em;
	text-decoration: none;
	font-size: 0.90em;
	font-weight: 600;
	text-transform: uppercase;
	outline: 0;
	color: #FFF;
	background: #ff8a0e;
	border-radius: 30px;
}


.about_section {
	background: #ffb86c;
	padding: 50px 15px;
}

.about_taital {
	font-size: 50px;
	color: #090807;
	line-height: 55px;
	font-weight: bold;
	padding: 0;
	text-transform: uppercase;
	margin-bottom: 20px;
}

p.about_text {
	color: #030303;
	font-size: 17px;
	line-height: 28px;
	font-weight: 500;
}

.row {
	display: -ms-flexbox;
	display: flex;
	-ms-flex-wrap: wrap;
	flex-wrap: wrap;
	margin-right: -15px;
	margin-left: -15px;
}

.col-md-6 {
	width: 50%;
	padding: 0 15px;
}

.classified-row {
	align-items: flex-start;
	margin-bottom: 15px;
}

.classified_box1 {
	width: 20%;
}

.classified_box2 {
	width: 70%;
}

.classified .classified_box span {
	color: #141629;
	display: block;
	font-size: 54px;
	font-weight: bold;
	text-align: center;
}

.blu2 {
	color: #f9f9f9;
	font-weight: bold;
}

.classified .classified_box .fornt h3 {
	color: #030303;
	font-size: 20px;
	line-height: 28px;
	font-weight: 700;
	padding-bottom: 10px;
}

.classified .classified_box .fornt p {
	color: #030303;
	font-size: 18px;
	line-height: 27px;
	font-weight: 500;
}

.slider-section {
	padding: 100px 0;
}

.slick-slide {
	height: auto;
}

.sliderimg {
	padding: 0 10px;
}

.slick-slide img {
	width: 350px;
	border: 2px solid #000;
	border-radius: 14px;
}

.slick-slider .slick-arrow {
	border: solid #FFF;
	border-width: 0 3px 3px 0;
	display: inline-block;
	margin-top: -10px;
	padding: 3px;
}

.slick-slider .slick-arrow::before {
	content: none;
}

.slick-slider .slick-next {
	transform: rotate(-45deg);
}

.slick-slider .slick-prev {
	transform: rotate(135deg);
}

.slick-prev,
.slick-next {
	position: absolute;
	display: block;
	height: 20px;
	width: 20px;
	line-height: 0px;
	font-size: 0px;
	cursor: pointer;
	background: transparent;
	color: transparent;
	top: 50%;
	-webkit-transform: translate(0, -50%);
	-ms-transform: translate(0, -50%);
	transform: translate(0, -50%);
	padding: 0;
	border: none;
	outline: none;
}

.slick-prev:hover,
.slick-next:hover,
.slick-prev:focus,
.slick-next:focus {
	outline: none;
	background: transparent;
	color: transparent;
}

.slick-prev:hover:before,
.slick-next:hover:before,
.slick-prev:focus:before,
.slick-next:focus:before {
	opacity: 1;
}

.slick-prev.slick-disabled:before,
.slick-next.slick-disabled:before {
	opacity: 0.25;
}

.slick-prev:before,
.slick-next:before {
	font-family: "slick";
	font-size: 20px;
	line-height: 1;
	color: white;
	opacity: 0.75;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	/* Icons */
}

@font-face {
	font-family: 'slick';
	font-weight: normal;
	font-style: normal;
	src: url('../fonts/slick.eot');
	src: url('../fonts/slick.eot?#iefix') format('embedded-opentype'), url('../fonts/slick.woff') format('woff'), url('../fonts/slick.ttf') format('truetype'), url('../fonts/slick.svg#slick') format('svg');
}

.slick-prev {
	left: -25px;
}

[dir="rtl"] .slick-prev {
	left: auto;
	right: -25px;
}

.slick-prev:before {
	content: "â†";
}

[dir="rtl"] .slick-prev:before {
	content: "â†’";
}

.slick-next {
	right: -25px;
}

[dir="rtl"] .slick-next {
	left: -25px;
	right: auto;
}

.slick-next:before {
	content: "â†’";
}

[dir="rtl"] .slick-next:before {
	content: "â†";
}

/* Dots */
.slick-dotted .slick-slider {
	margin-bottom: 30px;
}

.slick-dots {
	list-style: none;
	display: block;
	text-align: center;
	padding: 0;
	margin: 30px 0 0;
	width: 100%;
}

.slick-dots li {
	position: relative;
	display: inline-block;
	height: 20px;
	width: 20px;
	margin: 0 5px;
	padding: 0;
	cursor: pointer;
}

.slick-dots li button {
	border: 0;
	background: transparent;
	display: block;
	height: 20px;
	width: 20px;
	outline: none;
	line-height: 0px;
	font-size: 0px;
	color: transparent;
	padding: 5px;
	cursor: pointer;
}

.slick-dots li button:hover,
.slick-dots li button:focus {
	outline: none;
}

.slick-dots li button:hover:before,
.slick-dots li button:focus:before {
	opacity: 1;
}

.slick-dots li button:before {
	position: absolute;
	top: 0;
	left: 0;
	content: "â€¢";
	width: 20px;
	height: 20px;
	font-family: "slick";
	font-size: 40px;
	line-height: 20px;
	text-align: center;
	color: #fff;
	opacity: 1;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}

.slick-dots li.slick-active button:before {
	color: #ffb86c;
	opacity: 1;
}

.signin-section {
	background-color: #fff;
	padding: 50px 0;
	text-align: center;
}

.btn {
	display: inline-block;
	margin: 15px 10px;
	height: 50px;
	min-width: 200px;
	padding: 5px 30px;
	font-size: 15px;
	border-radius: 30px;
	background-size: 300% 100%;
	-moz-transition: all .4s ease-in-out;
	-o-transition: all .4s ease-in-out;
	-webkit-transition: all .4s ease-in-out;
	transition: all .4s ease-in-out;
}

.btn1 {
	background-image: linear-gradient(to right, #29323c, #485563, #2b5876, #4e4376);
	box-shadow: 0 4px 15px 0 rgba(45, 54, 65, 0.75);
	color: #fff;
}

.btn2 {
	color: #fff;
	background-image: linear-gradient(to right, #fc6076, #ff9a44, #ef9d43, #e75516);
	box-shadow: 0 4px 15px 0 rgba(252, 104, 110, 0.75);
}

.btn3 {
	background-image: linear-gradient(to right, #009245, #FCEE21, #00A8C5, #D9E021);
	box-shadow: 0 4px 15px 0 rgba(83, 176, 57, 0.75);
	color: #fff;
}

.btn:hover {
	background-position: 100% 0;
	-moz-transition: all .4s ease-in-out;
	-o-transition: all .4s ease-in-out;
	-webkit-transition: all .4s ease-in-out;
	transition: all .4s ease-in-out;
}

.contact-img {
	max-width: 100%;
}

#copyright {
	overflow: hidden;
	padding: 10px 15px;
	text-align: center;
}

#copyright p {
	text-transform: uppercase;
	font-size: 15px;
	color: #fff;
	margin: 0;
}
