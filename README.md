tecnicouto-site/
│── index.html        (Início)
│── servicos.html
│── sobre.html
│── contactos.html
│── style.css
└── images/
    ├── hero.jpg
    ├── engenharia.jpg
    ├── construcao.jpg
    └── projetos.jpg
<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tecnicouto, Lda | Engenharia e Construção</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <div class="logo">Tecnicouto, Lda</div>
  <nav>
    <a href="index.html">Início</a>
    <a href="servicos.html">Serviços</a>
    <a href="sobre.html">Sobre</a>
    <a href="contactos.html" class="cta">Pedir Orçamento</a>
  </nav>
</header>

<section class="hero" style="background-image:url('images/hero.jpg')">
  <div class="hero-content">
    <h1>Engenharia e Construção feitas para durar</h1>
    <p>Mais de 32 anos de experiência em soluções técnicas nos Açores.</p>
    <a href="contactos.html" class="btn">Pedir Orçamento</a>
  </div>
</section>

<section class="highlights">
  <div>
    <h2>32+</h2>
    <p>Anos de Experiência</p>
  </div>
  <div>
    <h2>Rigor</h2>
    <p>Técnico e Profissional</p>
  </div>
  <div>
    <h2>Confiança</h2>
    <p>Construída projeto a projeto</p>
  </div>
</section>

<footer>
  <p>© 2026 Tecnicouto, Lda</p>
  <p>Email: tecnicouto.geral@gmail.com | Tel: 296 581 021</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Serviços | Tecnicouto</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <div class="logo">Tecnicouto, Lda</div>
  <nav>
    <a href="index.html">Início</a>
    <a href="servicos.html">Serviços</a>
    <a href="sobre.html">Sobre</a>
    <a href="contactos.html" class="cta">Pedir Orçamento</a>
  </nav>
</header>

<section class="page">
  <h1>Os Nossos Serviços</h1>

  <div class="cards">
    <div class="card">
      <h3>Projetos de Engenharia</h3>
      <p>Planeamento técnico rigoroso e soluções eficazes.</p>
    </div>
    <div class="card">
      <h3>Construção Civil</h3>
      <p>Execução sólida, segura e de elevada qualidade.</p>
    </div>
    <div class="card">
      <h3>Fiscalização de Obras</h3>
      <p>Acompanhamento técnico do início ao fim.</p>
    </div>
    <div class="card">
      <h3>Consultoria Técnica</h3>
      <p>Apoio especializado para decisões seguras.</p>
    </div>
  </div>
</section>

<footer>
  <p>© 2026 Tecnicouto, Lda</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sobre | Tecnicouto</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <div class="logo">Tecnicouto, Lda</div>
  <nav>
    <a href="index.html">Início</a>
    <a href="servicos.html">Serviços</a>
    <a href="sobre.html">Sobre</a>
    <a href="contactos.html" class="cta">Pedir Orçamento</a>
  </nav>
</header>

<section class="page">
  <h1>Sobre a Tecnicouto</h1>
  <p>
    A Tecnicouto, Lda atua há mais de 32 anos nas áreas da engenharia,
    construção e atividades técnicas afins, com sede em Vila Franca do Campo,
    Ilha de São Miguel.
  </p>
  <p>
    Trabalhamos com rigor técnico, transparência e compromisso total
    com os nossos clientes.
  </p>
</section>

<footer>
  <p>© 2026 Tecnicouto, Lda</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contactos | Tecnicouto</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <div class="logo">Tecnicouto, Lda</div>
  <nav>
    <a href="index.html">Início</a>
    <a href="servicos.html">Serviços</a>
    <a href="sobre.html">Sobre</a>
    <a href="contactos.html" class="cta">Pedir Orçamento</a>
  </nav>
</header>

<section class="page">
  <h1>Contactos</h1>

  <p><strong>Email:</strong> tecnicouto.geral@gmail.com</p>
  <p><strong>Telefone:</strong> 296 581 021</p>
  <p><strong>Morada:</strong> Parque Industrial de Vila Franca do Campo, Lote 19</p>

  <form class="form">
    <input type="text" placeholder="Nome" required>
    <input type="email" placeholder="Email" required>
    <textarea placeholder="Descreva o seu projeto"></textarea>
    <button type="submit">Enviar Pedido</button>
  </form>
</section>

<footer>
  <p>© 2026 Tecnicouto, Lda</p>
</footer>

</body>
</html>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #0e0e0e;
  color: #f5f5f5;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 30px;
  background: #000;
}

.logo {
  font-size: 20px;
  font-weight: bold;
}

nav a {
  color: #fff;
  margin-left: 15px;
  text-decoration: none;
}

nav .cta {
  color: #c9a44c;
}

.hero {
  height: 80vh;
  background-size: cover;
  background-position: center;
  display: flex;
  align-items: center;
}

.hero-content {
  background: rgba(0,0,0,0.6);
  padding: 30px;
  max-width: 500px;
  margin-left: 30px;
}

.btn {
  display: inline-block;
  margin-top: 15px;
  padding: 12px 20px;
  background: #c9a44c;
  color: #000;
  text-decoration: none;
}

.highlights {
  display: flex;
  justify-content: space-around;
  padding: 40px 20px;
  background: #111;
}

.page {
  padding: 40px 20px;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.card {
  background: #1a1a1a;
  padding: 20px;
}

.form input,
.form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
}

.form button {
  background: #c9a44c;
  border: none;
  padding: 12px;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 20px;
  background: #000;
}

/* MOBILE */
@media (max-width: 768px) {
  .highlights {
    flex-direction: column;
    text-align: center;
  }

  header {
    flex-direction: column;
  }
}
