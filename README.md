
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yansi Hernández | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#050816;
    color:white;
    display:flex;
    min-height:100vh;
}

/* SIDEBAR */

.sidebar{
    width:320px;
    background:#0b1023;
    padding:30px;
    border-right:1px solid rgba(255,255,255,0.08);
}

.profile{
    text-align:center;
}

.profile img{
    width:170px;
    height:170px;
    border-radius:50%;
    border:4px solid #8b5cf6;
    box-shadow:0 0 30px #8b5cf6;
    object-fit:cover;
}

.profile h1{
    margin-top:20px;
    font-size:30px;
}

.profile p{
    color:#b8b8b8;
    margin-top:10px;
    line-height:1.6;
}

.btn{
    display:block;
    margin-top:20px;
    background:linear-gradient(90deg,#8b5cf6,#ec4899);
    padding:12px;
    border-radius:12px;
    color:white;
    text-decoration:none;
    font-weight:600;
}

.info{
    margin-top:35px;
}

.info p{
    margin:15px 0;
    color:#d6d6d6;
}

/* MAIN */

.main{
    flex:1;
    padding:40px;
}

/* HEADER */

.top{
    background:#0b1023;
    border:1px solid rgba(255,255,255,0.08);
    border-radius:20px;
    padding:35px;
}

.top h2{
    font-size:45px;
}

.top span{
    color:#c084fc;
}

.top p{
    margin-top:15px;
    color:#cfcfcf;
    line-height:1.8;
    max-width:700px;
}

/* TAGS */

.tags{
    margin-top:25px;
    display:flex;
    gap:15px;
    flex-wrap:wrap;
}

.tag{
    padding:10px 18px;
    background:#111827;
    border:1px solid #7c3aed;
    border-radius:10px;
    color:#c084fc;
}

/* STATS */

.stats{
    margin-top:30px;
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.card{
    background:#0b1023;
    border:1px solid rgba(255,255,255,0.08);
    padding:25px;
    border-radius:20px;
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
    box-shadow:0 0 20px rgba(139,92,246,0.4);
}

.card h3{
    color:#c084fc;
    margin-bottom:15px;
}

.number{
    font-size:40px;
    font-weight:bold;
}

/* SKILLS */

.skills{
    margin-top:40px;
}

.skills-box{
    display:flex;
    flex-wrap:wrap;
    gap:15px;
    margin-top:20px;
}

.skill{
    background:#111827;
    border:1px solid #8b5cf6;
    padding:15px 20px;
    border-radius:15px;
    font-weight:600;
}

/* PROJECTS */

.projects{
    margin-top:40px;
}

.project-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:20px;
    margin-top:20px;
}

.project{
    background:#0b1023;
    border-radius:20px;
    padding:25px;
    border:1px solid rgba(255,255,255,0.08);
    transition:0.3s;
}

.project:hover{
    transform:scale(1.03);
    box-shadow:0 0 25px rgba(236,72,153,0.3);
}

.project h4{
    color:#ec4899;
    margin-bottom:15px;
}

.project p{
    color:#d6d6d6;
    line-height:1.7;
}

/* FOOTER */

footer{
    margin-top:50px;
    text-align:center;
    color:#a1a1aa;
}

@media(max-width:900px){

body{
    flex-direction:column;
}

.sidebar{
    width:100%;
}

.top h2{
    font-size:35px;
}

}

</style>
</head>

<body>

<!-- SIDEBAR -->

<div class="sidebar">

<div class="profile">

<img src="https://i.imgur.com/2DhmtJ4.png">

<h1>Yansi Hernández 💜</h1>

<p>
Estudiante de Desarrollo de Software <br>
2do año | Apasionada por la tecnología
</p>

<a href="#" class="btn">Editar Perfil</a>

</div>

<div class="info">

<p>📍 San Salvador, El Salvador</p>
<p>📧 yansi.dev@gmail.com</p>
<p>📱 +503 0000-0000</p>
<p>💻 github.com/19792129-cell</p>

</div>

</div>

<!-- MAIN -->

<div class="main">

<div class="top">

<h2>¡Hola! Soy <span>Yansi 👋</span></h2>

<p>
Me gusta crear aplicaciones modernas, trabajar en proyectos de software,
diseñar páginas web y aprender nuevas tecnologías cada día.
</p>

<div class="tags">

<div class="tag">💻 Programadora</div>
<div class="tag">🚀 Aprendiendo</div>
<div class="tag">🌸 Creativa</div>
<div class="tag">⚡ Full Stack</div>

</div>

</div>

<!-- STATS -->

<div class="stats">

<div class="card">
<h3>Repositorios</h3>
<div class="number">12</div>
</div>

<div class="card">
<h3>Commits</h3>
<div class="number">245</div>
</div>

<div class="card">
<h3>Contribuciones</h3>
<div class="number">156</div>
</div>

<div class="card">
<h3>Seguidores</h3>
<div class="number">23</div>
</div>

</div>

<!-- SKILLS -->

<div class="skills">

<h2>Tecnologías y Habilidades</h2>

<div class="skills-box">

<div class="skill">HTML</div>
<div class="skill">CSS</div>
<div class="skill">JavaScript</div>
<div class="skill">Java</div>
<div class="skill">MySQL</div>
<div class="skill">PostgreSQL</div>
<div class="skill">GitHub</div>
<div class="skill">Visual Studio Code</div>

</div>

</div>

<!-- PROJECTS -->

<div class="projects">

<h2>Proyectos Destacados</h2>

<div class="project-grid">

<div class="project">
<h4>🛒 Sistema de Ventas</h4>

<p>
Aplicación desarrollada en Java y PostgreSQL para gestión de clientes y productos.
</p>

</div>

<div class="project">
<h4>📚 Sistema Escolar</h4>

<p>
Proyecto para registrar estudiantes, materias y notas con base de datos.
</p>

</div>

<div class="project">
<h4>🌐 Portafolio Web</h4>

<p>
Página personal moderna inspirada en GitHub usando HTML y CSS.
</p>

</div>

</div>

</div>

<footer>

✨ “Cada línea de código me acerca a mi futuro.” ✨

</footer>

</div>

</body>
</html>
