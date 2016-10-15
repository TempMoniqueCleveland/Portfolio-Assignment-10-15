# Portfolio-Assignment-10-15



//Home.html

<!DOCTYPE HTML>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="mcStylesheet.css">
</head>
<body>
	<header><h1>Monique Cleveland</h1></header>
	<a href= "About.html">About</a>
	<a href= "Contact.html">Contact</a>

	<div class="image1">
	<img src="https://www.google.com/search?q=image+of+roses&rlz=1C1AVNE_enUS666US666&espv=2&biw=1242&bih=566&tbm=isch&imgil=q0mB31-ms_bHxM%253A%253BEkMMIq7iLZKcEM%253Bhttp%25253A%25252F%25252Fwww.hdwallpapers.in%25252Ftag%25252Froses.html&source=iu&pf=m&fir=q0mB31-ms_bHxM%253A%252CEkMMIq7iLZKcEM%252C_&usg=__pl1cURQ-mJO6vK9i4ooiKEyG-5g%3D"></div>

	<div class="image2">
	<img src="https://www.google.com/search?q=image+of+lilies&rlz=1C1AVNE_enUS666US666&espv=2&biw=1242&bih=602&tbm=isch&imgil=SatSw_JjwVQpXM%253A%253BNwFStTkvsxjugM%253Bhttp%25253A%25252F%25252Fgarden.lovetoknow.com%25252Fwiki%25252FLily&source=iu&pf=m&fir=SatSw_JjwVQpXM%253A%252CNwFStTkvsxjugM%252C_&usg=__XBXlkpFhVp4gyoOeQRd3Jtb-RjI%3D"></div>

	<div class="image3">
	<img src="https://www.google.com/search?q=image+of+tulips&rlz=1C1AVNE_enUS666US666&espv=2&biw=1242&bih=602&tbm=isch&imgil=KjguJO3SV_W_OM%253A%253BaZX34jE7NUObDM%253Bhttp%25253A%25252F%25252Fphotographyblogger.net%25252F26-gorgeous-tulip-pictures%25252F&source=iu&pf=m&fir=KjguJO3SV_W_OM%253A%252CaZX34jE7NUObDM%252C_&usg=__hMz9t1QeHYx1qfx5folSztjzZ9g%3D"></div>

	
</body>

</html>

//About.html
<!DOCTYPE HTML>
<html>
	<head>
		<link rel="stylesheet" type="text/css" href="mcStylesheet.css">
	</head>
	<body>
	<a href= "Home.html">Home</a></br>
		<a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwi8t6fDvdnPAhWFOiYKHfYKCLQQFgggMAA&url=http%3A%2F%2Fgrandcircus.co%2F&usg=AFQjCNGbWQum-yfgyXXdVZqtTd_W2pbwKg&bvm=bv.135475266,d.eWE">Grand Circus Detroit</a>
	</body>
</html>


//Contact.html
<!DOCTYPE HTML>
<html>
	<head>
		<link rel="stylesheet" type="text/css" href="mcStylesheet.css">
		<script>
function myFunction() {
    document.getElementById("demo").innerHTML = "See...the words have changed!";
}
</script>
	</head>
	<body>
	<a href= "Home.html"><<< Home</a></br>
		<blockquote>
Now is the time for all good men to come to the aid of our country.
</blockquote>
<ol>
  <li>Roses</li>
  <li>Lillies</li>
  <li>Tulips</li>
</ol>
//Contact form
<form name="htmlform" method="post" action="html_form_send.php">
<table width="450px">
</tr>
<tr>
 <td valign="top">
  <label for="first_name">First Name: </label>
 </td>
 <td valign="top">
  <input  type="text" name="first_name" maxlength="50" size="30">
 </td>
</tr>
 
<tr>
 <td valign="top"">
  <label for="last_name">Last Name: </label>
 </td>
 <td valign="top">
  <input  type="text" name="last_name" maxlength="50" size="30">
 </td>
</tr>
<tr>
 <td valign="top">
  <label for="email">Email:</label>
 </td>
 <td valign="top">
  <input  type="text" name="email" maxlength="80" size="30">
 </td>
 
</tr>
<tr>
 <td valign="top">
  <label for="telephone">Telephone Number: </label>
 </td>
 <td valign="top">
  <input  type="text" name="telephone" maxlength="30" size="30">
 </td>
</tr>
<tr>
 <td valign="top">
  <label for="comments">Comments: </label>
 </td>
 <td valign="top">
  <textarea  name="comments" maxlength="1000" cols="25" rows="6"></textarea>
 </td>
 
</tr>
<tr>
 <td colspan="2" style="text-align:center">
  <input type="submit" value="Submit">   

<p>Changing words.</p>
<button type="button" onclick="myFunction()">Or submit here:</button>
 </td>
</tr>
</table>
</form>

	</body>
</html>

//mcStylesheet.css

body{
	background-color:gray;
}
h1{
	color:white;
}

a{
	color:yellow;
}

p{
	color:yellow;
}

blockquote{
	color:yellow;
}

ol{
	color:red;
}

.image1{
	box-shadow: 10px 10px 5px #888888;
	width:304px;height:228px;
	align:left;
}
.image2{
	width:304px;height:228px;
	align:center;
	
}
.image3{
	box-shadow: 10px 10px 5px #888888;
	width:304px;height:228px;
	align:right;
}

//ms.js

