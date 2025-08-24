<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>sign up/login</title>
    <link rel="stylesheet" href="./assets/master.css">
  </head>
  <body>
    <div class="login">
      <form action="log.php" method="post">
        <h1>LOGIN</h1>
        <label for="inp1">username</label>
        <input
          type="text"
          id="inp1"
          placeholder="username"
          required
          autofocus
        />
        <label for="inp2">password</label>
        <input type="password" id="inp2" required placeholder="@#*^%*$@" />
        <button>submit</button>
      </form>
    </div>
  </body>
</html>
