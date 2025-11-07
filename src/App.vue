<template>
  <div id="app">
    <header class="navbar">
      <div class="container">
        <a href="#" class="logo">
          <img
            src="@/assets/foto-advogado.png"
            alt="Logo Advocacia"
            class="logo-img"
          />
          <span>Mateus Advocacia</span>
        </a>
        <nav>
          <ul>
            <li><a href="#hero">Início</a></li>
            <li><a href="#about">O Escritório</a></li>
            <li><a href="#areas">Áreas</a></li>
            <li><a href="#contact">Contato</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <main>
      <section id="hero" class="hero-section">
        <div class="hero-content">
          <img
            src="@/assets/foto-advogado.png"
            alt="Advogado em escritório"
            class="hero-image"
          />
          <div class="hero-text-box">
            <h1>Expertise Jurídica para Seus Desafios</h1>
            <p>
              Representamos seus interesses com ética, dedicação e resultados.
            </p>
            <a href="#contact" class="cta-button">Fale Conosco</a>
          </div>
        </div>
      </section>

      <section id="about" class="content-section">
        <div class="container">
          <h2>Sobre o Escritório</h2>
          <div class="about-grid">
            <img
              src="@/assets/frente-escritorio.png"
              alt="Prédio do Escritório"
              class="about-image"
            />
            <div class="about-text">
              <p>
                Fundado em 2010, o escritório Advocacia Mateus Fernandes é
                reconhecido pela excelência e pelo compromisso inabalável com a
                justiça e a defesa dos direitos de nossos clientes. Nossa equipe
                é composta por profissionais altamente qualificados e
                experientes, dedicados a oferecer soluções jurídicas
                estratégicas e personalizadas.
              </p>
              <p>
                Acreditamos na importância de um atendimento humanizado e
                transparente, construindo relações de confiança e proximidade.
                Nosso objetivo é superar as expectativas, garantindo a
                tranquilidade e a segurança jurídica que você e sua empresa
                merecem.
              </p>
            </div>
          </div>
        </div>
      </section>

      <section id="areas" class="content-section bg-light">
        <div class="container">
          <h2>Áreas de Atuação</h2>
          <p class="section-description">
            Nossa expertise abrange diversas áreas do direito, garantindo um
            suporte completo e especializado.
          </p>
          <div class="areas-grid">
            <div class="area-card">
              <img
                src="@/assets/icone-direito-civil.png"
                alt="Direito Civil"
                class="area-icon"
              />
              <h3>Direito Civil</h3>
              <p>
                Contratos, responsabilidade civil, direitos do consumidor,
                família e sucessões.
              </p>
            </div>
            <div class="area-card">
              <img
                src="@/assets/icone-direito-empresarial.png"
                alt="Direito Empresarial"
                class="area-icon"
              />
              <h3>Direito Empresarial</h3>
              <p>
                Constituição de empresas, contratos comerciais, fusões e
                aquisições.
              </p>
            </div>
            <div class="area-card">
              <img
                src="@/assets/icone-direito-trabalhista.png"
                alt="Direito Trabalhista"
                class="area-icon"
              />
              <h3>Direito Trabalhista</h3>
              <p>
                Assessoria para empregados e empregadores, contencioso e
                consultivo.
              </p>
            </div>
            <div class="area-card">
              <img
                src="@/assets/icone-direito-penal.png"
                alt="Direito Penal"
                class="area-icon"
              />
              <h3>Direito Penal</h3>
              <p>
                Defesa em processos criminais, inquéritos policiais, compliance.
              </p>
            </div>
          </div>
        </div>
      </section>

      <section id="approach" class="content-section">
        <div class="container">
          <h2>Nossa Abordagem</h2>
          <div class="approach-grid">
            <div class="approach-item">
              <h3>
                <i class="fas fa-handshake"></i> Atendimento Personalizado
              </h3>
              <p>
                Cada caso é único e recebe atenção dedicada, com estratégias sob
                medida.
              </p>
            </div>
            <div class="approach-item">
              <h3><i class="fas fa-gavel"></i> Ética e Transparência</h3>
              <p>
                Compromisso com os mais altos padrões de conduta e comunicação
                clara.
              </p>
            </div>
            <div class="approach-item">
              <h3><i class="fas fa-chart-line"></i> Foco em Resultados</h3>
              <p>
                Buscamos as soluções mais eficientes para os objetivos de nossos
                clientes.
              </p>
            </div>
          </div>
        </div>
      </section>

      <section id="contact" class="content-section bg-light">
        <div class="container">
          <h2>Fale Conosco</h2>
          <p class="section-description">
            Estamos à disposição para entender suas necessidades e oferecer a
            melhor assistência jurídica.
          </p>
          <div class="contact-grid">
            <div class="contact-info">
              <h3>Informações de Contato</h3>
              <p>
                <i class="fas fa-map-marker-alt"></i> Rua Exemplo, 1234 -
                Bairro, Cidade - UF
              </p>
              <p><i class="fas fa-phone"></i> (XX) XXXX-XXXX</p>
              <p><i class="fas fa-envelope"></i>contato@mateusadvocacia.com</p>
              <div class="map-placeholder">
                <iframe
                  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3679.914902120005!2d-43.1764667850389!3d-22.90684678501188!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x997f58b0244747%3A0x6b6d2a4a7b51b7c8!2sCristo%20Redentor!5e0!3m2!1spt-BR!2sbr!4v1678912345678!5m2!1spt-BR!2sbr"
                  width="100%"
                  height="250"
                  style="border: 0"
                  allowfullscreen="true"
                  loading="lazy"
                >
                </iframe>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer class="footer">
      <div class="container">
        <div class="footer-links">
          <a href="#">Política de Privacidade</a>
          <a href="#">Termos de Uso</a>
        </div>
        <div class="social-links">
          <a href="#"><i class="fab fa-linkedin"></i></a>
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-facebook-f"></i></a>
        </div>
        <p>
          &copy; {{ new Date().getFullYear() }} Advocacia Mateus Fernandes.
          Todos os direitos reservados.
        </p>
      </div>
      <BotaoWhatsapp />
    </footer>
  </div>
