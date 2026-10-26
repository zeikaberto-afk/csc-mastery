
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#fff4c7">
<title>CSC Mastery | Your Exam Journey</title>
<style>
:root {
  --pink:#ffd6e5;
  --pink-dark:#ef79a5;
  --yellow:#ffe990;
  --cream:#fffaf0;
  --ink:#343044;
  --muted:#777486;
  --white:#ffffff;
  --green:#d9f5df;
  --red:#ffe0e0;
}
*{box-sizing:border-box}
body{
  margin:0;background:var(--cream);color:var(--ink);
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;
  line-height:1.5;
}
button{font:inherit;cursor:pointer}
button:focus-visible{outline:3px solid #8062c8;outline-offset:3px}
.topbar{
  background:var(--white);padding:14px 18px;
  display:flex;align-items:center;justify-content:space-between;
  border-bottom:1px solid #f0e8e7;position:sticky;top:0;z-index:5;
}
.brand{display:flex;align-items:center;gap:9px;font-weight:900;font-size:19px}
.logo{background:var(--yellow);border-radius:13px;padding:7px;font-size:23px}
.brand span:last-child{color:var(--pink-dark)}
.small-pill{background:#fff0a9;border-radius:30px;padding:7px 10px;font-size:12px;font-weight:800}
main{max-width:960px;margin:auto;padding:20px 16px 45px}
.hero{
  background:linear-gradient(130deg,#ffe0eb,#fff0a8);
  border-radius:27px;padding:25px 20px;position:relative;overflow:hidden;
}
.hero-content{position:relative;z-index:1;max-width:540px}
.eyebrow{font-size:12px;font-weight:900;letter-spacing:1.4px;text-transform:uppercase}
h1{font-size:clamp(30px,7vw,48px);line-height:1.1;margin:12px 0}
.hero p{color:#55495d;max-width:430px}
.cat{
  position:absolute;right:13px;bottom:6px;font-size:92px;
  transform:rotate(-7deg);filter:drop-shadow(0 5px 2px #a36a5930);
}
.btn{
  border:0;border-radius:14px;padding:13px 18px;font-weight:850;
  background:var(--ink);color:white;
}
.btn-pink{background:var(--pink-dark);color:#fff}
.btn-yellow{background:var(--yellow);color:var(--ink)}
.btn-light{background:white;color:var(--ink);border:1px solid #eee4e5}
.btn:disabled{opacity:.45;cursor:not-allowed}
.section-head{display:flex;align-items:end;justify-content:space-between;gap:10px;margin:28px 0 14px}
h2{font-size:22px;margin:0}
.muted{color:var(--muted);font-size:13px}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:16px}
.stat{background:white;border:1px solid #f0e8e7;border-radius:18px;padding:13px}
.stat strong{display:block;font-size:22px}
.stat span{font-size:11px;color:var(--muted)}
.grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:12px}
.card{background:white;border:1px solid #f0e8e7;border-radius:20px;padding:16px}
.subject-icon{font-size:29px}
.card h3{margin:8px 0 4px;font-size:17px}
.card p{font-size:13px;color:var(--muted);margin:0 0 13px}
.card .btn{width:100%;padding:11px 8px;font-size:13px}
.progress-track{height:8px;background:#eee8e7;border-radius:20px;overflow:hidden;margin-top:9px}
.progress-fill{height:100%;width:0;background:var(--pink-dark);transition:width .3s}
.panel{background:white;border:1px solid #f0e8e7;border-radius:23px;padding:20px;margin-top:18px}
.hidden{display:none!important}
.back{background:none;border:0;color:var(--muted);padding:0 0 15px;font-weight:700}
.question-meta{display:flex;justify-content:space-between;gap:8px;flex-wrap:wrap}
.question{font-size:21px;font-weight:850;margin:17px 0}
.answers{display:grid;gap:10px}
.answer{
  background:#fff;border:2px solid #eee7e7;border-radius:15px;
  padding:13px;text-align:left;color:var(--ink);font-weight:650;
}
.answer:hover{border-color:var(--pink-dark)}
.answer.correct{background:var(--green);border-color:#67bd80}
.answer.wrong{background:var(--red);border-color:#e88c8c}
.explanation{margin-top:15px;padding:15px;border-radius:16px;background:#fff6cf}
.explanation h3{margin:0 0 6px;font-size:16px}
.explanation p{margin:0;font-size:14px}
.quiz-footer{display:flex;justify-content:space-between;align-items:center;gap:10px;margin-top:18px}
.notice{font-size:12px;color:var(--muted)}
.membership{background:#fff0f5;border-radius:23px;padding:22px;margin-top:28px}
.price{font-size:35px;font-weight:950;margin:8px 0}
.price small{font-size:14px;font-weight:650}
footer{text-align:center;padding:22px 10px;color:var(--muted);font-size:12px}
#toast{font-size:13px;margin-top:12px;font-weight:700}
@media(min-width:650px){
 main{padding-top:28px}
 .hero{padding:38px}
 .cat{font-size:140px;right:35px;bottom:5px}
 .grid{grid-template-columns:repeat(3,minmax(0,1fr))}
 .panel{padding:27px}
}
@media(max-width:370px){
 .grid{grid-template-columns:1fr}
 .cat{font-size:65px;right:8px}
 .hero-content{max-width:85%}
}
</style>
</head>
<body>
<header class="topbar">
  <div class="brand"><span class="logo">🐱</span><span>CSC <span>Mastery</span></span></div>
  <span class="small-pill">🎓 EXAM PREP</span>
</header>

<main>
  <section id="home">
    <div class="hero">
      <div class="hero-content">
        <div class="eyebrow">Your future starts here ✨</div>
        <h1>Study smart.<br>Pass with confidence.</h1>
        <p>Small steps every day can bring you closer to your Civil Service Exam goal. Let's do this together!</p>
        <button class="btn" onclick="showSubjects()">Start studying →</button>
      </div>
      <div class="cat" aria-label="Cat wearing sunglasses">😎🐱</div>
    </div>

    <div class="stats">
      <div class="stat"><strong id="statDone">0</strong><span>Questions answered</span></div>
      <div class="stat"><strong id="statCorrect">0</strong><span>Correct answers</span></div>
      <div class="stat"><strong id="statRate">0%</strong><span>Accuracy</span></div>
    </div>

    <div class="section-head">
      <div><h2>Your learning corner 📚</h2><div class="muted">Choose a subject and practice at your pace.</div></div>
    </div>

    <div class="grid" id="subjects">
      <article class="card">
        <div class="subject-icon">🔢</div>
        <h3>Numerical Ability</h3>
        <p>Ratio, percentages, averages and number problems.</p>
        <div class="progress-track"><div class="progress-fill" id="progress-math"></div></div>
        <p id="count-math" style="margin-top:7px">Practice questions</p>
        <button class="btn btn-yellow" onclick="startQuiz('math')">Practice math →</button>
      </article>
      <article class="card">
        <div class="subject-icon">📝</div>
        <h3>Verbal Ability</h3>
        <p>Vocabulary, grammar and word relationships.</p>
        <div class="progress-track"><div class="progress-fill" id="progress-verbal"></div></div>
        <p id="count-verbal" style="margin-top:7px">Practice questions</p>
        <button class="btn btn-pink" onclick="startQuiz('verbal')">Practice English →</button>
      </article>
      <article class="card">
        <div class="subject-icon">🧠</div>
        <h3>Logical Reasoning</h3>
        <p>Patterns, logic and careful thinking.</p>
        <div class="progress-track"><div class="progress-fill" id="progress-logic"></div></div>
        <p id="count-logic" style="margin-top:7px">Practice questions</p>
        <button class="btn" onclick="startQuiz('logic')">Train your brain →</button>
      </article>
    </div>

    <section class="membership">
      <div class="eyebrow">Your study journey 💛</div>
      <h2>More practice, more confidence!</h2>
      <div class="price">₱49 <small>/ every 15 days</small></div>
      <p class="muted">Planned membership for extra reviewers and practice sets.</p>
      <p class="notice">Membership and payment features are not active yet. The lessons currently available on this demo site are open to everyone.</p>
      <button class="btn btn-light" onclick="membershipInfo()">Membership details</button>
      <div id="toast" role="status"></div>
    </section>
  </section>

  <section id="quiz" class="panel hidden">
    <button class="back" onclick="goHome()">← Back to subjects</button>
    <div class="question-meta">
      <span class="small-pill" id="quizSubject">Numerical Ability</span>
      <span class="muted" id="questionCount">Question 1</span>
    </div>
    <div class="progress-track"><div class="progress-fill" id="quizProgress"></div></div>
    <div id="quizArea">
      <div class="question" id="questionText"></div>
      <div class="answers" id="answerOptions"></div>
      <div id="explanation" class="explanation hidden" aria-live="polite">
        <h3 id="feedbackTitle">Great effort!</h3>
        <p id="explanationText"></p>
      </div>
      <div class="quiz-footer">
        <span class="notice" id="encouragement">You can do it! 🐱</span>
        <button class="btn" id="nextButton" disabled onclick="nextQuestion()">Next →</button>
      </div>
    </div>
    <div id="quizResults" class="hidden">
      <div style="font-size:55px;text-align:center">🏆🐱</div>
      <h2 style="text-align:center">Practice complete!</h2>
      <p id="resultText" style="text-align:center"></p>
      <p class="muted" style="text-align:center">Read the explanations and try again to improve your score.</p>
      <button class="btn btn-pink" style="width:100%" onclick="restartQuiz()">Try again</button>
      <button class="btn btn-light" style="width:100%;margin-top:10px" onclick="goHome()">Choose another subject</button>
    </div>
  </section>
</main>

<footer>
  <div style="font-size:25px">🐱💗💛</div>
  <strong>CSC Mastery</strong><br>
  Keep learning. Keep believing in yourself.<br><br>
  Independent study resource. Not affiliated with the Civil Service Commission.
</footer>

<script>
const lessons = {
math: {
  name:"Numerical Ability",
  questions:[
    {q:"The ratio of boys to girls in a class is 2:3. If there are 25 students, how many are girls?",
     a:["10","15","20","12"],correct:1,
     exp:"The ratio has 2 + 3 = 5 total parts. Each part is 25 ÷ 5 = 5 students. Girls represent 3 parts, so 3 × 5 = 15 girls."},
    {q:"What is 20% of 350?",
     a:["35","60","70","75"],correct:2,
     exp:"Convert 20% to 0.20, then multiply: 0.20 × 350 = 70."},
    {q:"The average of 12, 16, and 20 is:",
     a:["14","15","16","18"],correct:2,
     exp:"Add the numbers: 12 + 16 + 20 = 48. Divide by 3 numbers: 48 ÷ 3 = 16."},
    {q:"A bag costs ₱800 and has a 25% discount. What is the sale price?",
     a:["₱200","₱575","₱600","₱650"],correct:2,
     exp:"The discount is 800 × 0.25 = ₱200. Subtract it from the original price: 800 − 200 = ₱600."},
    {q:"If 5 notebooks cost ₱150, how much do 8 notebooks cost at the same price each?",
     a:["₱200","₱220","₱240","₱250"],correct:2,
     exp:"One notebook costs 150 ÷ 5 = ₱30. Eight notebooks cost 8 × 30 = ₱240."}
  ]
},
verbal: {
  name:"Verbal Ability",
  questions:[
    {q:"What is the closest meaning of 'diligent'?",
     a:["Lazy","Hardworking","Careless","Impatient"],correct:1,
     exp:"Diligent means showing careful and persistent effort. A diligent student works hard and studies consistently."},
    {q:"Choose the grammatically correct sentence.",
     a:["She go to school every day.","She going to school every day.","She goes to school every day.","She gone to school every day."],correct:2,
     exp:"With 'she' in the simple present tense, we normally add -s or -es to the verb: she goes."},
    {q:"Book is to reading as fork is to ____.",
     a:["Drawing","Eating","Writing","Sleeping"],correct:1,
     exp:"A book is used for reading. Similarly, a fork is used for eating. The relationship is an object and its usual function."},
    {q:"What is the opposite of 'scarce'?",
     a:["Rare","Limited","Abundant","Unusual"],correct:2,
     exp:"Scarce means insufficient or hard to find. Abundant means plentiful or available in large amounts."},
    {q:"Choose the correct sentence.",
     a:["Neither of the answers are correct.","Neither of the answers is correct.","Neither answers is correct.","Neither of answers are correct."],correct:1,
     exp:"'Neither' is treated as singular in this sentence, so the correct verb is 'is'."}
  ]
},
logic: {
  name:"Logical Reasoning",
  questions:[
    {q:"What number comes next? 2, 4, 8, 16, __",
     a:["18","24","30","32"],correct:3,
     exp:"Each number is multiplied by 2. Therefore, 16 × 2 = 32."},
    {q:"All roses are flowers. Some flowers fade quickly. Which statement must be true?",
     a:["All roses fade quickly.","No roses fade quickly.","All roses are flowers.","All flowers are roses."],correct:2,
     exp:"The first statement directly says all roses are flowers. We cannot conclude that roses fade quickly because the second statement only refers to some flowers."},
    {q:"Find the odd one out.",
     a:["Triangle","Square","Circle","Apple"],correct:3,
     exp:"A triangle, square, and circle are geometric shapes. An apple is a fruit."},
    {q:"If today is Monday, what day will it be 10 days from today?",
     a:["Wednesday","Thursday","Friday","Saturday"],correct:1,
     exp:"Seven days after Monday is Monday again. Three additional days bring us to Thursday."},
    {q:"Ana is taller than Ben. Ben is taller than Carlo. Who is the shortest?",
     a:["Ana","Ben","Carlo","Cannot be determined"],correct:2,
     exp:"Ana > Ben > Carlo in height. Carlo is shorter than both Ana and Ben, so Carlo is the shortest."}
  ]
}
};

let category="math", index=0, score=0, answered=false, runAnswers=0;
let stats={done:0,correct:0};
let progress={math:0,verbal:0,logic:0};

function showSubjects(){
  document.getElementById("home").classList.remove("hidden");
  document.getElementById("quiz").classList.add("hidden");
  window.scrollTo({top:0,behavior:"smooth"});
}
function goHome(){showSubjects();}

function startQuiz(key){
  category=key; index=0; score=0; runAnswers=0;
  document.getElementById("home").classList.add("hidden");
  document.getElementById("quiz").classList.remove("hidden");
  document.getElementById("quizArea").classList.remove("hidden");
  document.getElementById("quizResults").classList.add("hidden");
  renderQuestion();
  window.scrollTo({top:0,behavior:"smooth"});
}
function renderQuestion(){
  const lesson=lessons[category], item=lesson.questions[index];
  answered=false;
  document.getElementById("quizSubject").textContent=lesson.name;
  document.getElementById("questionCount").textContent=`Question ${index+1} of ${lesson.questions.length}`;
  document.getElementById("quizProgress").style.width=(index/lesson.questions.length*100)+"%";
  document.getElementById("questionText").textContent=item.q;
  document.getElementById("explanation").classList.add("hidden");
  document.getElementById("nextButton").disabled=true;
  document.getElementById("nextButton").textContent=index===lesson.questions.length-1?"See results →":"Next →";
  document.getElementById("encouragement").textContent=["You can do it! 🐱","Take your time! 💛","Every question helps you grow! 🌱"][index%3];

  const options=document.getElementById("answerOptions");
  options.innerHTML="";
  item.a.forEach((answer,i)=>{
    const btn=document.createElement("button");
    btn.className="answer";
    btn.textContent=String.fromCharCode(65+i)+". "+answer;
    btn.onclick=()=>chooseAnswer(i,btn);
    options.appendChild(btn);
  });
}
function chooseAnswer(choice,button){
  if(answered)return;
  answered=true;
  const item=lessons[category].questions[index];
  const buttons=document.querySelectorAll(".answer");
  buttons.forEach((b,i)=>{
    b.disabled=true;
    if(i===item.correct)b.classList.add("correct");
  });
  stats.done++; runAnswers++;
  progress[category]++;
  if(choice===item.correct){
    score++; stats.correct++;
    document.getElementById("feedbackTitle").textContent="Correct! Amazing job! 🎉";
  }else{
    button.classList.add("wrong");
    document.getElementById("feedbackTitle").textContent="Not quite, but keep learning! 💗";
  }
  document.getElementById("explanationText").textContent=item.exp;
  document.getElementById("explanation").classList.remove("hidden");
  document.getElementById("nextButton").disabled=false;
  updateStats();
}
function nextQuestion(){
  if(!answered)return;
  index++;
  if(index>=lessons[category].questions.length){
    document.getElementById("quizArea").classList.add("hidden");
    document.getElementById("quizResults").classList.remove("hidden");
    document.getElementById("quizProgress").style.width="100%";
    document.getElementById("resultText").textContent=`You got ${score} out of ${lessons[category].questions.length} correct. ${score===lessons[category].questions.length?"Perfect score! You're on fire! 🔥":score>=3?"Good work! Review the explanations and keep practicing.":"Good effort! Review the explanations, then try again. You can improve!"}`;
    updateStats();
  }else renderQuestion();
}
function restartQuiz(){startQuiz(category);}
function updateStats(){
  document.getElementById("statDone").textContent=stats.done;
  document.getElementById("statCorrect").textContent=stats.correct;
  document.getElementById("statRate").textContent=stats.done?Math.round(stats.correct/stats.done*100)+"%":"0%";
  ["math","verbal","logic"].forEach(key=>{
    const total=lessons[key].questions.length;
    document.getElementById("progress-"+key).style.width=Math.min(progress[key]/total*100,100)+"%";
    document.getElementById("count-"+key).textContent=progress[key]+" questions attempted";
  });
}
function membershipInfo(){
  document.getElementById("toast").textContent="💛 Membership checkout is coming soon. No payment is collected on this demo website.";
}
updateStats();
</script>
</body>
</html>
