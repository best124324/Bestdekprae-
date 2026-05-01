<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<title>เป็นแฟนกันนะ 🥺💖</title>

<style>
body {
  font-family: sans-serif;
  text-align: center;
  background: linear-gradient(to right, #ffd6e0, #ffe9f0);
  padding-top: 60px;
}

.container {
  background: white;
  display: inline-block;
  padding: 30px;
  border-radius: 20px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

img {
  width: 150px;
  margin-bottom: 20px;
}

h1 {
  font-size: 26px;
}

button {
  padding: 12px 20px;
  font-size: 16px;
  margin: 10px;
  border: none;
  border-radius: 10px;
  cursor: pointer;
}

.yes {
  background: #ff6b81;
  color: white;
}

.no {
  background: #ddd;
}
</style>
</head>

<body>

<div class="container">
  <img src="https://media.giphy.com/media/MDJ9IbxxvDUQM/giphy.gif" alt="cute">

  <h1>เป็นแฟนกันมั้ย 🥺💖</h1>
  <p>เราตั้งใจทำเว็บนี้ให้เธอเลยนะ 💌</p>

  <button class="yes" onclick="yes()">💖 ตกลง</button>
  <button class="no" onclick="no()">🙈 เขินแป๊บ</button>
</div>

<script>
function yes() {
  alert("เย้! ได้แฟนแล้ววว 💖🥰");
}

function no() {
  alert("เขินได้แต่อย่าหนีน้า 😆");
}
</script>

</body>
</html>
