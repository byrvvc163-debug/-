<img width="598" height="598" alt="tiger3 jpg" src="https://github.com/user-attachments/assets/03828073-2d00-4f48-b313-785f31fe67c6" />
<img width="1199" height="1146" alt="tiger2 jpg" src="https://github.com/user-attachments/assets/ac00b5e1-c5af-49f7-9874-249dbba0aca4" />
<img width="640" height="640" alt="tiger1 jpg" src="https://github.com/user-attachments/assets/0e96b0d2-f6ff-431c-acfc-ef48a68c6a18" />
# -<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>عالم النمور</title>

<style>
body{
    margin:0;
    font-family:Tahoma, Arial, sans-serif;
    background:#fff4e6;
    text-align:center;
}

header{
    background:#ff8800;
    color:white;
    padding:30px;
}

nav{
    background:#333;
    padding:10px;
}

nav a{
    color:white;
    text-decoration:none;
    margin:15px;
    font-size:18px;
}

section{
    background:white;
    margin:20px;
    padding:20px;
    border-radius:15px;
    box-shadow:0 2px 8px rgba(0,0,0,0.2);
}

.gallery img{
    width:280px;
    max-width:90%;
    margin:10px;
    border-radius:12px;
}

.highlight{
    color:darkred;
    font-weight:bold;
}

button{
    background:#ff8800;
    color:white;
    border:none;
    padding:12px 20px;
    font-size:18px;
    border-radius:8px;
    cursor:pointer;
}

button:hover{
    background:#e67300;
}

footer{
    background:#333;
    color:white;
    padding:20px;
    margin-top:20px;
}

@media screen and (max-width:700px){
    .gallery img{
        width:100%;
    }

    nav a{
        display:block;
        margin:10px;
    }
}
</style>
</head>

<body>

<script>
window.alert("مرحباً بك في موقع عالم النمور!");
</script>

<header>
    <h1>🐯 عالم النمور 🐯</h1>
    <p>موقع تعليمي للتعرف على النمور</p>
</header>

<nav>
    <a href="#about">نبذة</a>
    <a href="#gallery">الصور</a>
    <a href="#facts">حقائق</a>
    <a href="#sources">المصادر</a>
</nav>

<section id="about">
    <h2>نبذة عن النمور</h2>

    <p>
        يعتبر <span class="highlight">النمر</span>
        أكبر القطط البرية في العالم. يعيش في آسيا ويتميز
        بقوته الكبيرة وسرعته وخطوطه الفريدة.
    </p>
</section>

<section id="gallery">
    <h2>معرض الصور</h2>

    <div class="gallery">
        <img src="tiger1.jpg" alt="نمر">
        <img src="tiger2.jpg" alt="نمر">
        <img src="tiger3.jpg" alt="نمر">
    </div>

    <p>استبدل الصور بصورك الخاصة.</p>
</section>

<section id="facts">
    <h2>حقائق ممتعة</h2>

    <ul style="display:inline-block;text-align:right;">
        <li>النمور سباحة ممتازة.</li>
        <li>لا يوجد نمران لهما نفس الخطوط.</li>
        <li>قد يتجاوز وزن النمر 300 كجم.</li>
        <li>النمور من الحيوانات اللاحمة.</li>
    </ul>

    <p id="fact">اضغط على الزر لمعلومة إضافية.</p>

    <button onclick="showFact()">اضغط هنا</button>
</section>

<section id="sources">
    <h2>المصادر</h2>

    <p>Wikipedia - Tiger</p>
    <p>National Geographic - Tigers</p>
    <p>World Wildlife Fund (WWF)</p>
</section>

<footer>
    © 2026 عالم النمور
</footer>

<script>
function showFact(){
    document.getElementById("fact").innerHTML =
    "معلومة: يستطيع النمر القفز لمسافة تزيد عن 10 أمتار!";
}
</script>

</body>
</html>
