*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
}

body{
background:#f5f5f5;
color:#333;
}

header{
height:100vh;
background:linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
url("https://images.unsplash.com/photo-1500382017468-9049fed747ef?w=1600");
background-size:cover;
background-position:center;
}

nav{
display:flex;
justify-content:space-between;
padding:20px 60px;
background:#2e7d32;
position:fixed;
width:100%;
z-index:100;
}

nav h2{
color:white;
}

nav ul{
display:flex;
gap:30px;
list-style:none;
}

nav a{
text-decoration:none;
color:white;
font-weight:bold;
}

.banner{
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
height:100%;
color:white;
text-align:center;
padding:20px;
}

.banner h1{
font-size:55px;
}

.banner p{
font-size:22px;
margin:20px;
max-width:700px;
}

button{
padding:15px 40px;
border:none;
border-radius:30px;
background:#ffb300;
font-size:18px;
cursor:pointer;
transition:.4s;
}

button:hover{
transform:scale(1.1);
}

.conteudo{
display:flex;
align-items:center;
justify-content:center;
padding:80px;
gap:50px;
background:white;
}

.reverso{
flex-direction:row-reverse;
background:#eef7ee;
}

.conteudo img{
width:450px;
border-radius:20px;
box-shadow:0 10px 20px rgba(0,0,0,.2);
}

.conteudo h2{
margin-bottom:20px;
color:#2e7d32;
}

.importancia{
padding:80px;
text-align:center;
}

.cards{
display:flex;
gap:30px;
margin-top:40px;
justify-content:center;
flex-wrap:wrap;
}

.card{
background:white;
padding:30px;
width:300px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.15);
transition:.5s;
}

.card:hover{
transform:translateY(-10px);
}

#galeria{
padding:80px;
background:#fff;
text-align:center;
}

.galeria{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
margin-top:40px;
}

.galeria img{
width:100%;
border-radius:20px;
transition:.5s;
}

.galeria img:hover{
transform:scale(1.05);
}

#contato{
padding:80px;
background:#2e7d32;
color:white;
text-align:center;
}

footer{
background:#1b5e20;
color:white;
padding:20px;
text-align:center;
}
