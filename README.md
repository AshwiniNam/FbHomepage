# FbHomepage
<html>
	<head>

		<title>Facebook</title>

		<style>
		body{
				margin:0;
				padding:0;
				background:linear-gradient(white, #D3D8E8);
				font-family:Helvetica, Arial, sans-serif;
			}

        .header
			{
				background-color:rgb(59, 89, 152);
				height: 12.2%;
				width:100%;
				font-family:tahoma;
				border: 1px solid darkblue;
			}
		.right
			{
				width:45%;
				position:absolute;
				top:16%;
				left:56%;
			}
		.left
			{	
				width:55%;
				top:16%;
				position:absolute;
				left:12.2%;
			}
		.image
			{
				position: relative;
 				background-color: #f5f6f7;
  				width: 180px;
  				display:block
  				margin-left:auto
  				margin-right:auto
 			}
		.registration_form
			{
				background-color:white;
				border: 1px solid rgb(189, 199, 216);
				border-radius:5px;
				font-family:Helvetica, Arial, sans-serif;
				font-size:18px;
				font-weight:400;
				outline-color:rgb(77, 144, 254);
				padding-bottom:8px;
				padding-top:8px;
				padding-left:10px;
				padding-right:10px;
				margin:6px;
			}
		select
			{
				background-color:rgb(221, 221, 221);
				border:1px solid rgb(189, 199, 216);
				font-family:Helvetica, Arial, sans-serif;
				font-size:13px;
				font-weight:400;
				height:30px;
				padding:5px;
				width:56px;
				margin:0;
			}
		#birthday_help
			{
				color:rgb(54, 88, 153);
				font-family:Helvetica, Arial, sans-serif;
				font-size:11px;
				text-decoration-color:rgb(54, 88, 153);
				width:150px;
				display:inline-block;
				text-decoration:none;
			}
		.gender
			{
				color:rgb(29, 33, 41);
				font-family:Helvetica, Arial, sans-serif;
				font-size:18px;
				font-weight:400;
				padding-left:3px;
				padding-right:10px;
				margin-top:30px;
			}
		.terms_and_conditions
			{
				color:rgb(119, 119, 119);
				display:block;
				font-family:Helvetica, Arial, sans-serif;
				font-size:11px;
				margin-top:11px;
				margin-bottom:1px;
				width:316px;
			}
		#submit
			{	
				font-size:18px;
				background-color:rgb(105, 167, 78);
				border:1px solid rgb(59, 110, 34);
				color:white;
				font-family:Freight Sans Bold", Helvetica, Arial, sans-serif;
				padding:20px;
				width:194px;
				text-align:center;
				font-weight:700;
				margin-bottom:10px;
				margin-top:10px;
				text-shadow:rgba(0, 0, 0, 0.5) 0px 1px 2px;
				border-radius:5px;
				height:39px;
			}
		.button
			{
  				background-color: #90949c;
  				border: none;
  				color: white;
  				padding: 10px;
  				text-align: center;
  				text-decoration: none;
  				display: inline-block;
  				font-size: 9px;
  				margin: 2px;
  				cursor: pointer;
				border-radius: 50%;
			}
		.notification
			{
				background-color: #555;
 				color: white;
				text-decoration: none;
  padding: 15px 26px;

  display: inline-block;
  border-radius: 2px;
	background: red;
	position: absolute;
  top: 90px;
  right: 650px;
  padding: 5px 10px;
  border-radius: 50%;
  background-color: red;
  color: white;
}

/* Popup container */
.popup {
  position: relative;
  display: inline-block;
  cursor: pointer;
}

/* The actual popup (appears on top) */
.popup .popuptext {
  visibility: hidden;
  width: 160px;
  background-color: #555;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 8px 0;
  position: absolute;
  z-index: 1;
  bottom: 125%;
  left: 50%;
  margin-left: -80px;
}

/* Popup arrow */
.popup .popuptext::after {
  content: "";
  position: absolute;
  top: 100%;
  left: 50%;
  margin-left: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: #555 transparent transparent transparent;
}

/* Toggle this class when clicking on the popup container (hide and show the popup) */
.popup .show {
  visibility: visible;
  -webkit-animation: fadeIn 1s;
  animation: fadeIn 1s
}

/* Add animation (fade in the popup) */
@-webkit-keyframes fadeIn {
  from {opacity: 0;} 
  to {opacity: 1;}
}

@keyframes fadeIn {
  from {opacity: 0;}
  to {opacity:1 ;}
}
</style>


<script type="text/javascript">
	function buttonclick()
	{
		alert("New Facebook account created");
	}
	function gender()
	{
    var rd1= document.getElementById("rd1");
		var rd2= document.getElementById("rd2");
		var rd3= document.getElementById("rd3");
		if(rd1.checked==false&&rd2.checked==false&&rd3.checked==false)
		{
			alert("Gender not selected")
		}
	}
	function validate()
	{
		var FirstName = document.getElementById("FirstName");
		var LastName = document.getElementById("LastName");
		var email = document.getElementById("email");
		var NewPassword = document.getElementById("NewPassword");
	}

	function myFunction() {
  var popup = document.getElementById("myPopup");
  popup.classList.toggle("show");
}
	

</script>

</head>


<body>

<form> 
  <div class="header">
   <span style="font-size: 45px; position:absolute; left:180px; color:white; top:3.5%;  "> <b> facebook</b> </span>
   
   <span  style="position:absolute; right:575px; color:white; top:2%; font-size:12px;font-family: Helvetica, Arial, sans-serif" >Email or Phone </span>
   <span style="position:absolute; right:425px; color:white; top:2%; font-size:12px;font-family: Helvetica, Arial, sans-serif" type="password" >Password </span>
   

    <div style="position:absolute; right:250px; top:5%;">
      <input type="text" style="width:150px; height:22px; border:0.5px solid black"required></input> &emsp;
      <input type="password" style="width:150px; height:22px; border:0.5px solid black"required></input> &emsp;
      <button  style="background-color:#4267b2; height: 22px; color:white; border:1px solid darkblue; border-radius: 2px;" type="submit"> <b>Log In</b></button><br>
      <a href="#" style="color:#9cb4d8; text-decoration:none; position:relative; left:175px; top:5px;font-size:smaller;">Forgotten account?</a>


    </div>
  </div>
</form>

  <div class="left">
	<span style="color:#333; font-size:36px;direction: ltr;
    line-height: 1.34;display:black;font-family: 'Freight Sans Bold', Helvetica, Arial, sans-serif !important;font-family: inherit;
    font-weight: bold !important;
    letter-spacing: normal;
    text-rendering: optimizelegibility;left:180px;;">Recent logins</span>	<br><br>
	<span style="color:#1d2129; font-size:19px; font-family:Helvetica, Arial, sans-serif,text-align:center;left:180px;;">Click your picture or add an account</span>	<br><br>

	<a href="default.asp">
	<img class="image" src="kash.jpg" alt="Ashwini"/>
	<span class="notification">3</span>
	<span class="notification" style="background-color:white;right:98%;color: rgb(80, 79, 79);">X</span>
  </a>
  <div style=" background-color: #fff;
    border-bottom-left-radius: 4px;
    border-bottom-right-radius: 4px;
    overflow: hidden;
    padding: 12px;
    text-align: center;
    text-decoration: none;
    text-overflow: ellipsis;
    white-space: nowrap;
    width: 157px;color: #4b4f56;font-size: 18px;
    line-height: 22px;display: block;">Ashwini</div>
 </div>

 <a href="default.asp">
	<img style="left:400px; top:115px ;position: relative;" class="image" src="AddAccount.png" alt="AddAccount"/>
  </a>
  <div style=" background-color: #fff;
    border-bottom-left-radius: 4px;
    border-bottom-right-radius: 4px;
    overflow: hidden;
    padding: 12px;
    text-align: center;
    text-decoration: none;
	right:575px;
	left:400px; top:115px ;position: relative;
    text-overflow: ellipsis;
    white-space: nowrap;
    width: 157px;color: #4b4f56;font-size: 18px;
    line-height: 22px;display: block;">Add Account</div>
 </div>

  <form>
  <div class="right">
    <span style="color:#333; font-size:36px; font-family:Helvetica, Arial, sans-serif; font-weight:700; " >Create an account</span><br><br>
    <span style="color:#1d2129; font-size:19px; font-family:Helvetica, Arial, sans-serif;">It's quick and easy.</span>	<br><br>

    <input id="FirstName" class="registration_form" type="text" placeholder="First Name"style="width:180px;"required></input>
    <input id="LastName" class="registration_form" type="text" placeholder="Last Name" style="width:180px;"required></input>
    <input id="email" class="registration_form" type="text" placeholder="Mobile number or email address"style="width:377px;"required></input>
    <input id="NewPassword" class="registration_form" type="password" placeholder="New Password"style="width:377px;"required></input><br><br>
</form>
    <span style="font-family: inherit;color: #90949c;font-size: 16px;font-weight: bold;display: block;direction: ltr;
    line-height: 1.34;">Birthday</span><br>


    <select>
		<option>1</option>
		<option>2</option>
		<option>3</option>
		<option>4</option>
		<option>5</option>
		<option>6</option>
		<option>7</option>
		<option>8</option>
		<option>9</option>
		<option>10</option>
		<option>11</option>
		<option>12</option>
		<option>13</option>
		<option>14</option>
		<option>15</option>
		<option>16</option>
		<option>17</option>
		<option>18</option>
		<option>19</option>
		<option>20</option>
		<option>21</option>
		<option>22</option>
		<option>23</option>
		<option>24</option>
		<option>25</option>
		<option>26</option>
		<option>27</option>
		<option>28</option>
		<option>29</option>
		<option>30</option>
		<option>31</option>
    </select>


    <select>
    <option>Jan</option>
		<option>Feb</option>
		<option>Mar</option>
		<option>Apr</option>
		<option>May</option>
		<option>June</option>
		<option>July</option>
		<option>Aug</option>
		<option>Sep</option>
		<option>Oct</option>
		<option>Nov</option>
		<option>Dec</option>
    </select>


    <select>
		<option>1990</option>
		<option>1991</option>
		<option>1992</option>
		<option>1993</option>
		<option>1994</option>
		<option>1995</option>
		<option>1996</option>
		<option>1996</option>
		<option>1997</option>
		<option>1998</option>
		<option>1999</option>
		<option>2000</option>
		<option>2001</option>
		<option>2002</option>
		<option>2003</option>
		<option>2004</option>
		<option>2005</option>
		<option>2006</option>
		<option>2007</option>
		<option>2008</option>
		<option>2009</option>
		<option>2010</option>
		<option>2011</option>
		<option>2012</option>
		<option>2013</option>
		<option>2014</option>
		<option>2015</option>
		<option>2016</option>
		<option>2017</option>
		<option>2018</option>
		<option>2019</option>
		<option>2020</option>
    </select>
	<div class="popup" onclick="myFunction()"><a class="button" alt="Click for more information." href="#">?</a>
		<span class="popuptext" id="myPopup" style="background-color: white;color: black;">Providing your date of birth helps make sure that you get the right Facebook experience for your age. If you want to change who sees this, go to the About section of your Profile. For more details, please visit our <a>Data Policy.</a></span>
	  </div>
	  <br>
	  <br>
    

		<span style="font-family: inherit;color: #90949c;font-size: 16px;font-weight: bold;display: block;direction: ltr;
	    line-height: 1.34;">Gender</span><br>

    <input id="rd1" type="radio" value="Male" name="gender"><label class="gender">Male</label></input>
    <input id="rd2" type="radio" value="Female" name="gender"><label class="gender">Female</label></input>
		<input id="rd3" type="radio" value="Custom" name="gender"><label class="gender">Custom</label></input>
		<a class="button" href="#">?</a>
		<br>

     <p class="terms_and_conditions">
		By clicking Sign Up, you agree to our Terms, Data Policy and Cookie Policy. You may receive SMS notifications from us and can opt out at any time.
	</p><br>


     <button id="submit" onclick=" gender();buttonclick() ;">Sign Up</button><br>

     <span style="font-family:Helvetica, Arial, sans-serif; color:rgb(102, 102, 102); font-size:13px;font-weight: bold;"><a href="#">Create a Page</a> for a celebrity, band or business. </span>



  </div>


  <div class="footer">
		

  </div>

</body>

</html>
