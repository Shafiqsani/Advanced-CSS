
# Lab 05: Advanced CSS

## Introduction:
Students have learned advanced concepts of CSS3, media queries, and responsive web design. In this lab, student will practically design a responsive web page using the concepts learned in the lectures. 

## Lab Objectives:
The objective of this lab is to help students in designing a responsive web page using divisions, CSS3, and media queries.  Students will apply different CSS styles and responsive web designing concepts they have learned in the lectures to design the layout of a web page.

## Tools:
Dreamweaver, notepad, browser.
## Helping Material:
* Lecture slides.
* W3Schools: 	https://www.w3schools.com/html/html_responsive.asp 
* https://www.w3schools.com/Css/css_rwd_intro.asp  
* Plenty of DIV examples: http://www.mobilefish.com/tutorials/css/css_quickguide_div_examples_containers.html 

 


### Lab Task 1:
 
In the previous labs, you have designed a website which is similar to BBC’s website using tables and divisions. Designing the layout of a website using tables and divisions alone is non-trivial due to limited flexibility, layout distortions, and an inability to response against the change in screen size (e.g. browser’s window resized). Professional websites like BBC are designed using HTML5 and CSS3. The responsiveness of the BBC website can be observed by resizing browser’s window. When carefully observing this layout, one can easily see that there are three different layouts which are adapted whenever the screen size is changed. The three layouts are: a) smart phone layout, b) tablet layout, and c) desktop layout.



#### Your Task:
Design a responsive web page which has a layout similar to the BBC’s website. Your layout must be based on DIVs and CSS3. There must be three different layouts for the smart phone, tablet, and desktop. The layouts must be adapted automatically upon a relevant change in the screen size. An RWD example is already uploaded on LMS. You should use it as an example and extend it to design a responsive web page which is similar to BBC’s web site.
Hints
1.	Feel free to browse BBC’s website and look into its page source to see how the layout is designed.
2.	You can change the color scheme as per your choice. 
3.	BBC’s website has a menu (More) and a search bar. You can skip both in your layout.
4.	You are encouraged to use most of the HTML tags and CSS styles you have learned so far or even new tags, which you can learn from W3Schools.
5.	Make good use of HTML colors, fonts, font-family, font-sizes and other styles for the look and feel of the web page.
6.	Make sure to test your website with different resolutions by changing the resolution of your screen.

