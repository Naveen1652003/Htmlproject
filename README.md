# Htmlproject



Login page



<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Login Page</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
      }
      .login-container {
        width: 300px;
        padding: 20px;
        margin: 100px auto;
        background-color: #fff;
        box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.1);
        border-radius: 10px;
      }
      h1 {
        text-align: center;
      }
      .login-container label {
        display: block;
        margin-bottom: 5px;
      }
      .login-container input[type="email"],
      .login-container input[type="password"] {
        width: 100%;
        padding: 10px;
        margin-bottom: 15px;
        border: 1px solid #ccc;
        border-radius: 5px;
      }
      .login-container input[type="submit"] {
        width: 100%;
        padding: 10px;
        background-color: #5cb85c;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
      }
      .login-container input[type="submit"]:hover {
        background-color: #4cae4c;
      }
      .links {
        text-align: center;
        margin-top: 15px;
      }
      .links a {
        margin: 0 10px;
        text-decoration: none;
        color: #007bff;
      }
    </style>
  </head>
  <body>
    <div class="login-container">
      <h1>Login Page</h1>
      <form action="login.php" method="post">
        <label for="email"><b>Email ID:</b></label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required />

        <label for="password"><b>Password:</b></label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required />

        <input type="submit" value="Submit" />
      </form>
      <div class="links">
        <a href="./Form.html">Signup</a>
        <a href="./Forgotpassword.html">Forgot Password?</a>
      </div>
    </div>
  </body>
</html>


222222222222222222222222222222



Signup page



<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Signup Page</title>
    <style>
      body {
        background-color: rgb(145, 93, 194);
        font-family: Arial, sans-serif;
      }
      .form-container {
        width: 400px;
        padding: 20px;
        margin: 100px auto;
        background-color: white;
        border-radius: 10px;
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
      }
      h1 {
        text-align: center;
      }
      label {
        display: block;
        margin-bottom: 10px;
        font-weight: bold;
      }
      input[type="text"],
      input[type="email"],
      input[type="tel"],
      input[type="password"],
      input[type="date"],
      input[type="month"],
      input[type="week"] {
        width: 100%;
        padding: 10px;
        margin-bottom: 20px;
        border: 1px solid #ccc;
        border-radius: 5px;
      }
      input[type="checkbox"],
      input[type="radio"] {
        margin-right: 5px;
      }
      input[type="submit"] {
        width: 100%;
        padding: 10px;
        background-color: #5cb85c;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
      }
      input[type="submit"]:hover {
        background-color: #4cae4c;
      }
      .center-content {
        text-align: center;
      }
      .skills-container, .radio-container {
        margin-bottom: 20px;
      }
    </style>
  </head>
  <body>
    <div class="form-container">
      <h1>Signup Page</h1>
      <form action="">

        <label for="username">Name:</label>
        <input
          type="text"
          id="username"
          placeholder="Enter your name"
          name="username"
          required
        />

        <label for="Email">Email:</label>
        <input
          type="email"
          id="Email"
          placeholder="Enter your email"
          name="email"
          required
        />

        <label for="Phonenumber">Phone Number:</label>
        <input
          type="tel"
          id="Phonenumber"
          placeholder="Enter your phone number"
          name="phonenumber"
          required
        />

        <label for="Password">Password:</label>
        <input
          type="password"
          id="Password"
          placeholder="Enter your password"
          name="password"
          required
        />

        <label for="Dateofbirth">Date of Birth:</label>
        <input type="date" id="Dateofbirth" name="dateofbirth" required />

        <label for="month">Month:</label>
        <input type="month" id="month" name="month" />

        <label for="week">Week:</label>
        <input type="week" id="week" name="week" />

        <div class="skills-container">
          <label><b>Skills</b></label>
          <input type="checkbox" id="html-skill" value="html" /><label for="html-skill">HTML</label>
          <input type="checkbox" id="css-skill" value="css" /><label for="css-skill">CSS</label>
          <input type="checkbox" id="javascript-skill" value="javascript" /><label for="javascript-skill">JavaScript</label>
        </div>

        <div class="radio-container">
          <label><b>Your Favorite:</b></label>
          <input type="radio" id="html-radio" name="favorite" value="html" />
          <label for="html-radio">HTML</label>
          <input type="radio" id="css-radio" name="favorite" value="css" />
          <label for="css-radio">CSS</label>
          <input type="radio" id="javascript-radio" name="favorite" value="javascript" />
          <label for="javascript-radio">JavaScript</label>
        </div>

        <input type="submit" value="Submit" />
      </form>
    </div>
  </body>
</html>


3.............

Forgot passsword page:::

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forgot Password</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }
        .form-container {
            width: 400px;
            padding: 20px;
            margin: 100px auto;
            background-color: white;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        h1 {
            text-align: center;
            color: #5c5c5c;
        }
        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }
        input[type="email"],
        input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #5cb85c;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #4cae4c;
        }
    </style>
</head>
<body>

    <div class="form-container">
        <h1>Forgot Password</h1>
        <form action="">
            <label for="email"><b>Enter Email ID:</b></label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            
            <label for="current-password"><b>Enter Current Password:</b></label>
            <input type="password" id="current-password" name="current-password" placeholder="Enter your current password" required>
            
            <label for="new-password"><b>Enter New Password:</b></label>
            <input type="password" id="new-password" name="new-password" placeholder="Enter your new password" required>
            
            <input type="submit" value="Submit">
        </form>
    </div>

</body>
</html>



