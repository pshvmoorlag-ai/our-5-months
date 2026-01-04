# our-5-months
<!DOCTYPE html>
<html>
<head>
  <title>Happy Monthsary 💙</title>

  <style>
    body {
      background: linear-gradient(to bottom, #cce7ff, #e6f2ff);
      font-family: Arial, sans-serif;
      text-align: center;
      color: #003366;
      padding: 40px;
    }

    h1 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      max-width: 600px;
      margin: 15px auto;
    }

    .heart {
      font-size: 30px;
      margin: 10px;
    }

    button {
      background-color: #1e90ff;
      color: white;
      border: none;
      padding: 15px 28px;
      font-size: 16px;
      border-radius: 30px;
      cursor: pointer;
      margin: 10px;
      transition: 0.3s;
    }

    button:hover {
      background-color: #187bcd;
      transform: scale(1.05);
    }

    #hiddenMessage {
      display: none;
      margin-top: 20px;
      font-size: 18px;
    }

    #extraMessage {
      display: none;
      font-size: 22px;
      margin-top: 25px;
    }
  </style>
</head>

<body>

  <h1>Happy Monthsary 💙</h1>

  <div class="heart">💙💙💙💙💙</div>

  <p>
    Hi lovieeee!! Happy 5 months to usss, I'm so glad to have an amazing partner like you. No one could ever compare. 
  </p>

  <p>
    Thank you for being my comfort, my safe space and my favorite person.. 
    even when yo ass KEEPS playing bedwarsss 🥹🥹
  </p>

  <p>
    I’m really glad you’re mine.
  </p>

  <!-- BUTTONS -->
  <button onclick="showMessage()">When you miss me</button>
  <button onclick="gamerAlert()">...</button>
  <button onclick="clickMe()">CLICK ME 💙</button>

  <!-- HIDDEN TEXT -->
  <div id="hiddenMessage">
    💙 I miss you too. I’ll always choose you. 💙
  </div>

  <div id="extraMessage">
    💙💙💙  
    Surprise!  
    You’re my favorite person and you always will be. 
    💙💙💙
  </div>

  <script>
    function showMessage() {
      document.getElementById("hiddenMessage").style.display = "block";
    }

    function gamerAlert() {
      alert("You'll always be my baby boy :3 💙 (biggie" );
    }

    function clickMe() {
      document.getElementById("extraMessage").style.display = "block";
    }
  </script>

</body>
</html>