</template>

<script lang="js">
import BotaoWhatsapp from './components/BotaoWhatsapp.vue';

export default {
  components: {
    BotaoWhatsapp
  }
};
</script>

<style>
/* --- Import de Font Awesome para Ícones --- */
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css");

/* --- Reset Básico & Estilos Globais --- */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

:root {
  --primary-color: #003366; /* Azul escuro corporativo */
  --secondary-color: #c09f52; /* Ouro/Bege para detalhes */
  --accent-color: #f7f7f7; /* Cinza claro */
  --text-color: #333;
  --light-text: #fff;
}

html {
  scroll-behavior: smooth;
}

* {
  margin: 0;
  padding: 0;
}

body {
  font-family: "Montserrat", sans-serif; /* Fonte moderna e corporativa */
  line-height: 1.6;
  color: var(--text-color);
  background-color: var(--light-text);
}

h1,
h2,
h3 {
  line-height: 1.2;
  margin-bottom: 1rem;
  font-family: "Merriweather", serif; /* Fonte serifada para títulos */
  color: var(--primary-color);
}

p {
  overflow-wrap: break-word;
}

a {
  text-decoration: none;
  color: var(--primary-color);
}

.container {
  max-width: 100%;
  margin: 0 auto;
  padding: 0;
}

.section-description {
  max-width: 100%;
  margin: 0 auto 2rem;
  font-size: 1.1rem;
  color: #555;
}

/* --- Componentes Reutilizáveis --- */
.content-section {
  padding: 5rem 0;
  text-align: center;
}

.bg-light {
  background-color: var(--accent-color);
}

.cta-button {
  display: inline-block;
  background-color: var(--secondary-color);
  color: var(--light-text);
  padding: 0.9rem 2rem;
  border-radius: 5px;
  font-weight: bold;
  transition: background-color 0.3s ease;
  border: none;
  cursor: pointer;
  font-size: 1rem;
}

.cta-button:hover {
  background-color: #a38547; /* Tom mais escuro do ouro */
}

/* --- 1. Header & Navegação --- */
.navbar {
  background-color: var(--primary-color);
  color: var(--light-text);
  padding: 1rem 0;
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 1000;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
}

.navbar .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.navbar .logo {
  display: flex;
  align-items: center;
  font-size: 1.4rem;
  font-weight: bold;
  color: var(--light-text);
}

.navbar .logo-img {
  width: 3rem;
  max-width: 100%;
  margin-right: 10px;
  border-radius: 50%;
}

.navbar nav ul {
  list-style: none;
  display: flex;
}

.navbar nav li {
  margin-left: 2rem;
}

.navbar nav a {
  color: var(--light-text);
  font-weight: 500;
  padding-bottom: 5px;
  transition: color 0.3s ease, border-bottom 0.3s ease;
}

.navbar nav a:hover {
  color: var(--secondary-color);
  border-bottom: 2px solid var(--secondary-color);
}

/* --- 2. Hero Section --- */
.hero-section {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 80px; /* Espaço para o fixed navbar */
  background-color: var(--accent-color);
}

.hero-content {
  display: flex;
  align-items: center;
  max-width: 100%;
  background-color: var(--light-text);
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  overflow: hidden;
  text-align: left;
}

.hero-image {
  width: 50%;
  height: auto;
  object-fit: cover;
  display: block;
}

.hero-text-box {
  width: 50%;
  padding: 3rem;
}

.hero-text-box h1 {
  font-size: 2.8rem;
  margin-bottom: 1.5rem;
  color: var(--primary-color);
}

.hero-text-box p {
  font-size: 1.2rem;
  margin-bottom: 2.5rem;
  color: #555;
}

/* --- 3. About Section --- */
.about-grid {
  display: flex;
  align-items: center;
  gap: 3rem;
  margin-top: 3rem;
  text-align: left;
}

.about-image {
  flex: 1;
  width: 100%;
  max-width: 500px;
  border-radius: 8px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.about-text {
  flex: 1;
}

.about-text p {
  margin-bottom: 1rem;
  font-size: 1.1rem;
}

/* --- 4. Areas of Practice Section --- */
#areas h2 {
  margin-bottom: 1.5rem;
}

