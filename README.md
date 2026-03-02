# Day-4
html project registration form.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration form</title>
</head>
<body>
    <form action="#">
        <div class="container" style="display: block; height: 550px; width: 380px; border: 1px solid black; margin: auto;">
            <header style="text-align: center; background-color: rgba(245, 245, 237, 0.911);">
                <h1><b>Student Registration Form</b></h1>
            </header>
            <div class="box" style="display: flex; justify-content:center;">
                 <div class="box1" style="margin-right: 20px;">
                    <label for=""><b>First Name :</b></label><br>
                    <input type="text" id="first name" name="first name" placeholder="Enter the first Name" required/>
                    <br><br>
                    <label for=""><b>last Name :</b></label><br>
                    <input type="text" id="last name" name="lastt name" placeholder="Enter the lastt Name" required/><br><br>
                    <label for=""><b>Gender</b></label><br>
                    <input type="radio" id="male" name="0">Male
                    <input type="radio" id="female" name="0">Female <br>
                    <input type="radio" id="other" name="0">Other        <br><br>   
                    <label for=""><b>Course</b></label>  <br>
                    <select name="" id="">
                        <option value="">HTML</option>
                        <option value="">CSS</option>
                        <option value="">JAVASCRIPT</option>
                        <option value="">JAVA</option>
                        <option value="">PYHTON</option>
                    </select><br><br> 
                    <label for="#">Address</label>  <br> 
                 <fieldset style="height: 80px; width: 120px;"> <legend> Address</legend><textarea name="address" id="address" placeholder="Enter the Address" required style="height: 60px; width: 120px; border: hidden;"></textarea></fieldset>
                    <h1 ></h1></fieldset>
                 </div>
                 <div class="box2" style="background-color: rgba(245, 244, 242, 0.816);">
                    <label for="">Email :</label><br>
                    <input type="email" name="email" id="email" placeholder="Enter the Email" required/><br><br>
                    <label for="">PASSWORD :</label><br>
                    <input type="password" id="password" name="0" placeholder="Enter the password" required/><br><br>
                    <input type="checkbox" id="checkbox" name="0"><label for=""><b>Remember Me</b></label><br><br>
                    <button value="submit" style="background-color: rgba(52, 52, 243, 0.678);"> LOGIN</button>

                 </div>
            </div>
        </div>
    </form>
</body>
</html>
