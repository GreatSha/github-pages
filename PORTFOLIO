<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide">
<title>Shaun's Profile</title>
<style>
    body {
        font-family: "Audiowide", sans-serif;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
        background: #000;
    }

    .h2{
        font-family: "Audiowide", sans-serif;
    }
    .card{
        width: 320px;
        background: #f9f9f9;
        border-radius: 12px;
        box-shadow: 0 8px 16px rgba(0,0,0,0.2);
        text-align: center;
        padding: 20px;
        position: relative;
        cursor: pointer;
        transition: 0.5s;
        overflow: visible;
    }
    .card img {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        object-fit: cover;
        border: 5px solid #f9f9f9;
        position: absolute;
        top: 40px;
        left: 50%;
        transform: translateX(-50%) translateY(0);
        background: orange;
        transition: 0.5s;
        z-index: 0;
    }
    .card.active img {
        top: -60px;
        transform: translateX(-50%) translateY(0);
    }
    .card h2, .card p, .social-icons, .btn {
        opacity: 0;
        transform: translateY(20px);
        transition: 0.5s;
    }
    .card.active h2, .card.active p, .card.active .social-icons, .card.active .btn {
        opacity: 1;
        transform: translateY(0);
    }
    .card h2 {
        margin: 80px 0 10px;
        font-size: 24px;
    }
    .card p {
        font-size: 14px;
        color: #555;
        padding: 0 15px;
    }
    .social-icons {
        display: flex;
        justify-content: center;
        gap: 15px;
        margin: 15px 0;
    }
    .social-icons a {
        text-decoration: none;
        color: #555;
        font-size: 24px;
        transition: 0.3s;
    }
    .social-icons a:hover {
        color: #007BFF;
    }
    .btn {
        display: inline-block;
        padding: 10px 25px;
        background: #ff6961;
        color: white;
        text-decoration: none;
        border-radius: 8px;
        transition: 0.3s;
    }
    .btn:hover {
        background: #ff4c4c;
    }
</style>
</head>
<body>

<div class="card" onclick="toggleInfo()">
    <img src="2.jpg" alt="Profile Image">
    <h2>Shaun Dsouza</h2>
    <p><b>This is my personal profile, where I'm trying to authentically represent myself. However, I'm not sure if this is the right platform for me to be doing so..</p>
    <div class="social-icons">
        <a href="#"><i class="fab fa-instagram">📷</i></a>
        <a href="#"><i class="fab fa-facebook">📘</i></a>
        <a href="#"><i class="fab fa-github">🔗</i></a>
    </div>
    <a href="#" class="btn">More</a>
</div>

<script>
    function toggleInfo() {
        const card = document.querySelector('.card');
        card.classList.toggle('active');
    }
</script>

</body>
</html>
