# birthday html  
  
<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>Happy Birthday Farr 💗</title>  
  
<style>  
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;700&display=swap');  
  
* {  
  box-sizing: border-box;  
  font-family: 'DM Sans', sans-serif;  
}  
  
body {  
  margin: 0;  
  background: linear-gradient(180deg, #ffe4ef, #fff6fb);  
  color: #333;  
  text-align: center;  
  overflow-x: hidden;  
}  
  
.container {  
  padding: 60px 20px 100px;  
}  
  
h1 {  
  font-size: 2.2rem;  
  margin-bottom: 10px;  
  animation: float 3s ease-in-out infinite;  
}  
  
.name {  
  font-size: 1.3rem;  
  opacity: 0.8;  
  margin-bottom: 30px;  
}  
  
.message {  
  font-size: 1.1rem;  
  background: rgba(255,255,255,0.7);  
  padding: 20px;  
  border-radius: 18px;  
  margin: 30px auto;  
  max-width: 320px;  
}  
  
.gallery {  
  display: grid;  
  grid-template-columns: repeat(2, 1fr);  
  gap: 12px;  
  margin-top: 40px;  
}  
  
.gallery img {  
  width: 100%;  
  border-radius: 16px;  
  object-fit: cover;  
  transform: rotate(-1deg);  
}  
  
.gallery img:nth-child(even) {  
  transform: rotate(2deg);  
}  
  
.footer {  
  margin-top: 50px;  
  font-size: 0.9rem;  
  opacity: 0.7;  
}  
  
@keyframes float {  
  0%, 100% { transform: translateY(0); }  
  50% { transform: translateY(-8px); }  
}  
</style>  
</head>  
  
<body>  
  
<audio autoplay loop>  
  <source src="alewife.mp3" type="audio/mpeg">  
</audio>  
  
<div class="container">  
  <h1>HAPPYY BIRTHDAYY FARR 💐</h1>  
  <div class="name">for fafarrr nainaa</div>  
  
  <div class="message">  
    thankyouu for the fun we had together 😋<br>  
    hope today feels soft, loud, chaotic & happy<br>  
    just like you 💗  
  </div>  
  
  <div class="gallery">  
    <img src="photo1.jpg">  
    <img src="photo2.jpg">  
    <img src="photo3.jpg">  
    <img src="photo4.jpg">  
  </div>  
  
  <div class="footer">  
    made with love 💗  
  </div>  
</div>  
  
</body>  
</html>  
