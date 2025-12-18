 <!DOCTYPE html>
<head>
<html>
<title>Registration Form:</title>
</head>
<body>
<h1>Registration Form:
<form action="#" method="POST">
<fieldset>
<legend><mark>Registration</mark></legend>
<label for="fn">First name</label>
<input 
			type="text"
			id="fn"
			name="fname"
			required
			placeholder="firstname"><br><br>
			
<label for="ln">Last name</label>
<input 
			type="text"
			id="ln"
			name="lname"
			required
			placeholder="lastname"><br><br>
			
<label for="pw">Password</label>
<input 
			type="password"
			id="pw"
			name="pwd"
			required
			placeholder="password"><br><br>
			
<label for="mobile">Mobile number</label>
<input 
			type="tel"
			id="mobile"
			name="mobile"
			required
			placeholder="10 digits number"
			pattern="[0-9]{10}"><br><br>
			
<label for="dob">Date of birth</label>
<input 
			type="date"
			id="dob"
			name="dob"
			required><br><br>
			
<label for="sal">Salary</label>
<input 
			type="number"
			id="sal"
			name="salary"
			required
			placeholder="salary"
			min="10000"
			max="1000000"><br><br>
			
<label for="pic">Upload file:</label>
<input 
			type="file"
			id=" pic"
			name="profile pic"
			required><br><br>
			
<label for="mail">email</label>
<input 
			type="email"
			id="mail"
			name="email"
			required
			placeholder="email"><br><br>
			
<input 
			type="radio"
			id=" male"
			value="male"
			name="gender">
			<label for="male">male</label>
<input 
			type="radio"
			id="female"
			value="female"
			name="gender">
			<label for="female">female</label><br><br>
			
<input 
			type="checkbox"
			id="movie"
			value="watching movies"
			name="movies">
			<label for="movie">Watching movies</label>
<input 
			type="checkbox"
			id="travel"
			value="travelling"
			name="travelling">
			<label for="travel">travelling</label><br><br>
			
<select name="state">
			<option value=""disabled selected>select your state</option>
			<option value="AndhraPradesh">Andhrapradesh</option>
			<option value="Telangana">telangana</option>
			<option value="TamilNadu">tamilnadu</option>
			<option value="Kerala">kerala</option> <br><br>
			 <br>
<input type="submit" value="submit"/>
</fieldset>
</form>
</body>
</html> 
