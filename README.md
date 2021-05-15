# New_controls_demo_html

We can see some controls with the help of code .........


lets look into the code below,,,,,



<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8"/>
	<title>New controls example</title>
</head>
<body>
	<form action="." oninput="range_control_value.value=range_control.valueAsNumber">
		<p>
			Name:<input type="text" name="name_control" autofocus required><br>
			Email:<input type="email" name="email_control" required><br>
			URL:<input type="url" name="url_control" placeholder="enter the url of website"><br>
			Date:<input type="date" name="date_control"><br>
			Time:<input type="time" name="time_control"><br>
			Date and time of Birth:<input type="datetime" name="datetime_control"><br>
			Month:<input type="month" name="month_control"><br>
			Week:<input type="Week" name="week_control"><br>
			Number (min -10 max 10):<input type="number" min="-10" max="10" value="0"><br>
			Range(min 0 max 10):<input type="range" name="range_control" min="0" max="10" value="0"><output for="range_control" name="range_control_value"></output><br>
			Telephone:<input type="tel" name="tel_control"><br>
			Search term:<input type="search" name="search_control"><br>
			Favourite color:<input type="color" name="color_control"><br>
			<input type="submit" value="Submit!">
		</p>
	</form>

</body>
</html>
