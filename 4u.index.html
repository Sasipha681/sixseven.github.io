<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>ข้อความลับ</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Mali:wght@400;600&display=swap">
<style>
:root{--bg1:#dff2ff;--bg2:#f4fbff;--ink:#2b4a66;--muted:#6f8fa8;--card:#ffffff;--line:#b9dcf5;--accent:#5ab4ee;--accent-ink:#ffffff;--err:#e0627a;color-scheme:light}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg1:#16263a;--bg2:#1c3149;--ink:#e6f3ff;--muted:#9bbbd6;--card:#233b56;--line:#3a5e82;--accent:#7cc7f5;--accent-ink:#10253a;--err:#ff8fa3;color-scheme:dark}}
:root[data-theme="dark"]{--bg1:#16263a;--bg2:#1c3149;--ink:#e6f3ff;--muted:#9bbbd6;--card:#233b56;--line:#3a5e82;--accent:#7cc7f5;--accent-ink:#10253a;--err:#ff8fa3;color-scheme:dark}
*{box-sizing:border-box}
html,body{height:100%;margin:0}
body{background:linear-gradient(160deg,var(--bg1),var(--bg2));color:var(--ink);font-family:"Mali","Sarabun","Noto Sans Thai",system-ui,sans-serif;display:flex;align-items:center;justify-content:center;padding:env(safe-area-inset-top,0px) 20px env(safe-area-inset-bottom,0px);position:relative;overflow-x:hidden}
.cloud{position:fixed;font-size:2.2rem;opacity:.7;pointer-events:none}
.c1{top:10%;left:8%}.c2{top:18%;right:10%;font-size:1.6rem}.c3{bottom:12%;left:14%;font-size:1.8rem}.c4{bottom:20%;right:8%}
main{width:100%;max-width:400px;text-align:center;position:relative}
.panel{background:var(--card);border:3px solid var(--line);border-radius:28px;padding:2rem 1.4rem;box-shadow:0 8px 0 var(--line)}
.icon{font-size:3rem;margin-bottom:.2rem}
h1{font-size:1.5rem;margin:0 0 .4rem}
p{color:var(--muted);margin:0 0 1.4rem;line-height:1.7}
.code{display:flex;gap:14px;justify-content:center;margin-bottom:.8rem}
.code input{width:72px;height:88px;font:600 2.4rem/1 "Mali",sans-serif;text-align:center;color:var(--ink);background:var(--bg2);border:3px solid var(--line);border-radius:22px;outline:none;transition:border-color .15s,transform .15s}
.code input:focus{border-color:var(--accent);transform:scale(1.06)}
.code.shake{animation:shake .35s}
@keyframes shake{25%{transform:translateX(-8px)}75%{transform:translateX(8px)}}
@media (prefers-reduced-motion:reduce){.code.shake{animation:none}.code input:focus{transform:none}}
#err{min-height:1.5em;color:var(--err);font-size:.95rem;margin:0 0 .8rem}
button{font:inherit;font-weight:600;background:var(--accent);color:var(--accent-ink);border:0;border-radius:999px;padding:.8rem 2.2rem;cursor:pointer;box-shadow:0 4px 0 var(--line)}
button:active{transform:translateY(2px);box-shadow:0 2px 0 var(--line)}
button:focus-visible,input:focus-visible{outline:3px solid var(--ink);outline-offset:3px}
#msg{display:none;text-align:left;line-height:1.95;font-size:1.05rem}
#msg.show{display:block}
#msg .end{display:block;margin-top:1rem;text-align:center;font-weight:600;font-size:1.2rem;color:var(--accent)}
</style>
</head>
<body>
<span class="cloud c1">☁️</span><span class="cloud c2">✨</span><span class="cloud c3">☁️</span><span class="cloud c4">🩵</span>
<main>
  <section class="panel" id="lock">
    <div class="icon">🔐</div>
    <h1>ใส่รหัส 2 หลักนะ</h1>
    <p>พิมพ์ตัวเลขเพื่อเปิดอ่านข้อความ</p>
    <div class="code" id="code">
      <input inputmode="numeric" pattern="[0-9]" maxlength="1" aria-label="หลักที่ 1" autocomplete="off">
      <input inputmode="numeric" pattern="[0-9]" maxlength="1" aria-label="หลักที่ 2" autocomplete="off">
    </div>
    <div id="err" role="alert"></div>
    <button id="go" type="button">เปิดอ่านเลย</button>
  </section>
  <section class="panel" id="msg" aria-live="polite">
    <div>คืองี้ใช่ไหม คือเมื่อวานก่อนอ่ะเราบ่นกับพ่อแม่ว่า เราอยากได้รถ และทีนี้พ่อแม่เราก็พูดว่า “เดี๋ยวพรุ่งนี้พาไปซื้อรถนะ” และทีนี้วันนี้เราก็มาซื้อรถจริงๆ มีหลายคันมาก เลือกไม่ถูกเลยแหละ แบบมันหลายคันจริงๆ แต่เรามีคันที่ชอบนะ คันถึงเธอทุกวิด
    <span class="end">“คิดถึงเธอทุกวัน” &gt;&lt; 🩵</span></div>
  </section>
</main>
<script>
var PASSCODE = "67";
var boxes = Array.prototype.slice.call(document.querySelectorAll(".code input"));
var err = document.getElementById("err");
var wrap = document.getElementById("code");
boxes.forEach(function(b, i){
  b.addEventListener("input", function(){
    b.value = b.value.replace(/\D/g, "").slice(0,1);
    err.textContent = "";
    if (b.value && i < boxes.length - 1) boxes[i+1].focus();
    if (boxes.every(function(x){return x.value;})) check();
  });
  b.addEventListener("keydown", function(e){
    if (e.key === "Backspace" && !b.value && i > 0) boxes[i-1].focus();
    if (e.key === "Enter") check();
  });
});
document.getElementById("go").addEventListener("click", check);
function check(){
  var v = boxes.map(function(x){return x.value;}).join("");
  if (v.length < 2){ err.textContent = "กรอกให้ครบ 2 หลักนะ"; return; }
  if (v === PASSCODE){
    document.getElementById("lock").style.display = "none";
    document.getElementById("msg").classList.add("show");
  } else {
    err.textContent = "รหัสไม่ถูกนะ ลองใหม่อีกครั้ง";
    wrap.classList.remove("shake"); void wrap.offsetWidth; wrap.classList.add("shake");
    boxes.forEach(function(x){x.value="";}); boxes[0].focus();
  }
}
boxes[0].focus();
</script>
</body>
</html>
