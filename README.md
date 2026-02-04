# Valentine
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For Alessia ❤️</title>
<style>
body {
  margin: 0;
  height: 100vh;
  background: linear-gradient(135deg, #ff9a9e, #fad0c4);
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: "Georgia", serif;
}

.card {
  background: white;
  padding: 50px 60px;
  border-radius: 20px;
  text-align: center;
  box-shadow: 0 20px 40px rgba(0,0,0,0.2);
}

h1 {
  color: #d6336c;
  font-size: 32px;
}

p {
  font-size: 18px;
  color: #444;
}

.buttons {
  margin-top: 30px;
}

button {
  font-size: 18px;
  padding: 12px 30px;
  border-radius: 30px;
  border: none;
  margin: 10px;
  cursor: pointer;
  transition: transform 0.2s;
}

button:hover {
  transform: scale(1.1);
}

.yes {
  background: #ff4d6d;
  color: white;
}

.yes2 {
  background: #ff8fab;
  color: white;
}

.heart {
  font-size: 40px;
  margin-bottom: 10px;
}
</style>
</head>

<body>
  <div class="card">
    <div class="heart">❤️</div>
    <h1>Alessia</h1>
    <p>
      From the moment you crossed my mind,  
      my heart knew something special was happening.
    </p>

    <p style="font-size:22px;">
      Will you be my Valentine?
    </p>

    <div class="buttons">
      <button class="yes" onclick="love()">Yes 💕</button>
      <button class="yes2" onclick="love()">Yes 😘</button>
    </div>
  </div>

<script>
function love() {
  document.body.innerHTML = `
    <div style="text-align:center;">
      <h1 style="color:white;font-size:40px;">You just made my heart smile ❤️</h1>
      <p style="color:white;font-size:22px;">Happy Valentine’s Day, Alessia.</p>
    </div>
  `;
}
</script>
</body>
</html>

