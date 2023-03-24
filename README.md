# style-form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        #register-form{
            width: 300px;
            background-color: white;
            padding: 24px;
            margin-left: auto;
            margin-right: auto;
        }
        .input-label{
            margin: 0;
            margin-bottom: 4px;
            margin-top: 24px;
        }
        .input-item{
            width: 100%;
        }
        #terms-check{
            margin-top: 12px;
            margin-bottom: 18px;
        }

    </style>
</head>
<body style="background-color: lightblue;">
    <form id="register-form" method="get">
        <h1 style="text-align: center;">Signup</h1>
       <div>
       <p class="input-label"> Fullname: </p>
        <input class="input-item" type="text" name="fullname">
       </div>
       <div>
       <p class="input-label"> Email: </p>
        <input class="input-item" type="email" name="email">
       </div>
       <div>
       <p class="input-label"> Password: </p>
        <input class="input-item" type="password" name="Password">
       </div>
       <div>
       <p class="input-label"> Confirm Password: </p> 
        <input class="input-item" type="password" name="confirm password">
       </div><br>
       <div>
        Gender: <br>
        <input type="radio" name="male" value="male">
        Male</input>
        <input type="radio" name="female" value="female">
        Female</input>
        <input type="radio" name="other" value="other">
        Other</input>
       </div>
       <div>
        <p class="input-label"> Security Question: </p>
        <select class="input-item" name="security-question">
            <option value="first-pet-name">What was your pet Name?</option>
            <option value="first-job">What is your first job?</option>
            <option value="nick-name">What is your nick name?</option>
        </select>
       </div>
       <div>
        <textarea class="input-item" name="answer" id="" cols="30" rows="10"></textarea>
       </div>
       <div>
        <input id="terms-check" type="checkbox" name="terms-conditions" value="accept">I agree to accept terms and conditions</div>
       <input type="submit" value="register">
    </form>
</body>
</html>
