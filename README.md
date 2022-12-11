# blood-donation-website-on-html
using html and css i created a website
<html> 
<head> 

<title>blood donation</title> 

<style type="text/css"> 
#topbar{ 

height: 40px; 
display: flex; 
justify-content: center; 
margin-right: 142.5px; 

} 

body{ 

margin: 0px; 
padding:0px; 
font-family:Arial,Helvetica,sans-serif; 
} 



#topbar-section{ 

float: left; 
border-left: 1px grey solid; 
height: 100%; 

border-right: 1px grey solid; 
} 

.text{ 

float: left; 
border-right: 1px grey solid; 
} 

.text-styling{ 

float: left; 
margin:13px 20px 8px 20px; 
font-size: 90%; 
} 

#redbar{ 

height: 58px; 
background-color:BB1919; 
} 

#title{ 

float: left;  
font-weight: 400; 
color: #FFFFFF; 
font-family: ReithSans, Arial, Helvetica, freesans, sans-serif; 
font-size: 15px; 
margin-left:10px; 
display: flex; 
align-content: center; 


} 

.form{ 

float: right; 
color: white; 

} 

.form label,.form input,.form button{ 
margin-right: 5px; 
margin-top: 20px; 
} 

.main{ 
display: flex; 
flex-direction: row; 
align-content: center; 
justify-content: center; 
font-family: ReithSans, Arial, Helvetica, freesans, sans-serif; 
font-stretch: 100%; 
} 

.find{ 
height: 250px; 
width: 30vw; 
background-color: azure; 
margin: 10px; 
padding: 20px; 
display: flex; 
flex-direction: column; 
} 

.find label{ 
margin-bottom: 3px; 
} 
.find select{ 
margin-bottom: 7px; 
} 
.image{ 
height: 290px; 
width: auto; 
margin: 10px 
} 
.image img{ 
height: 100%; 
width: auto; 
} 

.process{ 
display: flex; 
flex-direction: row; 
justify-content: center; 



} 
.pro{ 
width: 61vw; 
background-color: #fafafa; 
padding: 10px; 
} 
.location{ 
display: flex; 
justify-content: center; 
margin: 10px; 

} 
.where{ 
background-color: #fafafa; 
padding: 10px; 
width: 61vw; 
display: flex; 
flex-direction: column; 
justify-content: center; 
align-content: center; 

} 
.text2{ 
display: flex; 
justify-content: center; 
margin: 10px; 
} 
.textarea{ 
background-color: #fafafa; 
padding: 10px; 
width: 61vw; 

} 
.text a{ 
color: black; 
} 
.text a:hover{ 
color: #1ABC9C; 
} 

</style> 

</head> 

<body> 

<div id="redbar"> 

<p id="title">BloodBank.com<br>A Social Initiative</p> 

<form class="form"> 

<label for="username">Donor Login</label> 
<input name="username" type="text" placeholder="Username"> 
<label for="password">Password</label> 
<input name="password" placeholder="Password" type="password"> 
<button type="submit">Login</button> 

</form> 

</div> 



<div id="topbar"> 

<div class="text"> 

<a href=""><p class="text-styling"><b> Register</b></p></a> 

</div> 

<div class="text"> 

<a href=""><p class="text-styling"><b>Why Donate Blood</b></p></a> 

</div> 

<div class="text"> 

<a href=""><p class="text-styling"><b>Who Can Give Blood</b></p></a> 

</div> 

<div class="text"> 

<a href=""><p class="text-styling"><b>Refer a Friend</b></p></a> 

</div> 

<div class="text"> 

<a href=""><p class="text-styling"><b>Contact Us</b></p></a> 

</div> 

</div> 

<section class="main"> 

<div class="find"> 

<h3>Find a Donor</h3> 
<label for="state">State</label> 
<select name="state" id="state" class="form-control"> 
<option value="Andhra Pradesh">Andhra Pradesh</option> 
<option value="Andaman and Nicobar Islands">Andaman and Nicobar Islands</option> 
<option value="Arunachal Pradesh">Arunachal Pradesh</option> 
<option value="Assam">Assam</option> 
<option value="Bihar">Bihar</option> 
<option value="Chandigarh">Chandigarh</option> 
<option value="Chhattisgarh">Chhattisgarh</option> 
<option value="Dadar and Nagar Haveli">Dadar and Nagar Haveli</option> 
<option value="Daman and Diu">Daman and Diu</option> 
<option value="Delhi">Delhi</option> 
<option value="Lakshadweep">Lakshadweep</option> 
<option value="Puducherry">Puducherry</option> 
<option value="Goa">Goa</option> 
<option value="Gujarat">Gujarat</option> 
<option value="Haryana">Haryana</option> 
<option value="Himachal Pradesh">Himachal Pradesh</option> 
<option value="Jammu and Kashmir">Jammu and Kashmir</option> 
<option value="Jharkhand">Jharkhand</option> 
<option value="Karnataka">Karnataka</option> 
<option value="Kerala">Kerala</option> 
<option value="Madhya Pradesh">Madhya Pradesh</option> 
<option value="Maharashtra">Maharashtra</option> 
<option value="Manipur">Manipur</option> 
<option value="Meghalaya">Meghalaya</option> 
<option value="Mizoram">Mizoram</option> 
<option value="Nagaland">Nagaland</option> 
<option value="Odisha">Odisha</option> 
<option value="Punjab">Punjab</option> 
<option value="Rajasthan">Rajasthan</option> 
<option value="Sikkim">Sikkim</option> 
<option value="Tamil Nadu">Tamil Nadu</option> 
<option value="Telangana">Telangana</option> 
<option value="Tripura">Tripura</option> 
<option value="Uttar Pradesh">Uttar Pradesh</option> 
<option value="Uttarakhand">Uttarakhand</option> 
<option value="West Bengal">West Bengal</option> 
</select> 

