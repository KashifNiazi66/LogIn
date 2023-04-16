<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width,
		initial-scale=1.0"
    />
    <title>Login Form</title>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
      integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background: #e7e393;
      }
      header {
        background-color:#DD7230;
        color: #fff;
        padding: 10px;
        text-align: center;
      }
      .container {
        border: 3px dotted #f4c95d;
        border-radius: 2%;
        max-width: 800px;
        margin: 100px auto 0 auto;
        padding: 20px;
      }

      .login-box {
        margin-left: 193px;
        padding: 10px;
      }
      input {
        background-color: white;
        border-radius: 10px;
        outline-style: none;
        outline-width: 0;
        font-size: 20px;
        display: inline-block;
        width: 50%;
        margin: 10px auto;
        padding: 5px 10px;
      }
      .btn {
        margin-left: 57px;
        margin-top: 10px;
        display: inline-block;
        padding: 10px 20px;
        background-color: #854d27;
        color: #fff;
        text-decoration: none;
        border-radius: 5px;
        transition: background-color 0.3s;
      }
      .btn:hover {
        background-color: #555;
      }
      .const {
        text-align: center;
      }
    </style>
  </head>

  <body>
    <header>
      <h1 class="heading">BiteBoss</h1>
      <h3 class="title">Login Form</h3>
    </header>

    <!-- container div -->
    <div class="container">
      <!-- Form section that contains the
			login and the signup form -->
      <div class="form-section">
        <!-- login form -->
        <div class="login-box">
          <i class="fa fa-user fa-lg fa-flip"></i>
          <input
            type="email"
            class="email ele"
            placeholder="forexample@email.com"
            required
          />
          <br />
          <i class="fa fa-lock fa-lg fa-flip"></i>
          <input
            type="password"
            class="password ele"
            placeholder="password"
            required
          />
          <br />
          <button class="btn">Login</button>
          <a href="/12html.html"><button class="btn">Signup</button></a>
        </div>
      </div>
    </div>
    <div class="const">
      <h4>
        CAUTION
        <i class="fa-sharp fa fa-triangle-exclamation fa-beat-fade fa-sm"></i>
      </h4>
      <p>
        A strong password typically consists of at least 8 characters that include a mix of uppercase and lowercase letters, numbers, 
        and symbols.
      </p>
    </div>
  </body>
</html>
