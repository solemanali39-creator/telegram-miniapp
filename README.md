<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Smart Quiz Academy</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<script src="https://telegram.org/js/telegram-web-app.js"></script>
<style>
body{
  font-family: Arial, sans-serif;
  background:#f5f7fa;
  text-align:center;
  padding:20px;
}
button{
  padding:12px 20px;
  font-size:16px;
  border:none;
  background:#0088cc;
  color:#fff;
  border-radius:6px;
}
</style>
</head>

<body>
<h2>Smart Quiz Academy</h2>
<p>Practice smart. Learn faster.</p>
<button onclick="startQuiz()">Start Quiz</button>

<script>
const tg = window.Telegram.WebApp;
tg.expand();

function startQuiz(){
  tg.sendData("Quiz Started");
}
</script>
</body>
</html>
