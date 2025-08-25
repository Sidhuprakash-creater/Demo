# Basic Terminology
1.Browser:-It as an application or a software i.e is used to communicate with the server that is present around the world wide(www.)
2.WEBSITE:-It is a collection of related webpage.
3.WEBPAGE:-It is a collection of Html,Css,javascript,PHp,xml etc.
4.DOMAIN NAME:-It is the name given for website.
5.URL:-It is uniform resource locator.
6.HTTP:-It is a protocol used for communication between client and server.
       -It is known as hyper text transfer protocol.
##HTML :-
-It stand for Hyper Text Markup Language.
-It is a markup language used to create and raw element like image,text,audio,forms etc in web pages.
-Html is also known as collection of static web pages.
## STRUCTURE OF HTML :-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

--<!DOCTYPE html>--
-Declares the DOCUMENT TYPE as HTML5.
_<html lang="en">
Root element of the Html document,specifying the language as English.
<head>
Contain metadata about the document.
<meta charset="UTF-8">
-Specifies the character encoding for the document as UTF-8.
-UTF-8 ->is a character encoding standard that supports a wide range of language and characters.
<meta name="viewport" content="width=device-width, initial-scale=1.0">
-controls the zooming and scaleing of the web page on different devices.
 <title>Document</title>
 -sets the title of webpage appearing in the browser's title bar and search engine results.
 <body>
 -Body contains the content of html documents.
 
 # BASIC TAGS OF HTML :->
# Heading Tags-
-Iit is used to create text in bolder & bigger size compare to normal text.
-It has 6 types of heading tags:- h1,h2,h3,h4,h5,h6.
-h1 is the highest heading tag and h6 is the lowest heading tag.

## Paragraph tags:-
-it is used to create text in normal size.
<p></p>

## Break Tag:-
-It is a single tag used to create a line break.
-it breaks the line and moves the crusor to the next line.
<br>
## Horizontal tag:-
-It is a single tag used to create a horizontal line.
-it breaks the line and move the crusor to next line but before moving the crusor to the next line,it creates horizontal line through out the page.
<hr>
## span tag:-<span></span>
-it is used to create text or block of text.
-it is inline element.
##Basic Styles in Html :-
1. bgcolor:-It is used to change in the background of the page.
2.text:-It is used to change the text color of the page.
3.align:-it is used to align the content of the page.(left,right,center)
# Note:- All the above properties used inside the tag.
## Text Styles in Html:-
<i> it is used to create a italic text
<em> it is used to create a emphasized text
<u>it is used to create a underline text
- <b> it is used to create bold text.
<ins> it is used to create a insert / underline text
<del> it is used to create a delete text
<sub> it is used to create a subscript text
<sup> it is used to create a superscript text
<mark> it is used to create a marked text
<small> it is used to create a small text
<big> it is used to create a big text

## pre tag :- <pre>....</pre>
-it is used to display the structure of element the way they are created to code edition

## Multimedia tags in HTML :- 
multimedia tags are used to add images , vedios ,audio etc in html.
## image tag :-
<img> image tag is used to display a image on a web page

## Attributes / properties:-
1.src :- it is used to specify the source of image
2. alt :-it is use to specify the alternative text of the image
3.height :- it is used to specify the height of the image 
4. width it is used to specify the width of the image

## syntax
<img src="image url" alt ="alt name">

## audio tag 
audio tag is used to display a audio in a web page

## attributes /properties
1src :-it is used to specified the source of audio
2control:- it gives option to play/pause , playback speed ,volume etc.
3 preload :- it is used to specify the preload of the audio(metadata,)

## syntax
<audio src="audio url " control preload ="metadata"></audio>

## vedio tag

<vedio>tag is used to display a vedio on a web page

## ifeame tag :-
-iframe stands for inline frame where we can use <iframe> tag to display the contain of website on our website.

syntax :- <iframe src="url" width="width" height="height" frameholder="0" >

## Hyperlink in HTML:-
-Anchor tag-- <a> it is used to create a hyperlink reference that navigates to another web page or section of the same page.

1. href :- stand for hyperlink refeerence . it is used to specify the destination of the hyperlink
2. target :- it is used to specifiy the target of the hyperlink(_self,_blank)
_self :- it is used to open the hyperlink in the same tab.
_blank :-it is used to open the hyperlink in a new tab

syntax :- <a href ="url" target ="_blank">link text</a>

## List :-
in html a list is a structured way to display a collaction of item . there are 3types of list available in html.

i. orderlist (ol)
ii. Un-orderlist(ul)
iii. Definition list (dl)

## i. Ordered list(ol) :-
-it is a type of list , the structurieses the element is the some specific order,either assending or dessending
-<ol> tag is to create order list.
<ol type ="i" start ="10">
# Attributes :-
type :- It is used to specify the type of the ordered list.(1,a,A,i).
start :- Starting index e.g :- start = 5. it starts the list from particular position
e.g:-
## un-ordered list(ul)
 -<ul> tag is to create ordered list.
 - Un-ordered list can not specify the type of the order items.

 #Attribute:-
 type- disc/circle/square
 e.g:-
  <ul type="circle">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
 </ul>

 ## Defination list:- <dl>.....</dl>
 -It is used to create a number of defination text &their description & meaning.
 -<dl>tag is used to create defination list.
 -<dd>...</dd> & <dt>...</dt> tags are used to create defination description and  defination text respectively.
 e.g-