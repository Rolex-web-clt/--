# --<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
    <form action="submit.php" method="post">
        <h1>Login Form</h1>
            <h4>All option are Mandatary</h4>
        <fieldset>
            <legend>Fillup your personal Id</legend><br>
            
         <div class="container">
            <div class="group">
            <label for="FirstName">FirstName:</label>
            <input type="text" name="fname" id="fname" placeholder="Enter your First name"><br><br>
</div>
<div class="group1">
            <label for="LastName">LastName:</label>
            <input type ="text" name="Lname" id="lname" placeholder="Enter your LastName"><br><br></div>
            <div class="group2">
            <label for="email">Email:</label>
            <input type ="text" name="email"id="email" placeholder="Enter your email address"><br><br>
            </div>
            <div class="group3">
            <label for="gender">Gender:</label><br>
            <input type="radio" name="gender" value="male" id="Male">
            <label for="male">Male</label>
            <input type="radio" name="gender" id="Female" value="Female" >
            <label for="female"> Female</label>
            <input type="radio" name="gender" id="Others" value="Others">
            <label for="others">Others</label><br><br></div>
            <div class="group4">
            <label for="country">Country:</label>
             <select country="Name">
                <option >Selected country</option>
                <option>Nepal</option>
                <option>USA</option>
                <option>INDIA</option>
             </select><br><br></div>
             <div class="group5">
            
              <label for="bio">Bio:</label><br>
                 <textarea rows="4"cols="50">
            </textarea></div>
            <br><br>
            <div class="group6">
            <input type="submit" value="Submit">
         </div>

             




         </div>



        </fieldset>






    </form>

    
</body>
</html>
