# Al-Adham-Advertising-and-Publicity
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الأدهم للدعاية والإعلان</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            direction: rtl;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .language-selector {
            position: absolute;
            top: 20px;
            right: 20px;
            background-color: #2980b9;
            padding: 5px 15px;
            border-radius: 5px;
            cursor: pointer;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
        }
        h1, h2 {
            color: #2c3e50;
        }
        .service-list {
            list-style-type: none;
            padding: 0;
        }
        .service-list li {
            background-color: #ecf0f1;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #2c3e50;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>الأدهم للدعاية والإعلان – إبداع بلا حدود!</h1>
    <div class="language-selector" onclick="changeLanguage()">English</div>
</header>

<section id="services">
    <h2>خدماتنا:</h2>
    <ul class="service-list">
        <li>تصميم الجرافيك والإعلانات المطبوعة</li>
        <li>الإعلانات الرقمية والتسويق الإلكتروني</li>
        <li>تصميم وتنفيذ الهويات البصرية</li>
    </ul>
</section>

<section id="why-choose-us">
    <h2>لماذا تختار الأدهم للدعاية والإعلان؟</h2>
    <ul class="service-list">
        <li>خبرة واحترافية في مجال الدعاية والإعلان</li>
        <li>تصاميم إبداعية تواكب أحدث الاتجاهات</li>
        <li>أسعار تنافسية مع جودة مضمونة</li>
        <li>التزام بالمواعيد وخدمة عملاء متميزة</li>
    </ul>
</section>

<footer>
    <p>للتواصل: 772329922 / 733887747</p>
    <p>البريد الإلكتروني: aladham2030@gmail.com</p>
    <p>موقعنا الإلكتروني: <a href="https://linktr.ee/ALADHAM2030" target="_blank">Linktr.ee/ALADHAM2030</a></p>
</footer>

<script>
    function changeLanguage() {
        if (document.documentElement.lang === "ar") {
            document.documentElement.lang = "en";
            document.querySelector("h1").innerText = "Al-Adham Advertising & Marketing – Creativity Without Limits!";
            document.querySelector("h2").innerText = "Our Services:";
            document.querySelectorAll(".service-list li")[0].innerText = "Graphic Design & Print Advertising";
            document.querySelectorAll(".service-list li")[1].innerText = "Digital Advertising & Online Marketing";
            document.querySelectorAll(".service-list li")[2].innerText = "Brand Identity Design & Implementation";
            document.querySelector("#why-choose-us h2").innerText = "Why Choose Al-Adham Advertising & Marketing?";
            document.querySelectorAll("#why-choose-us .service-list li")[0].innerText = "Professional expertise in advertising & marketing";
            document.querySelectorAll("#why-choose-us .service-list li")[1].innerText = "Creative designs that follow the latest trends";
            document.querySelectorAll("#why-choose-us .service-list li")[2].innerText = "Competitive prices with guaranteed quality";
            document.querySelectorAll("#why-choose-us .service-list li")[3].innerText = "Commitment to deadlines & excellent customer service";
            document.querySelector(".language-selector").innerText = "عربي";
        } else {
            document.documentElement.lang = "ar";
            document.querySelector("h1").innerText = "الأدهم للدعاية والإعلان – إبداع بلا حدود!";
            document.querySelector("h2").innerText = "خدماتنا:";
            document.querySelectorAll(".service-list li")[0].innerText = "تصميم الجرافيك والإعلانات المطبوعة";
            document.querySelectorAll(".service-list li")[1].innerText = "الإعلانات الرقمية والتسويق الإلكتروني";
            document.querySelectorAll(".service-list li")[2].innerText = "تصميم وتنفيذ الهويات البصرية";
            document.querySelector("#why-choose-us h2").innerText = "لماذا تختار الأدهم للدعاية والإعلان؟";
            document.querySelectorAll("#why-choose-us .service-list li")[0].innerText = "خبرة واحترافية في مجال الدعاية والإعلان";
            document.querySelectorAll("#why-choose-us .service-list li")[1].innerText = "تصاميم إبداعية تواكب أحدث الاتجاهات";
            document.querySelectorAll("#why-choose-us .service-list li")[2].innerText = "أسعار تنافسية مع جودة مضمونة";
            document.querySelectorAll("#why-choose-us .service-list li")[3].innerText = "التزام بالمواعيد وخدمة عملاء متميزة";
            document.querySelector(".language-selector").innerText = "English";
        }
    }
</script>

</body>
</html>
