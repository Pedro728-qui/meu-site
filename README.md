# meu-site
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Seu Nome | Profissional</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background: #0f172a;
    color: #f1f5f9;
    scroll-behavior: smooth;
}

header {
    text-align: center;
    padding: 80px 20px;
    animation: fadeIn 1.5s ease;
}

header img {
    width: 150px;
    border-radius: 50%;
    border: 4px solid #3b82f6;
    margin-bottom: 20px;
}

header h1 {
    font-size: 2.5rem;
}

header p {
    color: #94a3b8;
    margin-top: 10px;
}

nav {
    display: flex;
    justify-content: center;
    gap: 30px;
    padding: 15px;
    background: #1e293b;
}

nav a {
    color: #f1f5f9;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover {
    color: #3b82f6;
}

section {
    padding: 80px 20px;
    max-width: 1000px;
    margin: auto;
}

h2 {
    margin-bottom: 30px;
    color: #3b82f6;
}

.card {
    background: #1e293b;
    padding: 25px;
    border-radius: 10px;
    margin-bottom: 20px;
    transition: 0.4s;
}

.card:hover {
    transform: translateY(-5px);
}

.skills {
    margin-bottom: 20px;
}

.skill-bar {
    background: #334155;
    border-radius: 20px;
    overflow: hidden;
    margin-top: 5px;
}

.skill-progress {
    height: 10px;
    background: #3b82f6;
    width: 0;
    animation: loadSkill 2s forwards;
}

.portfolio {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.portfolio img {
    width: 100%;
    border-radius: 10px;
    transition: 0.4s;
}

.portfolio img:hover {
    transform: scale(1.05);
}

footer {
    text-align: center;
    padding: 30px;
    background: #1e293b;
    margin-top: 40px;
}

@keyframes fadeIn {
    from {opacity: 0; transform: translateY(-20px);}
    to {opacity: 1; transform: translateY(0);}
}

@keyframes loadSkill {
    to {width: var(--skill-level);}
}
</style>
</head>

<body>

<header>
    <img src="https://via.placeholder.com/150" alt="Foto de Perfil">
    <h1>Seu Nome</h1>
    <p>Especialista em Tecnologia | Desenvolvedor | Criador</p>
</header>

<nav>
    <a href="#sobre">Sobre</a>
    <a href="#skills">Habilidades</a>
    <a href="#portfolio">Portfólio</a>
    <a href="#contato">Contato</a>
</nav>

<section id="sobre">
    <h2>Sobre Mim</h2>
    <div class="card">
        <p>Sou um profissional apaixonado por inovação, tecnologia e soluções modernas. 
        Trabalho criando experiências digitais elegantes e eficientes.</p>
    </div>
</section>

<section id="skills">
    <h2>Habilidades</h2>

    <div class="skills">
        <p>HTML & CSS</p>
        <div class="skill-bar">
            <div class="skill-progress" style="--skill-level: 90%;"></div>
        </div>
    </div>

    <div class="skills">
        <p>JavaScript</p>
        <div class="skill-bar">
            <div class="skill-progress" style="--skill-level: 80%;"></div>
        </div>
    </div>

    <div class="skills">
        <p>Design UI/UX</p>
        <div class="skill-bar">
            <div class="skill-progress" style="--skill-level: 75%;"></div>
        </div>
    </div>

</section>

<section id="portfolio">
    <h2>Portfólio</h2>
    <div class="portfolio">
        <img src="https://via.placeholder.com/400x250" alt="Projeto 1">
        <img src="https://via.placeholder.com/400x250" alt="Projeto 2">
        <img src="https://via.placeholder.com/400x250" alt="Projeto 3">
    </div>
</section>

<section id="contato">
    <h2>Contato</h2>
    <div class="card">
        <p>Email: pquintino656@email.com</p>
        <p>LinkedIn: linkedin.com/in/seunome</p>
    </div>
</section>

<footer>
    <p>© 2026 | Seu Nome</p>
</footer>

</body>
</html>
