# Bestdekprae-<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>ขอเป็นแฟน</title>
  <style>
    body {
      font-family: sans-serif;
      text-align: center;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      color: #333;
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
    }
    .yes { background: #ff4d6d; color: white; }
    .no { background: #ccc; }
  </style>
</head>
<body>

<h1>🎯 คุณถูกเลือกเป็นคนพิเศษ!</h1>
<p>จะเป็นแฟนกับเรามั้ย?</p>

<button class="yes" onclick="yes()">💖 เป็นแฟนกันเลย</button>
<button class="no" onclick="no()">😏 คิดดูก่อน</button>

<script>
function yes() {
  alert("เย้! ได้แฟนแล้ววว 🥰");
}
function no() {
  alert("ระบบไม่อนุญาตให้ปฏิเสธนะ 😂 ลองกดใหม่");
}
</script>

</body>
</html>
