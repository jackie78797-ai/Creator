<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>MarketJo Creator Network</title>

<style>

body{
margin:0;
font-family:Arial;
background:#87CEEB;
color:black;
}

header{
background:black;
color:white;
padding:25px;
text-align:center;
}

header h1{
margin:0;
font-size:32px;
}

header p{
margin-top:8px;
color:#ddd;
}

.container{
max-width:900px;
margin:auto;
padding:30px;
}

.card{
background:white;
padding:25px;
margin-bottom:25px;
border-radius:10px;
box-shadow:0 5px 15px rgba(0,0,0,0.15);
}

.card h2{
margin-top:0;
}

input, textarea{
width:100%;
padding:12px;
margin-top:8px;
margin-bottom:15px;
border:1px solid #ccc;
border-radius:5px;
}

button{
background:black;
color:white;
padding:15px;
border:none;
border-radius:5px;
cursor:pointer;
font-size:16px;
}

button:hover{
background:#333;
}

footer{
text-align:center;
padding:20px;
color:black;
}

</style>
</head>

<body>

<header>
<h1>MarketJo Creator Network</h1>
<p>Connecting Beauty Creators With Brands</p>
</header>

<div class="container">

<div class="card">
<h2>Creator Information</h2>

<label>Creator Name</label>
<input id="name">

<label>Instagram Profile</label>
<input id="instagram">

<label>YouTube Channel</label>
<input id="youtube">

</div>


<div class="card">
<h2>Profile Stats</h2>

<label>Total Followers</label>
<input id="followers">

<label>Average Reel Views</label>
<input id="reelviews">

<label>Story Views</label>
<input id="storyviews">

</div>


<div class="card">
<h2>Audience Details</h2>

<label>Audience Gender %</label>
<input id="gender">

<label>Top Countries</label>
<input id="countries">

<label>Top Cities</label>
<input id="cities">

</div>


<div class="card">
<h2>Niche</h2>

<label>Your Niche</label>
<input id="niche">

<label>Worked with Brands Before?</label>
<input id="brands">

</div>


<div class="card">
<h2>Rates</h2>

<label>Reel Rate</label>
<input id="reel">

<label>Reel + Story Rate</label>
<input id="combo">

<label>Full Campaign</label>
<input id="campaign">

</div>


<div class="card">
<h2>Submit Profile</h2>

<button onclick="send()">Submit to WhatsApp</button>

</div>

</div>

<footer>
© MarketJo Creator Network
</footer>


<script>

function send(){

let message=

"NEW CREATOR APPLICATION\n\n"+

"Name: "+document.getElementById("name").value+"\n"+
"Instagram: "+document.getElementById("instagram").value+"\n"+
"YouTube: "+document.getElementById("youtube").value+"\n\n"+

"Followers: "+document.getElementById("followers").value+"\n"+
"Reel Views: "+document.getElementById("reelviews").value+"\n"+
"Story Views: "+document.getElementById("storyviews").value+"\n\n"+

"Audience Gender: "+document.getElementById("gender").value+"\n"+
"Countries: "+document.getElementById("countries").value+"\n"+
"Cities: "+document.getElementById("cities").value+"\n\n"+

"Niche: "+document.getElementById("niche").value+"\n"+
"Brand Experience: "+document.getElementById("brands").value+"\n\n"+

"Reel Rate: "+document.getElementById("reel").value+"\n"+
"Combo Rate: "+document.getElementById("combo").value+"\n"+
"Campaign Rate: "+document.getElementById("campaign").value


window.open(
"https://wa.me/917865967201?text="+encodeURIComponent(message)
)

}

</script>

</body>
</html>
