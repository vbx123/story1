<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>صفحة كتابة القصة</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Amiri&family=Reem+Kufi+Fun&display=swap');

    body {
      background-color: #121212;
      color: #f5f5f5;
      font-family: 'Amiri', serif;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    header {
      text-align: center;
      margin: 30px 0 20px 0;
    }

    h1 {
      font-family: 'Reem Kufi Fun', sans-serif;
      color: #00bfa5;
      font-size: 2em;
      margin-bottom: 10px;
    }

    .container {
      width: 90%;
      max-width: 900px;
      background-color: #1e1e1e;
      border-radius: 15px;
      padding: 25px;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
    }

    label {
      font-family: 'Reem Kufi Fun', sans-serif;
      font-size: 1.1em;
      color: #bdbdbd;
    }

    input[type="text"] {
      width: 100%;
      padding: 10px;
      margin: 10px 0 20px 0;
      border: none;
      border-radius: 8px;
      background-color: #2c2c2c;
      color: #f5f5f5;
      font-size: 1em;
    }

    textarea {
      width: 100%;
      height: 400px;
      padding: 15px;
      border: none;
      border-radius: 10px;
      background-color: #2c2c2c;
      color: #f5f5f5;
      font-size: 1.1em;
      line-height: 1.8;
      resize: none;
    }

    textarea:focus, input:focus {
      outline: 2px solid #00bfa5;
    }

    .controls {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-top: 15px;
    }

    .word-count {
      font-size: 1em;
      color: #a5a5a5;
    }

    button {
      background-color: #00bfa5;
      color: #121212;
      border: none;
      border-radius: 8px;
      padding: 10px 20px;
      font-size: 1em;
      cursor: pointer;
      font-family: 'Reem Kufi Fun', sans-serif;
      transition: 0.3s;
    }

    button:hover {
      background-color: #009e8a;
    }

    footer {
      margin: 25px 0;
      color: #777;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>?? صفحة كتابة القصة</h1>
    <p>اكتب قصتك بأسلوبك وابدأ الإبداع الآن</p>
  </header>

  <div class="container">
    <label for="title">عنوان القصة:</label>
    <input type="text" id="title" placeholder="اكتب عنوان القصة هنا...">

    <label for="author">اسم الكاتب (اختياري):</label>
    <input type="text" id="author" placeholder="مثال: محمد قاسم">

    <label for="story">القصة:</label>
    <textarea id="story" placeholder="ابدأ في كتابة قصتك هنا..."></textarea>

    <div class="controls">
      <span class="word-count" id="wordCount">عدد الكلمات: 0</span>
      <button id="saveBtn">?? حفظ القصة</button>
    </div>
  </div>

  <footer>
    <p>??? تصميم احترافي لصفحة كتابة القصص - بإبداع</p>
  </footer>

  <script>
    const storyArea = document.getElementById('story');
    const wordCount = document.getElementById('wordCount');
    const saveBtn = document.getElementById('saveBtn');

    // تحديث عدد الكلمات
    storyArea.addEventListener('input', () => {
      const text = storyArea.value.trim();
      const words = text === '' ? 0 : text.split(/\s+/).length;
      wordCount.textContent = `عدد الكلمات: ${words}`;
    });

    // حفظ القصة محليًا
    saveBtn.addEventListener('click', () => {
      const title = document.getElementById('title').value.trim();
      const author = document.getElementById('author').value.trim();
      const story = storyArea.value.trim();

      if (title === '' || story === '') {
        alert('يرجى كتابة العنوان والقصة قبل الحفظ.');
        return;
      }

      const storyData = { title, author, story, date: new Date().toLocaleString() };
      localStorage.setItem('savedStory', JSON.stringify(storyData));

      alert('? تم حفظ القصة بنجاح!');
    });

    // تحميل القصة المحفوظة إن وجدت
    window.onload = () => {
      const saved = localStorage.getItem('savedStory');
      if (saved) {
        const data = JSON.parse(saved);
        document.getElementById('title').value = data.title;
        document.getElementById('author').value = data.author;
        storyArea.value = data.story;
        wordCount.textContent = `عدد الكلمات: ${data.story.trim().split(/\s+/).length}`;
      }
    };
  </script>
</body>
</html>
