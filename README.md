<!DOCTYPE html>
<html>
  <head>
    <title>sign in</title>
    <base target="_blank">
    <link href='https://fonts.googleapis.com/css?family=Sofia' rel='stylesheet'>
    <style>
      body {   
        background-color: aquamarine;
        display: grid;
        font-family: Sofia;
        font-size: 250px;
      }
      header {
        position: relative;
        top: 0px;
        height: 100vh;
        background-repeat: no-repeat;
        background-blend-mode: luminosity ;
        background-size: cover;
        background-image: url(/images/mac.jpg);
      }
      legend {
        color: springgreen;
        text-align: center;
      }
      fieldset {
        color: violet;
        position: absolute;
        border-radius: 25px;
        float: left;
        top: 20%;
        right: 25px;
        border-color: seagreen;
        width: 40%;
        height: 1000px;
        z-index: 1;
      }
      nav {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        position: absolute;
        top: 0px;
        width: 100%;
        height: 70px;
        background-color: rgba(19, 18, 18, 0);
      }
      .logo {
        position: absolute;
        top: 5px;
        left: 10px;
        max-width: 60px;
        max-height: 60px;
        transition-duration: 0.5s;
      }
      .logo:hover {
        transform: scale(1.1);
      }
      .nav {
        position: absolute;
        right: 20px;
        top: 15px;
      }
      button {
        width: 60px;
        height: 40px;
        background-color: transparent;
        color: tomato;
        margin-left: 10px;
        border: none;
        transition-duration: 0.5s;
      }
      button:hover {
        color: aquamarine;
        font-family: serif;
        background-color: rgb(34, 33, 33);
      }
      main {
        position: relative;
        height: 1000px;
        background-color: gold;
        box-shadow: 0px 5px 5px 5px rgb(20, 20, 20);
      }
      .tran {
        background-color: transparent;
        height: 240px;
        width: 100%;
        z-index: 1;
      }
      footer {
        position: fixed;
        background-attachment: fixed;
        bottom: 0px;
        z-index: -1;
        width: 100%;
        height: 250px;
        background-color: firebrick;
      }
    </style>
  </head>
  <body>
    <header>
      <nav>
        <img class="logo" src="/images/logo.jpg" alt="logo">
        <div class="nav">
        <a href="index.html" ><button>Home</button></a><button>Login</button><button class="sep">contact</button>
        </div>
      </nav>
      <form>
        <fieldset>
          <legend>Sign in</legend>
          <label for="first name">First name:</label>
        <input type="text">
        </fieldset>
      </form>
    </header>
    <div>
    </div>
    <main>
    </main>
    <div class="tran"></div>
    <footer>
      <img src="/images/pizza.jpg">
    </footer>
  </body>
</html>
