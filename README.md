<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Virelah Premium Learning System</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;800&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box}
body{font-family:'Poppins',sans-serif;background:#0f0f0f;color:white;overflow-x:hidden}

/* HERO */
.hero{position:relative;height:100vh;display:flex;justify-content:center;align-items:center;text-align:center;padding:20px}
.hero video{position:absolute;top:0;left:0;width:100%;height:100%;object-fit:cover;z-index:-2}
.overlay{position:absolute;width:100%;height:100%;background:rgba(0,0,0,0.75);z-index:-1}

.hero-content{max-width:900px;animation:fadeIn 1.5s ease-in-out}
@keyframes fadeIn{from{opacity:0;transform:translateY(40px)}to{opacity:1;transform:translateY(0)}}

h1{font-size:48px;font-weight:800;margin-bottom:20px}
.highlight{color:#ffd369}
.hero p{font-size:20px;margin-bottom:30px;opacity:0.9}

.cta{
display:inline-block;padding:18px 45px;background:#ffd369;color:#000;
border-radius:50px;font-weight:700;text-decoration:none;
animation:pulse 2s infinite;transition:0.3s}
@keyframes pulse{0%{transform:scale(1)}50%{transform:scale(1.08)}100%{transform:scale(1)}}
.cta:hover{background:white}

.timer{margin-top:20px;font-size:18px;color:#ff4d4d;font-weight:600}

.section{padding:80px 20px;text-align:center}
.section.dark{background:#151515}
.section h2{font-size:36px;margin-bottom:20px}

.features{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;max-width:1100px;margin:auto;margin-top:40px}

.card{
background:#1e1e1e;padding:30px;border-radius:15px;
box-shadow:0 10px 30px rgba(0,0,0,0.4);transition:0.3s}
.card:hover{transform:translateY(-10px)}

.price-box{background:#111;padding:80px 20px;text-align:center}
.price{font-size:60px;font-weight:800;margin:20px 0;color:#ffd369}

.email-box input{
padding:15px;width:250px;border-radius:30px;border:none;margin-right:10px}
.email-box button{
padding:15px 25px;border:none;border-radius:30px;
background:#ffd369;font-weight:600;cursor:pointer}

.social a{color:#ffd369;margin:0 10px;text-decoration:none;font-weight:600}

footer{background:#000;padding:30px;text-align:center;font-size:14px;opacity:0.7}

@media(max-width:768px){
h1{font-size:32px}
.hero{height:auto;padding:100px 20px}
}
</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
<video autoplay muted loop>
<source src="https://www.w3schools.com/howto/rain.mp4" type="video/mp4">
</video>
<div class="overlay"></div>

<div class="hero-content">
<h1>Raise a <span class="highlight">Confident & Intelligent</span> Child</h1>
<p>Scientifically structured printable learning system trusted by 5,000+ parents worldwide.</p>
<a href="#pricing" class="cta">Get Instant Access Now</a>

<div class="timer">
Offer Expires In: <span id="countdown"></span>
</div>
</div>
</section>

<!-- AUTHORITY -->
<section class="section dark">
<h2>Why This System Works</h2>
<div class="features">
<div class="card"><h3>Designed By Experts</h3><p>Built with child psychology & proven learning frameworks.</p></div>
<div class="card"><h3>Proven Results</h3><p>Parents report focus improvement within weeks.</p></div>
<div class="card"><h3>Instant Access</h3><p>Download immediately after secure payment.</p></div>
</div>
</section>

<!-- TESTIMONIALS -->
<section class="section">
<h2>What Parents Are Saying</h2>
<div class="features">
<div class="card">⭐⭐⭐⭐⭐<p>"My daughter improved reading skills fast!"</p><strong>- Sarah M.</strong></div>
<div class="card">⭐⭐⭐⭐⭐<p>"Finally structured worksheets that work."</p><strong>- Amanda L.</strong></div>
<div class="card">⭐⭐⭐⭐⭐<p>"Worth every dollar."</p><strong>- Jessica R.</strong></div>
</div>
</section>

<!-- BEFORE AFTER -->
<section class="section dark">
<h2>Real Transformation</h2>
<div class="features">
<div class="card"><h3>Before</h3><p>Low focus & inconsistent learning.</p></div>
<div class="card"><h3>After</h3><p>Confident, structured & improved performance.</p></div>
</div>
</section>

<!-- EMAIL CAPTURE -->
<section class="section">
<h2>Get Free Sample Pack</h2>
<p>Enter your email below:</p>
<div class="email-box">
<!-- Replace below form with Mailchimp Embedded Form -->
<input type="email" placeholder="Enter your email">
<button>Send Sample</button>
</div>
</section>

<!-- PRICING -->
<section class="price-box" id="pricing">
<h2>Premium Bundle Access</h2>
<div class="price">$47</div>

<form action="https://www.paypal.com/cgi-bin/webscr" method="post">
<input type="hidden" name="cmd" value="_xclick">
<input type="hidden" name="business" value="infotanmoy1982@gmail.com">
<input type="hidden" name="item_name" value="Virelah Premium Learning System">
<input type="hidden" name="amount" value="47.00">
<input type="hidden" name="currency_code" value="USD">
<input type="hidden" name="return" value="https://yourusername.github.io/thankyou.html">
<input type="submit" value="Secure Payment via PayPal" class="cta">
</form>

<br><br>
<a href="https://virelah.gumroad.com" class="cta">Buy via Gumroad</a>

<!-- UPSELL -->
<div style="margin-top:40px">
<h3>🔥 Add Advanced Pack for $27</h3>
<form action="https://www.paypal.com/cgi-bin/webscr" method="post">
<input type="hidden" name="cmd" value="_xclick">
<input type="hidden" name="business" value="infotanmoy1982@gmail.com">
<input type="hidden" name="item_name" value="Advanced Activity Pack">
<input type="hidden" name="amount" value="27.00">
<input type="hidden" name="currency_code" value="USD">
<input type="submit" value="Add To My Order" class="cta">
</form>
</div>

</section>

<!-- SOCIAL -->
<section class="section dark">
<h2>Follow Us</h2>
<div class="social">
<a href="#">Facebook</a>
<a href="#">Instagram</a>
<a href="#">Pinterest</a>
</div>
</section>

<footer>
© 2026 Virelah Premium Learning System. All Rights Reserved.
</footer>

<!-- COUNTDOWN -->
<script>
var countDownDate=new Date().getTime()+(24*60*60*1000);
var x=setInterval(function(){
var now=new Date().getTime();
var distance=countDownDate-now;
var h=Math.floor((distance%(1000*60*60*24))/(1000*60*60));
var m=Math.floor((distance%(1000*60*60))/(1000*60));
var s=Math.floor((distance%(1000*60))/1000);
document.getElementById("countdown").innerHTML=h+"h "+m+"m "+s+"s";
if(distance<0){clearInterval(x);document.getElementById("countdown").innerHTML="Expired";}
},1000);
</script>

<!-- FACEBOOK PIXEL -->
<script>
!function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?
n.callMethod.apply(n,arguments):n.queue.push(arguments)};
if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';
n.queue=[];t=b.createElement(e);t.async=!0;
t.src=v;s=b.getElementsByTagName(e)[0];
s.parentNode.insertBefore(t,s)}(window, document,'script',
'https://connect.facebook.net/en_US/fbevents.js');
fbq('init','1275521451105310');
fbq('track','PageView');
</script>

<!-- GOOGLE ANALYTICS -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
window.dataLayer=window.dataLayer||[];
function gtag(){dataLayer.push(arguments);}
gtag('js',new Date());
gtag('config','GA_MEASUREMENT_ID');
</script>

</body>
</html>
