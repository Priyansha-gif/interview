<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Image Slider</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    background:#f2f4f8;
}

header{
    background:#0d6efd;
    color:white;
    padding:14px 22px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:16px;
    font-size:14px;
}

.slider-wrapper{
    margin:60px auto;
    width:100%;
    position:relative;
}

.slider{
    display:flex;
    justify-content:center;
    align-items:center;
    gap:18px;
}

.slide{
    width:190px;
    height:130px;
    opacity:0.45;
    transition:0.4s;
    cursor:pointer;
}

.slide img{
    width:100%;
    height:100%;
    object-fit:cover;
    border-radius:12px;
    box-shadow:0 4px 10px rgba(0,0,0,0.15);
}

.slide.active{
    width:340px;
    height:230px;
    opacity:1;
    transform:scale(1.05);
}

.arrow{
    position:absolute;
    top:50%;
    transform:translateY(-50%);
    background:rgba(0,0,0,0.65);
    color:white;
    border:none;
    font-size:22px;
    padding:10px 15px;
    border-radius:50%;
    cursor:pointer;
}

.prev{ left:25px; }
.next{ right:25px; }

.popup{
    display:none;
    position:fixed;
    inset:0;
    background:rgba(0,0,0,0.9);
    justify-content:center;
    align-items:center;
    z-index:999;
}

.popup img{
    max-width:90%;
    max-height:80%;
    border-radius:12px;
}

.close{
    position:absolute;
    top:20px;
    right:28px;
    font-size:32px;
    color:white;
    cursor:pointer;
}

@media(max-width:768px){
    .slide{
        width:130px;
        height:95px;
    }
    .slide.active{
        width:240px;
        height:165px;
    }
}
</style>
</head>

<body>

<header>
    <h3>My Website</h3>
    <nav>
        <a href="#">Home</a>
        <a href="#">Gallery</a>
        <a href="#">Contact</a>
    </nav>
</header>

<div class="slider-wrapper">
    <button class="arrow prev" onclick="prev()">❮</button>

    <div class="slider">
        <div class="slide">
            <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee">
        </div>
        <div class="slide">
            <img src="https://images.unsplash.com/photo-1503264116251-35a269479413">
        </div>
        <div class="slide">
            <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085">
        </div>
    </div>

    <button class="arrow next" onclick="next()">❯</button>
</div>

<div class="popup" id="popup">
    <span class="close" onclick="closePop()">×</span>
    <img id="popImg">
</div>

<script>
let slides = document.querySelectorAll(".slide");
let index = 1;

function update(){
    slides.forEach(s => s.classList.remove("active"));
    slides[index].classList.add("active");
}

function next(){
    index = (index + 1) % slides.length;
    update();
}

function prev(){
    index = (index - 1 + slides.length) % slides.length;
    update();
}

slides.forEach(s => {
    s.onclick = () => {
        document.getElementById("popup").style.display = "flex";
        document.getElementById("popImg").src = s.querySelector("img").src;
    };
});

function closePop(){
    document.getElementById("popup").style.display = "none";
}

update();
</script>

</body>
</html>
