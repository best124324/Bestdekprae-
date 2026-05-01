<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<title>โดนจับเป็นแฟน 😈</title>

<style>
body {
  font-family: sans-serif;
  text-align: center;
  background: linear-gradient(to right, #ff758c, #ff7eb3);
  padding-top: 100px;
  overflow: hidden;
}

h1 { font-size: 30px; color: white; }

button {
  padding: 12px 20px;
  font-size: 16px;
  margin: 10px;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  position: absolute;
}

.yes {
  background: #ff1744;
  color: white;
  left: 40%;
  top: 50%;
}

.no {
  background: #eee;
  left: 55%;
  top: 50%;
}
</style>
</head>

<body>

<h1>💘 คุณโดนเลือกแล้ว!</h1>
<p style="color:white;">จะเป็นแฟนกับเรามั้ย? 😏</p>

<button class="yes" onclick="yes()">💖 ตกลง</button>
<button class="no" id="noBtn">🙄 ไม่เอา</button>

<script>
function yes() {
  let count = 0;
  let interval = setInterval(() => {
    alert("เป็นแฟนแล้วนะ 😆💖");
    count++;
    if(count > 3) clearInterval(interval);
  }, 500);
}

const noBtn = document.getElementById("noBtn");

// ปุ่มหนีขั้นเทพ
noBtn.addEventListener("mouseover", () => {
  moveBtn();
});

// กดก็หนี
noBtn.addEventListener("click", () => {
  alert("ไม่ให้กดดด 😂");
  moveBtn();
});

function moveBtn() {
  const x = Math.random() * (window.innerWidth - 100);
  const y = Math.random() * (window.innerHeight - 50);
  noBtn.style.left = x + "px";
  noBtn.style.top = y + "px";
}

// เด้งข้อความหลอกตอนเข้าเว็บ
setTimeout(() => {
  alert("⚠️ แจ้งเตือน: คุณมีแฟนแล้ว 1 คน");
}, 1000);
</script>

</body>
</html>
