<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<title>ملاك ❤️</title>

<style>
body {
  font-family: Arial;
  background: #fff0f5;
  margin: 0;
  overflow-x: hidden;
}

.header {
  background: #ff4d6d;
  color: white;
  padding: 20px;
  font-size: 28px;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.content {
  padding: 30px;
  position: relative;
  z-index: 2;
  line-height: 1.8;
}

.infobox {
  float: left;
  width: 260px;
  background: #ffe5ec;
  border: 2px solid #ffccd5;
  padding: 15px;
  margin: 10px;
  text-align: center;
  border-radius: 12px;
}
.infobox img {
  width: 100%;
  border-radius: 12px;
}

h1, h2 {
  color: #ff4d6d;
}

/* القلوب */
.heart {
  position: fixed;
  bottom: -20px;
  font-weight: bold;
  animation: floatUp 6s linear forwards;
  opacity: 0.8;
}

@keyframes floatUp {
  0% { transform: translateY(0) scale(1); opacity: 0.8; }
  50% { transform: scale(1.3); }
  100% { transform: translateY(-110vh) scale(1.5); opacity: 0; }
}

/* رسائل الحب الصغيرة */
.love-message {
  position: fixed;
  font-size: 16px;
  color: #ff3366;
  animation: floatMsg 5s linear forwards;
}

@keyframes floatMsg {
  0% { transform: translateY(0); opacity: 0; }
  10% { opacity: 1; }
  90% { opacity: 1; }
  100% { transform: translateY(-80vh); opacity: 0; }
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
ملاك مو مجرد بنت في حياتي… هي الشيء اللي غيرني بالكامل.
أنا سعد، ومن يوم عرفتها وأنا أشوف الدنيا أجمل 💕
</p>

<h2>جمالها</h2>
<p>
جمالها يفوق أي كلام… هي فعلاً "جمال العالم كله".
ضحكتها لحالها تخلي قلبي يطير، ونظرتها كلها ثقة وهدوء.
</p>

<h2>ذكائها وثقتها</h2>
<p>
ملاك ذكية وفاهمة كل شيء حواليها… طريقة تفكيرها، كلامها، أسلوبها، كله يدل على أنها مميزة.
وهي واثقة بنفسها بطريقة تلهم أي شخص يعرفها.
</p>

<h2>دلعها واهتمامها</h2>
<p>
دلعها واهتمامها عليّ مش أي حد يحس فيه… تحسسني إني أهم شخص عندها 😍
</p>

<h2>حبي لها</h2>
<p>
أنا أحبها، أهيم فيها، وأؤمن بها… وجودها معايا نعمة حقيقية.
</p>

<h2>رسالة أخيرة</h2>
<p>
يا ملاك… أحبك من كل قلبي ❤️  
أنتِ أجمل شيء صار لي، وأتمنى أظل أقدّرك وأحبك كل يوم.  
وجودك بحياتي يخليني أحس بالسعادة والأمان، وأهيم فيك أكثر مما تتخيلي.
</p>

</div>

<script>
// إنشاء قلوب متصاعدة بألوان وأحجام مختلفة
window.addEventListener("load", function() {

  const colors = ["#ff4d6d","#ff66a3","#ff99c9","#ff3366","#ff1a75"];
  const messages = ["أحبك 💖","أهيم فيك ❤️","أنتِ قلبي 💕","أنتِ أجمل شيء 🌹"];

  function createHeart() {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML = "❤️";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.fontSize = (15 + Math.random() * 25) + "px";
    heart.style.color = colors[Math.floor(Math.random()*colors.length)];
    document.body.appendChild(heart);
    setTimeout(() => heart.remove(), 6000);
  }

  function createLoveMsg() {
    const msg = document.createElement("div");
    msg.classList.add("love-message");
    msg.innerHTML = messages[Math.floor(Math.random()*messages.length)];
    msg.style.left = Math.random() * 80 + "vw";
    document.body.appendChild(msg);
    setTimeout(() => msg.remove(), 5000);
  }

  setInterval(createHeart, 200); // سرعة القلوب
  setInterval(createLoveMsg, 2000); // ظهور رسائل الحب
});
</script>

</body>
</html>
