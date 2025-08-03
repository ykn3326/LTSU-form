# LTSU-form
<html>
    <head>
        <title>Hospital</title>
    </head>
    <body>
        <h1>Yogesh Hospital</h1>
        <h2>Patient Registration Form</h2>
        <h3>General Chekup Form</h3>
        <hr><hr><hr>
        <br><br>
        <form action ="VS cod.php">
        <label for = "name">  Name : </label>
        <input type = "text">
        <br>
        <br>
        <label for = "addresss">Address : </label>
        <input type ="text" name="address" id="address">
        <br>
        <br>
        <label for="password">Enter your password : </label>
        <input type="password" id="password" name="password">
        <br><br>
        <label>Contact</label>
        <input type="number">
        <br>
        <br>
        <label for="email">Email : </label>
        <input type="email" id="email" name="email">
        <br><br>
        <label for="gender">Gender : </label>
        <label for="male">male</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="female">female</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="gender">other :</label>
        <input type="radio" id="other" name="gender" value="other">
        <br><br>
        
        <label for ="bloodgroup">blood group : </label>
        <input type="text" list="bloodgroup" name="bloodgroup" id="bloodgrooup">
        <datalist id="bloodgroup">
            <option value="A+">A+</option>
            <option value ="B-">B-</option>
            <option value="O+">O+</option>
        </datalist>
        <br><br>
        <label for="dob">date of birth : </label>
        <input type="date" id="dob" name="dob">
        <br><br>
        <label for="time">time of form submission : </label>
        <input type="time" id="time" name="time">
        <br><br>
        <label for="color">favorite color : </label>
        <input type="color" id="color" name="color">
        <br><br>
        <label for="file">past record file : </label>
        <input type="file" id="file" name="file">

        <br><br>
        
        <button type="submit">submit</button>
       
  </form>
    </body>
</html>
