# video.html


<!DOCTYPE html>
<html lang="en">
<meta charset="utf-8">
<head>
	<title>Media/embedding: Task2</title>
	<link rel="stylesheet" type="text/css" href="4sytle.css">
</head>
<body>
	<h1>Video embed</h1>
	<video controls loop autoplay muted>
	    <source src="mediasamples/rabbitmp4.mp4" type="video/mp4">
		<source src="mediasamples/rabbitwebm.webm" type="video/webm">
		<p>Your broswer doesn't support HTML5 video. Here is a <a href="rabbitmp4.mp4">link to the video</a> instead.</p>
	</video>
</body>
</html>


(4STYLE.CSS)


body {
	background-color: #fff;
	color: #333;
	font: 1em / 1.4 Helvetica Neue, Helvetica, Arial, sans-serif;
	padding: 1em;
	margin: 0;
}

* {
	box-sizing: border-box;
}

video {
	border: 1px solid black;
	width: 320px;
	height: 240px;
