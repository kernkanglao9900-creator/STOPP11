<!DOCTYPE html>
<html lang="lo">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ຮ້ານຂາຍໄອດີເກມ PRO</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap');

body{
    margin:0;
    font-family:'Orbitron', sans-serif;
    background:#0f0f1a;
    color:white;
}

header{
    text-align:center;
    padding:40px 20px;
    background:linear-gradient(90deg,#ff00cc,#3333ff);
}

header h1{
    font-size:40px;
    letter-spacing:3px;
}

.container{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    padding:30px;
}

.card{
    background:#1c1c2e;
    width:300px;
    margin:20px;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 0 20px rgba(0,255,255,0.4);
    transition:0.4s;
    border:1px solid #00ffff;
}

.card:hover{
    transform:translateY(-10px);
    box-shadow:0 0 30px #00ffff;
}

.card img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.card-content{
    padding:15px;
}

.card h2{
    color:#00ffff;
}

.price{
    color:#ff00cc;
    font-size:18px;
    font-weight:bold;
}

button{
    width:100%;
    padding:10px;
    border:none;
    border-radius:8px;
    background:linear-gradient(90deg,#00ffff,#ff00cc);
    color:white;
    font-weight:bold;
    cursor:pointer;
    margin-top:10px;
}

button:hover{
    opacity:0.8;
}

footer{
    text-align:center;
    padding:20px;
    background:#111;
    margin-top:40px;
    color:#aaa;
}
</style>

</head>
<body>

<header>
    <h1>🎮 GAME ID SHOP PRO</h1>
    <p>ໄອດີແທ້ • ປອດໄພ • ລາຄາຄຸ້ມຄ່າ</p>
</header>

<div class="container">

    <div class="card">
        <img src="https://source.unsplash.com/400x300/?gaming,roblox" alt="Roblox">
        <div class="card-content">
            <h2>ໄອດີ Roblox</h2>
            <p>ເລເວວສູງ • ໄອເທັມຫາຍາກ</p>
            <p class="price">150,000 ກີບ</p>
            <button onclick="alert('ຕິດຕໍ່ທາງ Facebook ເພື່ອຊື້')">ຊື້ເລີຍ</button>
        </div>
    </div>

    <div class="card">
        <img src="https://source.unsplash.com/400x300/?esports,freefire" alt="Free Fire">
        <div class="card-content">
            <h2>ໄອດີ Free Fire</h2>
            <p>ສະກິນຫາຍາກ • ອັນດັບສູງ</p>
            <p
