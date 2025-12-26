<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Quiz Game</title>
<style>
body{
  background:#111;
  color:white;
  font-family:Arial;
  text-align:center;
}
button{
  padding:15px;
  margin:10px;
  font-size:18px;
}
</style>
</head>

<body>

<h1>🎮 لعبة الأسئلة</h1>
<p id="q">هل تحب البرمجة؟</p>

<button onclick="a(1)">نعم</button>
<button onclick="a(0)">لا</button>

<script>
function a(x){
 document.getElementById("q").innerText =
 x ? "🔥 ممتاز!" : "😅 جرّب مرة ثانية";
}
</script>

</body>
</html>
