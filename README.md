- 👋 Hi, I’m @Mohammedzebari
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Mohammedzebari/Mohammedzebari is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مولد الإعلانات</title>
</head>
<body>
  <h1>مرحبا بك في مولد الإعلانات 🚀</h1>
  <form id="adForm">
    <label>اسم المنتج:</label><br>
    <input type="text" id="product"><br><br>
    <label>الجمهور المستهدف:</label><br>
    <input type="text" id="audience"><br><br>
    <label>المنصة:</label><br>
    <input type="text" id="platform"><br><br>
    <button type="submit">أنشئ الإعلان</button>
  </form>

  <script>
    document.getElementById('adForm').onsubmit = function(event) {
      event.preventDefault();
      const product = document.getElementById('product').value;
      const audience = document.getElementById('audience').value;
      const platform = document.getElementById('platform').value;

      alert(`تم إنشاء إعلان لمنتج: ${product}\nللجمهور: ${audience}\nعلى المنصة: ${platform}`);
    };
  </script>
</body>
</html>
