
# Front End Development - HTML


HTML   - Building blocks
CSS    - Design (colours, fonts, empty space)
JS     - Functions



HTML:

.html
Headings - H1, H2, H3, [etc], P
Defines structure, including tab title (metadata)

```HTML
<html>
	<head>
		<meta charset="UTF-8">
		<title>Patrick's Profile</title>

		Put metadata and trackers in here
		eg Google Analytics, Hotjar
		Import JS, font colours, tab logos

		<meta name="description" content="Descriptive text regarding Patrick">

		<link rel="stylesheet" type="text/css" href="css.md">    <-- CSS

	</head>
	<body>
		<h1>Heading</h1>
		<h2>Sub-heading</h2>
		<h3>Sub-sub-heading</h3>

		<p>Paragraphs</p>
		
		<h4>Ordered Lists</h4>
		<ol>
			<li>List item 1</li>
			<li>List item 2</li>
			<li>List item 3</li>
		</ol>

		<h4>Unordered Lists</h4>
		<ul>
			<li>List item</li>
			<li>List item</li>
			<li>List item</li>
		</ul>

		<h3>Hyperlinks</h3>
		<a href="https://www.poetryfoundation.org/poems/46560/dulce-et-decorum-est">Contents of Link </a>

		<h3>Images</h3>
		<p>Self-closing tag, no contents</p>
		<img src="Location of image" alt="Description to help Google bot understand" style="border-width: 2 px; border-colour: grey; border: solid">

		<form action="">
			<input type="text" name="">
			<input type="email" name="" id="">
			<input type="password" name="" id="">
			<input type="submit" name="" id="">
		</form>

		<table>
			<tr>
				<td><img src="photo location"></td>
				<td>
					<h3>Photo title</h3>
					<p>Photo description Photo description Photo description Photo description Photo description Photo description Photo description Photo description Photo description</p>
				</td>
			</tr>
		</table>


	</body>
</html>
```

- charset UTF-8 (Unicode) is this keyboard type, most widely used
- <body> is for content
- Indentation vital
- Hyperlinks are known in HTML as Anchors
- HREF is an attribute of the anchor tag: <a href=""></a>
- In image tag, alt= is for visually impared users, or to help bots understand images <-- more realistically
- It is possible to create new tags using HTML, not common
- Using tables allows you to have photos horizontal to text, and other uses.