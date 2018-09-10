<!DOCTYPE html>
<html>
	
	<head>
		
		<style>
			
			.outer
			{
				height:auto; width:100%;				
			}
			
			.heading
			{
				height:60px;width:100%; background-color:#454545;margin-top:-30px;
			}
			
			.formArea
			{
				height:1000px; width:100%; background-color:#8211;
			}
			
			.formPortion
			{
				    
				   width: 40%;
				   
				   margin-left:40px;
				    padding: 10px;		
			}
			
			.imageDiv{
				
				margin-top:70px;
				margin-right:40px;
				float:right;
				background-color:blue;
				height:387px;
				width:46.2%;
			}
			
			.registerbtn {
			    background-color: brown;
			    color: white;
			    padding: 16px 20px;
			    margin: 8px 0;
			    border: none;
			    cursor: pointer;
			    width: 100%;
			    opacity: 0.9;
			}
		</style>
		
	</head>
	
	<body>
		
		<div class="outer">
			
			<div class="heading">
				
				<h1 style="text-align:center;text-family:bodoni;font-size:40px;color:white;">JOIN US</h1>
			</div>
			
			<div class="formArea">
				
				<div class="imageDiv">
					
					<img src="stt.jpg">
				</div>
				
				<div class="formPortion">
					
					<form style="margin-top:20px;">
						
						
						<br><br><br><br><br><br><br>
					
				      NAME: <input type="text" align="left">    <br><br>  
					
					DATE OF BIRTH: <input type="text"> <br><br>
					
					
					COUNTRY:
					
					<select>
						
						<option value="Afganistan">Afganistan</option>
						<option value="Saudi Arabia">Saudi Arabia</option>
					    <option value="India">India</option>
						<option value="China">China</option>
					</select> <br><br>
					
					
					EMAIL: <input type="email"> <br><br>
					
					SELECT GENDER: <br>
					
					<input type="radio" name="gender" value="male" checked> Male <br>
					<input type="radio" name="gender" value="female"> Female <br>
					<input type="radio" name="gender" value="other"> Other <br><br>
					
					SELECT LANGUAGE: <br>
					
					<input type="radio" name="LANGUAGE" value="English" checked> English <br>
					<input type="radio" name="LANGUAGE" value="Hindi" checked> Hindi <br>
					
					<br><br>
					
					<button type="submit" class="registerbtn" name="REGISTER">REGISTER</button>
				</form>
				<br><br>
				
				<h3 style="color:black;text-align:center">Already have an account <a href="#" style="color:brown;">Sign in</a>.</h3>
				</div>
			</div>
			
			
		</div>
	</body>
</html>
