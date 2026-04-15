# Math-vidhyarthi-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Math Vidyarthi | Class 12 Maths All Boards</title>

<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<style>
body{margin:0;font-family:Arial;background:#f2f4f7}
header,footer{background:#0d47a1;color:#fff;text-align:center;padding:12px}
nav{background:#1565c0;padding:8px;text-align:center}
nav button{margin:4px;padding:8px;border:none;border-radius:4px}
.section{display:none;padding:15px}
.box{background:#fff;padding:15px;margin-bottom:15px;border-radius:5px;box-shadow:0 0 5px #ccc}
button{padding:8px;background:#0d47a1;color:#fff;border:none;border-radius:4px;margin-top:5px}
select,input,textarea{width:100%;padding:8px;margin:5px 0}
.chat-box{height:250px;overflow:auto;border:1px solid #ccc;padding:10px}
.user{color:blue}
.bot{color:green}
.correct{color:green}
.wrong{color:red}
</style>
</head>

<body>

<header>
<h2>📘 Math Vidyarthi</h2>
<p>Class 12 Maths – All Boards</p>
</header>

<nav>
<button onclick="show('home')">Home</button>
<button onclick="show('chapters')">Chapters</button>
<button onclick="show('mcq')">MCQ</button>
<button onclick="show('ai')">AI Chat</button>
<button onclick="show('support')">Support</button>
</nav>

<!-- HOME -->
<div id="home" class="section" style="display:block">
<div class="box">
<h3>Welcome Student 👋</h3>
<p>✔ Step-by-step Maths Help</p>
<p>✔ AI Doubt Solver</p>
<p>✔ Customer Support</p>
</div>
</div>

<!-- CHAPTER -->
<div id="chapters" class="section">
<div class="box">
<h3>Determinants</h3>
\[
\begin{vmatrix}
1 & 2 & 3\\
4 & 5 & 6\\
7 & 8 & 9
\end{vmatrix}
\]
<button onclick="document.getElementById('sol').style.display='block'">Show Solution</button>
<div id="sol" style="display:none">
\[
= -3 + 12 - 9 = 0
\]
<b>Answer: 0</b>
</div>
</div>
</div>

<!-- MCQ -->
<div id="mcq" class="section">
<div class="box">
<h3>MCQ Test</h3>
<p>Determinant of square matrix is?</p>
<button onclick="ans(true)">Scalar</button>
<button onclick="ans(false)">Vector</button>
<button onclick="ans(false)">Matrix</button>
<p id="mcqres"></p>
</div>
</div>

<!-- AI CHAT -->
<div id="ai" class="section">
<div class="box">
<h3>🤖 AI Maths Chat</h3>

<div class="chat-box" id="chat"></div>

<input id="q" placeholder="Type maths question e.g. integral of x^2">
<button onclick="chat()">Send</button>

<p><small>⚠ Demo AI – Class 12 Maths only</small></p>
</div>
</div>

<!-- SUPPORT -->
<div id="support" class="section">
<div class="box">
<h3>📞 Customer Support</h3>
<input placeholder="Your Name">
<input placeholder="Email / Phone">
<textarea rows="4" placeholder="Describe your issue or problem"></textarea>
<button onclick="alert('Support request submitted ✔')">Submit</button>

<p>
📧 Email: support@mathvidyarthi.com <br>
📱 WhatsApp: +91-XXXXXXXXXX
</p>
</div>
</div>

<footer>
© 2026 Math Vidyarthi | Free Education for All
</footer>

<script>
function show(id){
document.querySelectorAll('.section').forEach(s=>s.style.display='none');
document.getElementById(id).style.display='block';
}

function ans(c){
document.getElementById("mcqres").innerHTML =
c ? "<span class='correct'>Correct ✔</span>" : "<span class='wrong'>Wrong ✖</span>";
}

function chat(){
let q=document.getElementById("q").value.toLowerCase();
let chat=document.getElementById("chat");
chat.innerHTML+="<div class='user'>You: "+q+"</div>";

let reply="Please ask Class 12 Maths question.";
if(q.includes("integral")) reply="∫x² dx = x³/3 + C";
if(q.includes("determinant")) reply="Determinant is a scalar value of square matrix.";
if(q.includes("probability")) reply="Probability = favourable outcomes / total outcomes.";

chat.innerHTML+="<div class='bot'>AI: "+reply+"</div>";
document.getElementById("q").value="";
chat.scrollTop=chat.scrollHeight;
}
</script>

</body>
</html>
