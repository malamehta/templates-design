# templates-design
 facebook login page using basic of html and css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="main">
       
        <div class="header">
            <div class="logo">
                <img src="images/fblogo.jpg">
            </div>
            <div class="form"> 
                <table>
                    <tr>
                        <td style="padding-right: 40px;">Email or Phone </td>
                        <td>Password </td>
                       <td> </td>
                    </tr>
                    <tr >
                        <td style="padding-top: 8px;"> <input type="text" placeholder="Email or Phone"></td>
                        <td style="padding-top: 8px;"> <input type="password" placeholder="Password"></td>
                        <td style="padding-top: 8px;"><input type="submit" placeholder="submit"></td>
                    </tr>
                    <tr><td></td>
                        <td style="padding-top: 5px;color: rgb(185, 174, 174);"> forgotton account?</td><td></td>
                    </tr>
                </table>
            </div>
        </div>
        <div class="bodypart">
            <div class="left">
                <img src="images/facebook.jpg">
            </div>
            <div class="right">
                <h1>Create an account</h1>
                <p style="padding-top: 6px;"><b>it's free and always will be.</b></p>
                <table>
                    <tr><td  style="padding-top: 14px;"><input type="text" placeholder="First name" style="height: 30px;"></td>
                        <td  style="padding-top: 14px;"><input type="text" placeholder="Surname" style="height: 30px;"></td>
                    </tr>
                 </table>   
                  <table>  
                    <tr><td style="padding-top: 10px;"><input type="text" placeholder="mobile number or email address" style="width: 330px; height: 30px;"></td></tr>
                    <tr><td style="padding-top: 10px;"><input type="password" placeholder="New password" style="width: 330px; height: 30px;"></td></tr>
                    <tr><td style="font-weight: bold;padding-top: 20px;">Birthday</td></tr>
                    </table>
                    <table>
                    <tr><td><input type="date"></td><td>why do i need to provide my<br> date of birth?</td></tr>
                    <tr><td style="padding-top: 14px;"><input type="radio" name="gender">Male <input type="radio" name="gender">Female</td></tr>
                </table>
                <p style="padding-top: 20px;color: rgb(100, 99, 99);">By clicking sign up,you agree to our Terms, Data policy and Cookie Policy.You may receive SMS
                     notification from us and can opt out at any time.</p>
                     <table>

                        <tr><td style="padding-top: 14px;;"><input type="submit" value="Sign Up" style="width: 200px;
                         height: 50px;background-color: green;color: white;border-radius: 5px;" ></td></tr>
                         <tr><td style="padding-top: 20px;">create a page for a celebrity ,band aur business.</td></tr>
                     </table>
                     
            </div>
        </div>
        <div class="footer">

        </div>
       

    </div>
    
</body>
</html>