.areas-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  margin-top: 3rem;
  width: 100%;
  max-width: 100%;
}

.area-card {
  background: var(--light-text);
  padding: 2.5rem;

  border-radius: 8px;
  box-shadow: 0 5px 20px rgba(0, 0, 0, 0.08);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  text-align: center;
  width: 100%;
}

.area-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
}

.area-card .area-icon {
  width: 120px;
  max-width: 100%;
  height: 120px;
  object-fit: cover;
  border-radius: 5px;
  margin-bottom: 1.5rem;
}

.area-card h3 {
  color: var(--primary-color);
  font-size: 1.5rem;
  margin-bottom: 1rem;
}

.area-card p {
  color: #666;
}

/* --- 5. Our Approach Section --- */
.approach-grid {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  gap: 2rem;
  margin-top: 3rem;
}

.approach-item {
  flex-basis: calc(33% - 2rem);
  background: var(--accent-color);
  padding: 2rem;
  border-radius: 8px;
  text-align: left;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.05);
}

.approach-item h3 {
  color: var(--primary-color);
  font-size: 1.3rem;
  margin-bottom: 1rem;
}

.approach-item h3 i {
  color: var(--secondary-color);
  margin-right: 10px;
  font-size: 1.5rem;
}

/* --- 6. Contact Section --- */
.contact-grid {
  display: flex;
  gap: 3rem;
  margin-top: 3rem;
  text-align: left;
}

.contact-form {
  flex: 2;
  background: var(--light-text);
  padding: 2.5rem;
  border-radius: 8px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
}

.contact-info {
  flex: 1;
  background: var(--primary-color);
  color: var(--light-text);
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
}

.contact-info h3 {
  color: var(--secondary-color);
  margin-bottom: 1.5rem;
  font-size: 1.6rem;
}

.contact-info p {
  margin-bottom: 1rem;

  align-items: center;
  font-size: 1.1rem;
}

.contact-info p i {
  color: var(--secondary-color);
  font-size: 1.2rem;
}

.form-group {
  margin-bottom: 1.5rem;
}

.form-group label {
  display: block;
  margin-bottom: 0.5rem;
  font-weight: 600;
  color: var(--primary-color);
}

.form-group input,
.form-group textarea {
  width: 100%;
  max-width: 100%;
  padding: 0.9rem;
  border: 1px solid #ddd;
  border-radius: 5px;
  font-family: inherit;
  font-size: 1rem;
  transition: border-color 0.3s ease;
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: var(--secondary-color);
}

.form-group textarea {
  resize: vertical;
}

.contact-form .cta-button {
  width: 100%;
  margin-top: 1rem;
}

.map-placeholder {
  margin-top: 2rem;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
}

/* --- 7. Footer --- */
.footer {
  background-color: var(--primary-color);
  color: var(--light-text);
  text-align: center;
  padding: 2.5rem 0;
  font-size: 0.95rem;
}

.footer .container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.footer-links a,
.social-links a {
  color: var(--light-text);
  margin: 0 0.8rem;
  font-size: 1.1rem;
  transition: color 0.3s ease;
}

.footer-links {
  margin-bottom: 1rem;
}

.social-links {
  margin-bottom: 1.5rem;
}

.footer-links a:hover,
.social-links a:hover {
  color: var(--secondary-color);
}

/* --- Responsividade --- */
@media (max-width: 992px) {
  .hero-content {
    flex-direction: column;
    width: 90%;
  }

  .hero-image,
  .hero-text-box {
    width: 100%;
  }

  .hero-image {
    max-height: 350px;
  }

  .hero-text-box {
    padding: 2rem;
    text-align: center;
  }

  .hero-text-box h1 {
    font-size: 2.2rem;
  }

  .about-grid,
  .contact-grid {
    flex-direction: column;
  }

  .approach-item {
    flex-basis: calc(50% - 2rem);
  }

  .contact-info {
    margin-top: 2rem;
  }
}

@media (max-width: 768px) {
  .navbar .container {
    flex-direction: column;
  }
  .navbar .logo {
    margin-bottom: 1rem;
  }
  .navbar nav ul {
    flex-wrap: wrap;
    justify-content: center;
  }
  .navbar nav li {
    margin: 0 0.5rem 0.5rem;
  }

  .hero-text-box h1 {
    font-size: 1.8rem;
  }

  .approach-item {
    flex-basis: 100%;
  }
}

@media (max-width: 576px) {
  .hero-image {
    display: none; /* Em telas muito pequenas, a imagem do hero pode ser removida */
  }

  .hero-content {
    background-color: transparent;
    box-shadow: none;
  }

  .hero-section {
    background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
      url("@/assets/frente-escritorio.png"); /* Imagem de fundo responsiva */
    background-size: cover;
    background-position: center;
    color: var(--light-text);
  }

  .hero-text-box h1,
  .hero-text-box p {
    color: var(--light-text);
  }

  .content-section {
    padding: 3rem 0;
  }

  .about-grid,
  .areas-grid,
  .approach-grid,
  .contact-grid {
    gap: 1.5rem;
  }
}
</style>
