# Front End Development - CSS:

HTML   - Building blocks
CSS    - Design (colours, fonts, empty space)
JS     - Functions


## CSS:		Cascading Style Sheets

.css
Edits structure, by definitions

First step: link to style sheet
	<link rel="stylesheet" type="text/css" href="css.md">

Uses selector methods:


```CSS
Select {

}
_____________________________________________
Using HTML tag selector:

h1 {
	font-size: 30px
}

h1, h2 {
	colour: #EA545B
	text-align: center
}

body, p {
	colour: rgb(30,30,30);
	font-family: 'serif';
	font-size: 20px;
	background-colour: rgb(230, 230, 230)
}
_____________________________________________

```

### Colours / Text:
	- Hexidecimals (#D92027)
	- RGB (218, 58, 47)
	- RGBA (218, 58, 47, 0.5)
		- Opacity ie gray scale

Choose one colour, use a gray scale, avoid full black backgrounds / text

- Colour Hunt
- Coolors.co
- Extension

Text:
- Font Ninja


## Box model / Divs

- Section areas made using <div> </div> (divides)
- Classes created from this:	<div class="Hobbies">
- Padding around objects

<div class="section-white">
</div>

Box Model:
	- Margin
	- Border
		- General rule: Subtle is better for border radius / shadow
	- Padding
	- Content


### Class selectors:

dot notation

```CSS
.section-white{
	background-colour: white;
}

```