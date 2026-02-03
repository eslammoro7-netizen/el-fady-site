
 html>
<html lang="ar" dir="rtl">فة خط تحت الكلمة */
<head>
    <meta charset="UTF-8">
    <title>مشروع El Fady | المبرمج الصغير</title>
    <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/606/606203.png">
    
    <style>
        /* تنسيق عام للجسم */
        body {
            background-color: #f0f8ff; /* خلفية الموقع */
            color: darkblue; /* لون الخط الأساسي */
            font-weight: bold; /* خط عريض */
        }

        /* تأثير حركي لزر الإرسال */
        button:hover {
            background-color: #45a049 !important;
            transform: scale(1.1);
            transition: 0.3s;
        }

        /* تأثير حركي للروابط */
        a:hover {
            color: #FF5722;
            text-decoration: underline;
        }
    </style>
</head>

<body>

  /* تأثير لزر الإرسال */
button:hover {
    background-color: #45a049 !important; /* لون أخضر أغمق */
    transform: scale(1.1); /* تكبير الزر بنسبة 10% */
    transition: 0.3s; /* جعل الحركة ناعمة وليست مفاجئة */
}

/* تأثير لروابط التنقل */
a:hover {
    color: #FF5722; /* تغيير لون الرابط للبرتقالي */
    text-decoration: underline; /* إضافة خط تحت الكلمة */
}
    h1 {
            color: #ff0000;
            text-align: center;
        }
    </style>

<body style="background-color: lightgray;">

  <header>
 <ol type="A">
<li>مرحباً بكم في مشروعي 🌟</li>
</ol>
<img src="https://images.unsplash.com/photo-1550745165-9bc0b252726f" alt="شاشة كمبيوتر" style="width:100%; max-width:500px; display:block; margin:auto; border-radius: 10px; margin-top: 20px;">
<div id="clock" style="font-size: 24px; color: #ff5722; text-align: center; margin-top: 20px;"></div>

<main>
<footer>
<p>2026 © حقوق النشر - ابحث عن المزيد في <a href="https://www.google.com" target="_blank">جوجل</a></p>
<h3>إنجازاتي في البرمجة:</h3>
<ol type="A">
  <li>تنسيق العناوين باللون الأحمر 🎨</li>
  <li>إضافة صورة وتحديد حجمها 🖼️</li>

<li>إنشاء روابط تفتح في نافذة جديدة 🔗</li>
<textarea placeholder="ما رأيك في البرمجة؟"></textarea><br><br>
<button onclick="alert('شكراً لمشاركتك رأيك في مشروع El Fady!')" style="background-color: #4CAF50; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer; font-family: Arial;">
  أرسل رأيك ✨
</button>

<table border="1" style="background-color: #f0f8ff; color: darkblue;">
    <td>المهارة</td>
    <td>الحالة</td>
  </tr>
  <tr>
    <td>إضافة الروابط</td>
<td><a href="https://www.google.com" target="_blank" style="color: green;">مكتمل ✅</a></td>

    <td>تعلم الجداول 📊</td>
    <td>قيد التنفيذ ⏳</td>
  </tr>

</table>
<h3 style="text-align: center;">شاهد وتعلم المزيد 📺</h3>
<iframe width="100%" height="315" 
src="https://www.youtube.com/embed/dQw4w9WgXcQ" <hr>
<h3 style="text-align: center;">شاركنا رأيك في المشروع ✍️</h3>
<form style="background-color: white; padding: 20px; border-radius: 10px;">
  <label>الاسم:</label><br>
  <input type="text" placeholder="اكتب اسمك هنا  <label>البريد الإلكتروني:</label><br>
  <input type="email" placeholder="example@mail.com" required><br><br>
"><br><br>
  
  <label>رأيك في المشروع:</label><br>
  <textarea placeholder="ما رأيك في البرمجة؟" <p>كيف وجدت تجربة البرمجة مع El Fady؟</p>
<input type="radio" name="feedback" value="fun" id="f1">
<label for="f1">ممتعة 🤩</label><br>

<input type="radio" name="feedback" value="hard" id="f2">
<label for="f2">صعبة قليلاً 😅</label><br><br><label>ما هي أكثر مهارة أعجبتك؟</label><br>
<select name="best-skill">
  <option value="tables">بناء الجداول 📊</option>
  <option value="videos">إضافة الفيديوهات 🎥</option>
  <option value="forms">إنشاء النماذج 📝</option>
</select><br><br>

 <input type="checkbox" id="agree" required>
  <label for="agree">أوافق على سياسة الخصوصية 📜</label><br><br>
></textarea><br><br>
  <button type="submit" style="background-color: #4CAF50; color: white; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer;">إرسال الرأي 🚀   id="myButton"</button>

  <input type="submit" value="إرسال الرأي 🚀">
</form<script>
    // 1. الوصول للزر عن طريق الـ ID الذي أعطيناه له
    const btn = document.getElementById('myButton');

    // 2. إخبار المتصفح: "عندما يضغط (click) المستخدم على الزر، نفذ الآتي"
    btn.onclick = function() {
        alert("شكراً لك يا مبرمج El Fady! تم استلام رأيك بنجاح 🌟");
<div id="clock" style="font-size: 24px; color: #FF5722; text-align: center; margin-top: 20px;">جاري تحميل الوقت... ⏳</div>

    جاري تحميل الوقت... ⏳
</div>

</script>
function updateClock() {
    const now = new Date();
    // جلب الساعات والدقائق والثواني
    const h = now.getHours();
    const m = now.getMinutes();
    const s = now.getSeconds();

    // دمج الكلمة العربية مع الأرقام
    const timeString = "الساعة الآن: " + h + ":" + m + ":" + s;

    // عرض النتيجة في الـ div
    document.getElementById('clock').innerHTML = timeString;
}

// تشغيل الدالة كل 1000 مللي ثانية (ثانية واحدة)
setInterval(updateClock, 1000);


frameborder="0" allowfullscreen></iframe>
<script>
  function updateClock() {
    const now = new Date();
    // الحصول على الساعات والدقائق والثواني بشكل منظم scriptk
    const hours = String(now.getHours()).padStart(2, '0');
    const minutes = String(now.getMinutes()).padStart(2, '0');
    const seconds = String(now.getSeconds()).padStart(2, '0');
  
    const timeString = hours + ":" + minutes + ":" + seconds;
    
    // الربط مع السطر 57
    document.getElementById('clock').textContent = timeString;
  }

  // تحديث كل ثانية واحدة
  setInterval(updateClock, 1000);
  updateClock(); 
</script>
</body>
</html>
