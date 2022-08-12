<style>

html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
main_content,
video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font-family: "Lucida Console", -apple-system, Monaco,
    "Bitstream Vera Sans Mono", Terminal, monospace, BlinkMacSystemFont,
    "Segoe UI", Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue",
    sans-serif;
}
/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}

ol,
ul {
  list-style: none;
}
blockquote,
q {
  quotes: none;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
  content: "";
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}

* {
  margin: 0;
  padding: 0;
}
	
	
body {
  color: white;
	 background: url(https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/bd_type1_citycrop.jpg) no-repeat center center fixed; 
  font-family: -apple-system, Monaco, "Bitstream Vera Sans Mono",
    "Lucida Console", Terminal, monospace, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
  line-height: 1.5;
   -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

iframe {
  margin: 0px;
  padding: 0px;
  background-image: url("https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/bd_type1_car.jpg");
  border: none;
}

p
{
  background-image: url("https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/halfscreen-black.gif");
}
	
img {
  padding: 0px;
  margin: 0px;
  width: 100%;
}

h2,
h1,
h3 {
  color: white;
  background: transparent
    url(https://raw.githubusercontent.com/ThakaRashard/bubblegumpop/gh-pages/img/halfscreen-gray.gif)
    center repeat;
  font-family: "Helvetica Neue", "Bitstream Vera Sans Mono", sans-serif, -apple-system, Monaco, 
    "Lucida Console", Terminal, monospace, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen-Sans, Ubuntu, Cantarell;
  font-weight: 900;
  padding: 0px;
  margin: 0px;
  text-align: left;
  font-variant-caps: small-caps;
  text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 20px #fff, 0 0 40px #0ff,
    0 0 80px #0ff, 0 0 90px #0ff, 0 0 100px #0ff, 0 0 150px #0ff;
}

h2 {
font-weight: 900;
font-family: "Helvetica Neue", sans-serif, "Lucida Console", Terminal;
padding: 0px;
margin: 0px;
text-align: left;

}
.firstcharacter {
  color: #fff;
  text-shadow: 0 0 7px #fff, 0 0 10px #fff, 0 0 21px #fff, 0 0 42px #0fa,
    0 0 82px #0fa, 0 0 92px #0fa, 0 0 102px #0fa, 0 0 151px #0fa;
  font-family: -apple-system, Monaco, "Bitstream Vera Sans Mono",
    "Lucida Console", Terminal, monospace, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
  float: left;
  font-size: 75px;
  line-height: 60px;
  padding-top: 7px;
  padding-right: 8px;
  padding-left: 3px;
}

.neonText {
  color: #fff;
  text-shadow: 0 0 7px #fff, 0 0 10px #fff, 0 0 21px #fff, 0 0 42px #0fa,
    0 0 82px #0fa, 0 0 92px #0fa, 0 0 102px #0fa, 0 0 151px #0fa;
  font-family: -apple-system, Monaco, "Bitstream Vera Sans Mono",
    "Lucida Console", Terminal, monospace, BlinkMacSystemFont, "Segoe UI",
    Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
}

.storyBox {
  width: 100%;
  position: relative;
  display: flex;
}

.storyBox .card {
  position: relative;
  cursor: pointer;
}

.storyBox .card .face {
  width: 100%;
  height: 200px;
  transition: 0.5s;
}

.storyBox .card .face.face1 {
  position: relative;
  background: #333;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 1;
  transform: translateY(100px);
}

.storyBox .card:hover .face.face1 {
  background: #00c2ff;
  transform: translateY(0);
}

.storyBox .card .face.face1 .storycontent {
  opacity: 0.2;
  transition: 0.5s;
}

.storyBox .card:hover .face.face1 .storycontent {
  opacity: 1;
}

.storyBox .card .face.face1 .storycontent img {
  max-width: 100px;
}

.storyBox .card .face.face1 .storycontent h3 {
  margin: 10px 0 0;
  padding: 0;
  color: #fff;
  text-align: center;
  font-size: 1.5em;
}

.storyBox .card .face.face2 {
  position: relative;
  background: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
  box-sizing: border-box;
  box-shadow: 0 20px 50px rgba(0, 0, 0, 0.8);
  transform: translateY(-100px);
}

.storyBox .card:hover .face.face2 {
  transform: translateY(0);
}

.storyBox .card .face.face2 .storycontent p {
  margin: 0;
  padding: 0;
}

.storyBox .card .face.face2 .storycontent a {
  margin: 15px 0 0;
  display: inline-block;
  text-decoration: none;
  font-weight: 900;
  color: #333;
  padding: 5px;
  border: 1px solid #333;
}

.storyBox .card .face.face2 .storycontent a:hover {
  background: #333;
  color: #fff;
}

	
.some-page-wrapper {
  margin: 15px;
  background-color: ##23b2ff;
}

.row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 100%;
}

.column {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 1;
  overflow: hidden;
}

.double-column {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 2;
  overflow: hidden;
}

.blue-column {
  background-color: #23ff32;
  
}

.green-column {
    
    background-color: #c9ff23;
}	
	/* ------------------------------------------- */	
	
	
.twoPanelSpread {
  margin: 0px;
  padding: 0px;
  background: url( https://i.giphy.com/media/ddZXIrimeaXY0xclfC/giphy.webp )
    center repeat;
}

.row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 100%;
}

.panelColumn {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 1;
  overflow: hidden;
}

.leftColumn {
  background-color: #2470ff;
  width: 100%;
}

.leftColumn img {
  flex-shrink: 0;
  min-width: 100%;
  min-height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.rightColumn {
  background-color: #c9ff23;
}
.rightColumn img {
  flex-shrink: 0;
  min-width: 100%;
  min-height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}
a:hover {
  color: #c9ff23;
}

.divAlbumReview {
  background-image: url("https://m.media-amazon.com/images/I/41QKR5BJVZL.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  padding: 50px;
  clear: both;
  margin: 0px;
  border-bottom: 0px dashed #c9ff23;
  font-size: 20px;
  color: white;
  font-family: Monaco, "Bitstream Vera Sans Mono", "Lucida Console", Terminal,
    monospace;
}

.pdivAlbumReview {
  background: rgba(255, 108, 35, 0.5);
}

.broken-width {
  width: 100%;
}

.right-width {
  min-width: 100%;
}

audio {
  -webkit-transition: all 0.5s linear;
  -moz-transition: all 0.5s linear;
  -o-transition: all 0.5s linear;
  transition: all 0.5s linear;
  -moz-box-shadow: 2px 2px 4px 0px #006773;
  -webkit-box-shadow: 2px 2px 4px 0px #006773;
  box-shadow: 2px 2px 4px 0px #006773;
  -moz-border-radius: 7px 7px 7px 7px;
  -webkit-border-radius: 7px 7px 7px 7px;
  border-radius: 7px 7px 7px 7px;
}

audio:hover,
audio:focus,
audio:active {
  -webkit-box-shadow: 15px 15px 20px rgba(0, 0, 0, 0.4);
  -moz-box-shadow: 15px 15px 20px rgba(0, 0, 0, 0.4);
  box-shadow: 15px 15px 20px rgba(0, 0, 0, 0.4);
  -webkit-transform: scale(1.05);
  -moz-transform: scale(1.05);
  transform: scale(1.05);
}

#row_image  {
border: 5px solid #ccc;
background: #666;
  max-width: 100%;
  padding: 50px;
  background-image: url("https://www.whosampled.com/static/track_images_100/mr11753_2010108_73251697983.jpg");
  background-repeat: repeat;
	}

	
.gallery {
  width: 100%;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  border-radius: 50%;
  box-shadow:
    inset 0 0 50px #fff,
    inset 20px 0 80px ##FFF300,
    inset -20px 0 80px #0AFF00,
    inset 20px 0 300px ##FFF300,
    inset -20px 0 300px #0AFF00,
    0 0 50px #fff,
    -10px 0 80px #FFF300,
    10px 0 80px #0AFF00;
  
}
.image {
  width: 100px;
  flex: 1 0 auto;
}
.featured-image {
  flex: 0 0 100%;
}

/* GiTHUB_LOGO##TEAM_SPiRiT!!! */

	/* IMAN_FRUM_SOMALiA_MY_MOMMA */
.pinupGallery {
  width: 100%;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
   object-fit: contain;
}
.pinupImage {
  width: 100px;
  flex: 1 0 auto;
}
.featured-pinupImage {
  flex: 0 0 100%;
}	
	
/* General presentation stuff */
.post-content {
	max-width: 100%;
	margin: 0 auto;
}

/* img {	max-width: 100%; }  ###MAY_BE_BREAKING_SOME_SOME_IMAGES */

/* Set content grid so it respects order values */
.post-content {
	display: grid;
}

/*
Style image if there is an image right after the heading
Use order to put it above the heading
Relative position for absolute caption
*/
.post-content h1 + .kg-image-card {
	margin: 0 -24px;
	order: -1;
	position: relative;
}


/* Style image's caption if there is an image right after the heading */
.post-content h1 + .kg-image-card figcaption {
	bottom: 0;
	left: 0;
	right: 0;
	padding: 1rem 1rem 1.2rem;
	opacity: 0.5;
	background: white;
}
	
/* FLEX_BOX_FOR_3_IMAGES */
.flex-container {

    display: flex;
     align-items: stretch; 
     flex-flow: row nowrap;  
    flex-direction: row; 
    flex-wrap: nowrap; 
    justify-content: center;
    align-content: stretch;
    height: 100%;
    padding: 15px;
    gap: 5px;

  }

  .flex-container > div{
   
    border: 1px solid #c9ff23;
    border-radius: 1px;
    padding: 8px;
  }




	
	
</style>

## Hole To Another Universe

## DEAR_MUWA##OH_HOW_I_MISS_YOU ##
```
1 # HOLE_TO_ANOTHER_UNiVERSE##############################
2 # TO####################################################
3 # ANOTHER###############################################
4 # UNiVERSE##############################################
```

<iframe width="100%" height="601" src="https://www.youtube.com/embed/FJZ-BHBKyos" title="[HD] Greatest Hollywood Car Chase of All Time - Bullitt (1968)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="100%" height="601" src="https://www.youtube.com/embed/TYw-xygF5Pc" title="775 hp Supercharged Bullitt Mustang Steve McQueen Edition from Steeda" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<img src="https://github.com/ThakaRashard/BUBBLEGUMPOP_MUNA/blob/master/assets/images/muna_i_wanna_BULLiT_LiKE_JEFFS7.PNG">
<img src="https://raw.githubusercontent.com/ThakaRashard/BUBBLEGUMPOP_MUNA/master/assets/images/muna_i_wanna_BULLiT_LiKE_JEFFS.PNG">

```
1 # HOLE_TO_ANOTHER_UNiVERSE##############################
2 # TO####################################################
3 # ANOTHER###############################################
4 # UNiVERSE##############################################
```

		{% highlight ruby %}
1 # HOLE_TO_ANOTHER_UNiVERSE##############################
2 # TO####################################################
3 # ANOTHER###############################################
4 # UNiVERSE##############################################
{% endhighlight %}

---
layout: default
---

Text can be **bold**, _italic_, ~~strikethrough~~ or `keyword`.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
