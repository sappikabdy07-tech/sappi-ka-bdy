<!DOCTYPE html>
<html>
<head>
<title>Birthday Quiz for Sapna 🎂</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src="https://cdn.jsdelivr.net/npm/emailjs-com@3/dist/email.min.js"></script>
<style>
body{
    font-family: Arial, sans-serif;
    text-align:center;
    padding:30px;
    background:url('https://lh3.googleusercontent.com/pw/AP1GczOIEP67lMpx5UEDzv9T7YF24x-_K8ZAzKlPBIUqgpXYP49OeRQ66Pw9v-eB_bvm3WyZMrOxz5NpfcreM8KxO2taldgbQSWHny99Q-wgeonZSuxwKOoM3AHbLlYIUyE8n3NC5sLXpXO3PKAFpCbUHNw=w608-h913-s-no-gm?authuser=0') no-repeat center center fixed;
    background-size:cover;
}
#box{
    background:rgba(255,255,255,0.9);
    padding:30px;
    border-radius:15px;
    max-width:600px;
    margin:auto;
}
button{
    padding:10px 20px;
    font-size:16px;
    background:#ff4d88;
    color:white;
    border:none;
    border-radius:5px;
    cursor:pointer;
    margin-top:10px;
}
input{
    padding:10px;
    width:80%;
    margin-top:10px;
    font-size:16px;
    border-radius:5px;
    border:1px solid #ccc;
}
h2,p{color:#ff4d88;}
</style>
</head>

<body>
<div id="box">
<h2>Welcome!</h2>
<h2>Happy Birthday, Sapna! 🎉💖</h2>
<p>Hey Sapna! 🎉 On your 21st birthday, I wish you endless joy, laughter, and love. May every moment be filled with happiness, your dreams turn into reality, and your heart stay light forever. Enjoy this special day! 💖</p>
<button onclick="startQuiz()">Start Quiz</button>
</div>

<script>
emailjs.init("aTNGSy2m2EwEF-6m8"); // EmailJS key

let questions=[
"First of all, are you fine? 🙂",
"What was your first reaction when you saw the gift? 🎁",
"If this surprise had a secret planner, who would you suspect first? 👀",
"If you rate this gift (1-10), what would you give? ⭐",
"If you describe this gift in one word, what would it be? ✨",
"Did this surprise feel unexpected? 🎉",
"Are you enjoying this quiz? 😄",
"What is your favorite hobby or thing you love doing the most? 🎨🎵⚽",
"What is your favorite part of today’s celebration? 🎉",
"If you could make a wish right now, what would it be? 🌟",
"If your day today had a soundtrack, which song would it be? 🎵",
"Who is the first person you want to share your happiness with today? 💌",
"Last question… will you send me a smile? 😊"
];

let answers=[];
let q=0;

function startQuiz(){
    showQuestion();
}

function showQuestion(){
    document.getElementById("box").innerHTML=`
        <h2>${questions[q]}</h2>
        <input type="text" id="answer" placeholder="Type your answer">
        <br>
        <button onclick="nextQuestion()">Next</button>
    `;
}

function nextQuestion(){
    let ans=document.getElementById("answer").value.trim();
    if(ans===""){
        alert("Please enter an answer!");
        return;
    }
    answers.push(questions[q] + " → " + ans);
    q++;
    if(q<questions.length){
        showQuestion();
    } else{
        sendEmail();
        document.getElementById("box").innerHTML=`
            <h2>🎉 Quiz Completed 😄</h2>
            <p>Thank you for playing 💖</p>
            <button onclick="secretQuestion()">Continue</button>
        `;
    }
}

function sendEmail(){
    let allAnswers = answers.join("\n\n");
    emailjs.send("service_b20g8i1","template_clk64s8",{
        message: allAnswers,
        time: new Date().toLocaleString()
    })
    .then(function(response){
        console.log("SUCCESS!", response.status, response.text);
    }, function(error){
        console.log("FAILED...", error);
    });
}

function secretQuestion(){
    document.getElementById("box").innerHTML=`
        <h2>Do you want to know who I am? 🤫</h2>
        <button onclick="revealSecret('yes')">Yes</button>
        <button onclick="revealSecret('no')">No</button>
    `;
}

function revealSecret(ans){
    if(ans==="yes"){
        document.getElementById("box").innerHTML=`
            <h2>🎉 Surprise! 🎉</h2>
            <p>Kya kroge jaan kar? 😏</p>
            <img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="200">
            <p>Enjoy your special day 💖</p>
            <p>Thanks for participating! 🙏</p>
        `;
    } else{
        document.getElementById("box").innerHTML=`
            <h2>Alright 😄 Enjoy your day ✨</h2>
            <img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="200">
            <p>Thanks for participating! 🙏</p>
        `;
    }
}
</script>
</body>
</html>
