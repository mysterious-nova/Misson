# Misson
On the mission <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Baby Says Hello</title>

<style>
body{
    background:#ffeef2;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    font-family:Arial;
}

.card{
    text-align:center;
    background:white;
    padding:30px;
    border-radius:20px;
    box-shadow:0 5px 15px rgba(0,0,0,0.2);
}

.baby{
    font-size:80px;
}

.flower{
    font-size:60px;
}

.hello{
    margin-top:10px;
    font-size:30px;
    color:#ff4d6d;
    animation: wave 1.5s infinite;
}

@keyframes wave{
    0%{transform:scale(1);}
    50%{transform:scale(1.2);}
    100%{transform:scale(1);}
}
</style>
</head>

<body>

<div class="card">
    <div class="baby">👶</div>
    <div class="flower">🌸</div>
    <div class="hello">Hello 🌷</div>
</div>

</body>
</html>
