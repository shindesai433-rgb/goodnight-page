<!DOCTYPE html>
<html>
<head>
<title>Good Night</title>

<style>
body{
    margin:0;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    font-family:Arial;
    background:linear-gradient(#0f2027,#203a43,#2c5364);
    color:white;
    text-align:center;
}

.card{
    background:rgba(255,255,255,0.1);
    padding:40px;
    border-radius:20px;
    backdrop-filter:blur(5px);
}

button{
    margin-top:20px;
    padding:10px 20px;
    border:none;
    border-radius:20px;
    background:#ff7aa2;
    color:white;
    cursor:pointer;
}

.hidden{
    display:none;
    margin-top:15px;
}
</style>

</head>

<body>

<div class="card">

<h2>Good Night Amrutha</h2>

<p>
I hope today was kind to you.
If not, tomorrow will try again.
</p>

<button onclick="showMessage()">
Tap before you sleep
</button>

<p id="extra" class="hidden">
Just a reminder before the day ends  
someone somewhere is smiling because you exist.
</p>

</div>

<script>

function showMessage(){
document.getElementById("extra").style.display="block";
}

</script>

</body>
</html># goodnight-page