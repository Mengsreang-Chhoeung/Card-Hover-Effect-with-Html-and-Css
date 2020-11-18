### Card-Hover-Effect-with-Html-and-Css
#### Enjoy coding with html and css...

លំហាត់ខាងក្រោមនេះ ទាមទារឲ្យអ្នកមានចំណេះដឹងទាក់ទងនឹង:
- HTML
- CSS
  - Position
  - Transform 2D and 3D
  - Flexbox

# លំហាត់ Card
![Thumbnail](/images/1.jpg)
# កូដ HTML:
```javascript
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<title>Card</title>
	<link rel="stylesheet" type="text/css" href="css/style2.css">
</head>
<body>
	<div class="card">
		<div class="image">
			<img src="images/angkor-wat.JPG" alt="angkor-wat">
		</div>
		<div class="content">
			<h3 class="title">
				Angkor Wat
			</h3>
			<p class="paragraph">
				Angkor Wat is a temple complex in Cambodia and the largest religious monument in the world by land area, on a site measuring 162.6 hectares.
			</p>
			<a href="#" class="btn">See more</a>
		</div>
	</div>
</body>
</html>
```
# កូដ CSS:
```javascript
body{
	margin: 0;
	padding: 0;
	background-color: #dedede;
	display: flex;
	height: 100vh;
	justify-content: center;
	align-items: center;
	font-family: verdana, sans-serif;
}

.card{
	width: 280px;
	height: 400px;
	position: relative;
	overflow: hidden;
}

.card::before{
	content: "";
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background-color: rgba(0,0,0,0.6);
	opacity: 0;
	transition: 1s;
	cursor: pointer;
}

.card:hover::before{
	opacity: 1;
}

.card .image {
	width: 100%;
	height: 100%;
}

.card .image > img {
	width: 100%;
	height: 100%;
	object-fit: cover;
}

.card .content{
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	padding: 20px;
	box-sizing: border-box;
	color: #f6f6f6;
	display: flex;
	flex-direction: column;
	justify-content: flex-end;
	transform: translateY(400px);
	transition: 1s;
}

.card:hover .content{
	transform: translateY(0px);
}

.card .content .title{
	margin: 0;
}

.card .content .btn{
	width: 110px;
	padding: 10px 0px;
	text-align: center;
	background-color: rgba(125,125,125,0.8); 
	color: #f6f6f6;
	text-decoration: none;
	transition: 0.4s;
}

.card .content .btn:hover{
	background-color: #fff; 
	color: #333333;
}
```
[Facebook-MengSreang Channel](https://www.facebook.com/mengsreangchannel)

[Facebook-CodeIsMine](https://www.facebook.com/CodeIsMine)

[YouTube-MengSreang Channel](https://www.youtube.com/channel/UCE6UmKNi-bYNWwOBUYoT-yQ)

[YouTube-CodeIsMine](https://www.youtube.com/channel/UCBKsUkGih9kdXcrz54zNH1w)

### អរគុណច្រើន សំណាងល្អ!🙏