#### CODE:
```
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8" content="width=device-width, initial-scale=1.0">
     <link rel="stylesheet" href="style.css">
    <title>BBC Home</title>
  </head>
  <body>
      <div class="nav-bar">
        <div class="left-side">
          <div class="link">
              <a href="">  <img class="bbc"  src="./b.gif" alt=""> </a>
          </div>
          <div class="link">
            <a href="">  <img class="sign"  src="./sign1.png" alt=""> </a>
          </div>
          <div class="link">
            <a href="">Home</a>
          </div>
          <div class="link">
            <a href="">News</a>
          </div>
          <div class="link">
            <a href="">Sport</a>
          </div>
          <div class="link">
            <a href="">Reel</a>
          </div>
          <div class="link">
            <a href="">Worklife</a>
          </div>
          </div>
        </div>
<div class="image-first">
  <img  src="./adv.png" class="responsive" alt="">
</div>
<div class="int">
  <div class="wb">
    <b><h3>  Welcome to BBC.com</h3></b>
  </div>
<div class="dat">
  <h3 id="dt">Saturday,20 March</h3>
</div>
</div>
<br>
<br><br>
<div class="five-images">
  <div class="col-6 col-s-12 image-first">
<img  src="./va.png" class="responsive" alt="">
  </div>
<div class="col-3 col-s-12 sec-img">
  <div class="sc">
    <img src="./c.png" alt="">
  </div>
<div class="sc">
  <img src="./d.png" alt="">
</div>
</div>
<div class="col-3 col-s-12 thr-img">
  <div class="tr" style="border-bottom:2px solid white;padding-right:2px">
    <img class=thrid src="./e.png" alt="">
  </div>
  <div class="th">
    <img src="./f.png" alt="">
  </div>
</div>
</div>
<div class="News">
  <h2><mark>|</mark> News</h2>
</div>

  <div class="sc">
    <div class="col-4 col-s-12">
      <a href="#"><img src="./i.png" alt=""></a>
    </div>
    <div class="col-4 col-s-12">
        <a href="#"><img src="./q.png" alt=""></a>
    </div>
    <div class="col-4 col-s-12">
      <a href="#"><img src="./h.png" alt=""></a>
    </div >
  </div>
  <hr>
  <div class="Sports">
    <h2><mark>|</mark> Sports</h2>
  </div>
  <div class="sc">
    <div class="col-4 col-s-12">
      <a href="#"><img src="./j.png" alt=""></a>
    </div>
    <div class="col-4 col-s-12">
      <a href="#"><img src="./k.png" alt=""></a>
    </div>
    <div class="col-4 col-s-12">
      <a href="#"><img src="./l.png" alt=""></a>
    </div>
  </div>
<br><br>
<div class="weather">
  <img src="./m.png" class="responsive" alt="">
</div>
<br><br>
<div class="Asia News">
  <h2><mark>|</mark>Asia News</h2>
</div>
<div class="sc">
<div class="col-3 col-s-12">
  <a href="#"><img src="./n.png" alt=""></a>
</div>
<div class="col-3 col-s-12">
  <a href="#"><img src="./p.png" alt=""></a>
</div>
<div class="col-3 col-s-12">
  <a href="#"><img src="./q.png" alt=""></a>
</div>
<div class="col-3 col-s-12">
  <a href="#"><img src="./i.png" alt=""></a>
</div>
</div>
<hr>
<div class="video">
  <div class="Editors-Pick">
    <h2><mark>|</mark>Feature video</h2>
  </div>
  <div class="video" >
    <iframe width=100% height=720 src="https://www.youtube.com/embed/tgbNymZ7vqY?autoplay=1"></iframe>
  </div>
</div>
<div class="image-first">
  <img  src="./last.png" class="responsive"  alt="">
</div>

  </body>
</html>
CSS:
body{
  font-family: "Montserrat",sans-serif;
  margin: 0px;

}


.left-side{
  display: flex;

}
.responsive {
  width: 100%;
  max-width: 100%;
  height: auto;
}
mark {
    background: none;
    color: red;
  }
.nav-bar>.left-side> div{
	width:100%;
	height:30px;
	padding-top: 10px;
  border: 1px solid white;
	background-color: black;
	color: white;
	text-align:center;
}
.bbc{
  width: 60px;
  height: 20px;
}
.sign{
  width: 70px;
  height: 25px;
}
.link >a{
   padding-top: 5px;
	text-decoration: none;
	color:white;
}
.link> a:hover{
  border-bottom: 3px solid yellow;
}
.int{
	padding: 20px;
}
.wb{
	font-weight: bold;
	float: left;
	color: darken;

}
.dat{
	color: brown;
	float: right;
}

a:hover{
  opacity: 0.9;
}
.five-images{
  max-width: 100%;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  padding-left: 15px;
  padding-right: 15px;
  content: "";
  clear: both;
  display: table;
}
.five-images>div{
  border: 3px solid white;
}
.first-image>img{
  max-width: 100%;
  height: auto;
}
.sec-img{
  display: flex;
  flex-direction: column;

}
.thr-img{
  display: flex;
  flex-direction: column;

}
.sec-img>div{
  border: none;
  flex:1;
}
.sec-img>div>img{
  width: 100%;
  height:100%;
}

.thr-img>div>img{
  width: 100%;
  height:100%;

}
.thr-img>div{
  border:none;
  flex: 1;
}


.first-image{

flex:2;

}
.sec-img{
flex: 1;

}
.thr-img{
flex: 1;
}
.news{
  width: 100%;
}
.ne{
  width: 100%;
  display: flex;
}
.ne>div{
  flex:1;
}
.ne>div>a>img{
  width: 100%;
  height:100%;

}
.sp{
  width: 100%;
  display: flex;
  content: "";
  clear: both;
}
.sp>div{
  flex: 1;
}
.sp>div>a>img{
  width: 100%;
  height:100%;

}
.an{
  width: 100;
  display: flex;
  align-content: center;

}
.an>div{
border: 2px solid white;
  flex:1;
}
.an>div>a>img{
  width: 100%;
  height:100%;

}
.video{
  border="0" align = "center"
}
.picks{
  background-color: white;
}
.images{
  display: flex;
}
.images>div{

}

.r-y{
  flex:2;
}
.r-y>img{
  width:100%;
}
.y-img{

  flex:1;

}
.y-img>img{
  padding-right: 2px;
  float: right;
}
.t-v{
  display: flex;
}
.t-v>div{
  flex:1;
}
.t-v>div>img{
  width:100%;
}
*{
  box-sizing: border-box;
}
[class*="col-"] {
	width: 100%;
}
@media only screen and (max-width: 600px) {
  /* For tablets: */
  .col-s-1 {width: 8.33%;}
  .col-s-2 {width: 16.66%;}
  .col-s-3 {width: 25%;}
  .col-s-4 {width: 33.33%;}
  .col-s-5 {width: 41.66%;}
  .col-s-6 {width: 50%;}
  .col-s-7 {width: 58.33%;}
  .col-s-8 {width: 66.66%;}
  .col-s-9 {width: 75%;}
  .col-s-10 {width: 83.33%;}
  .col-s-11 {width: 91.66%;}
  .col-s-12 {width: 100%;}
  body {
    background-color: blue;
  }
}
@media only screen and (min-width: 600px) {
  /* For desktop: */
  .col-1 {width: 8.33%;}
  .col-2 {width: 16.66%;}
  .col-3 {width: 25%;}
  .col-4 {width: 33.33%;}
  .col-5 {width: 41.66%;}
  .col-6 {width: 50%;}
  .col-7 {width: 58.33%;}
  .col-8 {width: 66.66%;}
  .col-9 {width: 75%;}
  .col-10 {width: 83.33%;}
  .col-11 {width: 91.66%;}
  .col-12 {width: 100%;}
  body {
    background-color: white;
  }
}

[class*="col-"] {
	float: left;
	padding: 5px;
}

.row::after {
	content: "";
	clear: both;
	display: block;
}


```
![alt text](https://i.ibb.co/ZThLQvF/5.png)
