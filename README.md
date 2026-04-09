<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<title>ملاك ❤️</title>

<style>
body {
  font-family: Arial;
  background: #f8f9fa;
  margin: 0;
  overflow-x: hidden;
}

.header {
  background: #ff4d6d;
  color: white;
  padding: 15px;
  font-size: 26px;
  text-align: center;
}

.content {
  padding: 25px;
  background: white;
  position: relative;
  z-index: 2;
  line-height: 1.8;
}

.infobox {
  float: left;
  width: 260px;
  background: #ffe5ec;
  border: 1px solid #ffccd5;
  padding: 10px;
  margin: 10px;
  text-align: center;
}
.infobox img {
  width: 100%;
  border-radius: 10px;
}

h1, h2 {
  color: #ff4d6d;
}

/* القلوب */
.heart {
  position: fixed;
  bottom: -20px;
  color: #ff4d6d;
  animation: floatUp 6s linear forwards;
  opacity: 0.7;
}

@keyframes floatUp {
  0% {transform: translateY(0); opacity: 0.8;}
  100% {transform: translateY(-110vh); opacity: 0;}
}
</style>
</head>

<body>

<div class="header">💖 قصة حب ما تنتهي 💖</div>

<div class="content">

<h1>ملاك</h1>

<div class="infobox">
  <img src="your-image.jpg" alt="صورة ملاك">
  <p><b>الاسم:</b> ملاك</p>
  <p><b>تاريخ البداية:</b> 28/12/2025</p>
</div>

<p>
ملاك مو مجرد بنت في حياتي… ملاك هي الشيء اللي غيرني، غير تفكيري، وغير إحساسي بكل شيء حولي.
أنا سعد، ومن يوم دخلت حياتي، وأنا أشوف الدنيا بشكل أجمل.
</p>

<h2>جمالها</h2>
<p>
جمالها مو طبيعي… هي جمال العالم كله، وضحكتها تسوى الدنيا وما فيها.
</p>

<h2>ذكائها</h2>
<p>
ملاك ذكية بطريقة مختلفة… كل كلمة تقولها فيها وعي وجمال.
</p>

<h2>ثقتها بنفسها</h2>
<p>
ملاك لازم تعرف شيء مهم:
هي مو بس جميلة… هي قوية، واثقة، ومميزة بطريقة ما تتكرر.
</p>

<h2>دلعها واهتمامها</h2>
<p>
دلعها عليّ شيء ما ينمل منه… واهتمامها يخليني أحس إني أغلى شخص في حياتها.
</p>

<h2>عن حبي لها</h2>
<p>
أنا أحب ملاك… مو حب بسيط.
أنا أهيم فيها، وأفكر فيها بكل وقت.
وجودها في حياتي نعمة حقيقية ❤️
</p>

<h2>رسالة أخيرة</h2>
<p>
يا ملاك… أحبك جدًا جدًا، وأهيم فيك، وأؤمن بك، وأقدرك أكثر مما تتخيلين. وجودك معي يخليني أحس بالسعادة كل يوم.
</p>

</div>

<script>
// انتظر تحميل الصفحة بالكامل قبل إنشاء القلوب
window.addEventListener("load", function() {
  function createHeart() {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML = "❤️";

    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (15 + Math.random() * 25) + "px";

    document.body.appendChild(heart);

    setTimeout(() => {
      heart.remove();
    }, 6000);
  }

  setInterval(createHeart, 300);
});
</script>

</body>
</html>
