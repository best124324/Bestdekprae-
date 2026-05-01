<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<title>ขอเป็นแฟน 😏</title>

<style>
body {
  font-family: sans-serif;
  text-align: center;
  background: linear-gradient(to right, #ff9a9e, #fad0c4);
  padding-top: 100px;
}

h1 { font-size: 28px; }

button {
  padding: 12px 20px;
  font-size: 16px;
  margin: 10px;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  position: relative;
}

.yes {
  background: #ff4d6d;
  color: white;
}

.no {
  background: #ccc;
  position: absolute;
}
</style>
</head>

<body>

<h1>💘 ระบบสุ่มเลือกคุณแล้ว!</h1>
<p>จะเป็นแฟนกับเรามั้ย? 🤭</p>

<button class="yes" onclick="yes()">💖 ตกลง</button>
<button class="no" id="noBtn">🙄 ไม่เอา</button>

<script>
function yes() {
  alert("เย้! หนีไม่รอดแล้วนะ 😆💖");
}

const noBtn = document.getElementById("noBtn");

noBtn.addEventListener("mouseover", () => {
  const x = Math.random() * window.innerWidth - 100;
  const y = Math.random() * window.innerHeight - 50;
  noBtn.style.left = x + "px";
  noBtn.style.top = y + "px";
});

noBtn.addEventListener("click", () => {
  alert("กดไม่ทันหรอกกก 😂");
});
</script>

</body>
</html>