<label for="city">City</label> 
<select name="city" id="city" class="form-control"> 
<option value="Andhra Pradesh">Lucknow</option> 
<option value="Andaman and Nicobar Islands">Prayagraj</option> 
<option value="Arunachal Pradesh">Kanpur</option> 
<option value="Assam">Bengaluru</option> 
<option value="Bihar">Kolkata</option> 
<option value="Chandigarh">Mumbai</option> 
<option value="Chhattisgarh">Jaipur</option> 
<option value="Dadar and Nagar Haveli">Amritsar</option> 
<option value="Daman and Diu">Chandigarh</option> 
<option value="Delhi">Ghaziabad</option> 
<option value="Lakshadweep">Noida</option> 
<option value="Puducherry">Bhopal</option> 
<option value="Goa">Patna</option> 
<option value="Gujarat">Ahmedabad</option> 
<option value="Haryana">Surat</option> 
<option value="Himachal Pradesh">Dehradun</option> 
<option value="Jammu and Kashmir">Haridwar</option> 
<option value="Jharkhand">Kota</option> 
<option value="Karnataka">Varanasi</option> 
<option value="Kerala">Kanyakumari</option> 
<option value="Madhya Pradesh">Riwa</option> 
<option value="Maharashtra">Kolhapur</option> 
<option value="Manipur">Trivendram</option> 
<option value="Meghalaya">Tirupati</option> 
<option value="Mizoram">Surathkal</option> 
<option value="Nagaland">Kalicut</option> 
<option value="Odisha">Puri</option> 
<option value="Punjab">Jalandhar</option> 
</select> 

<label for="group">Group</label> 
<select name="group" id="group" class="form-control"> 
<option value="Andhra Pradesh">A+</option> 
<option value="Andaman and Nicobar Islands">B+</option> 
<option value="Arunachal Pradesh">AB+</option> 
<option value="Assam">A-</option> 
<option value="Bihar">B-</option> 
<option value="Chandigarh">AB-</option> 
<option value="Bihar">O+</option> 
<option value="Chandigarh">O-</option> 
</select> 

<button type="submit">Search</button> 


</div> 

<div class="image"> 
<img src="donate blood.jpg"> </div> 

</section> 

<section class="process"> 
<div class="pro"> 
<h4 style="text-align: center;">Donation Process</h4> 
<p>The entire process of donating whole blood (that is, blood with all component cells) takes about 1 hour. Blood donors must be at least 17 years old (16 in some places with consent of a parent or guardian) and weigh at least 110 pounds (50 kilograms). In addition, they must be in good health. Their pulse, blood pressure, and temperature are measured, and a blood sample is tested to check for low blood count (anemia). Donors are asked a series of questions about their health, factors that might affect their health, and countries they have visited. Certain conditions and factors can permanently or temporarily disqualify people from donating blood. Disqualifying factors typically are those that might make donation dangerous for the donor or risk transmitting a disorder to the recipient. The decision to accept or disqualify a donor can be complicated.</p> 
</div> 
</section> 

<section class="location"> 

<div class="where"> 
<div > 
<h4 style="display: block;">Where do you want to donate?</h4> 
</div> 
<div> 
<select name="city" id="city" class="form-control"> 
<option value="Andhra Pradesh">Lucknow</option> 
<option value="Andaman and Nicobar Islands">Prayagraj</option> 
<option value="Arunachal Pradesh">Kanpur</option> 
<option value="Assam">Bengaluru</option> 
<option value="Bihar">Kolkata</option> 
<option value="Chandigarh">Mumbai</option> 
<option value="Chhattisgarh">Jaipur</option> 
<option value="Dadar and Nagar Haveli">Amritsar</option> 
<option value="Daman and Diu">Chandigarh</option> 
<option value="Delhi">Ghaziabad</option> 
<option value="Lakshadweep">Noida</option> 
<option value="Puducherry">Bhopal</option> 
<option value="Goa">Patna</option> 
<option value="Gujarat">Ahmedabad</option> 
<option value="Haryana">Surat</option> 
<option value="Himachal Pradesh">Dehradun</option> 
<option value="Jammu and Kashmir">Haridwar</option> 
<option value="Jharkhand">Kota</option> 
<option value="Karnataka">Varanasi</option> 
<option value="Kerala">Kanyakumari</option> 
<option value="Madhya Pradesh">Riwa</option> 
<option value="Maharashtra">Kolhapur</option> 
<option value="Manipur">Trivendram</option> 
<option value="Meghalaya">Tirupati</option> 
<option value="Mizoram">Surathkal</option> 
<option value="Nagaland">Kalicut</option> 
<option value="Odisha">Puri</option> 
<option value="Punjab">Jalandhar</option> 
</select> 
<button type="submit">Submit</button> 
</div> 

</div> 

</section> 
<section class="text2"> 
<div class="textarea"> 
<textarea style="width: 60vw;height: 50px;" placeholder="Give Feedback"></textarea> 
</div> 
</section> 



</body> 


</html>
