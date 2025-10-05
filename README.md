<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Meu Perfil</title>
    <style>
        :root {
            --primary-color: #2d3748;
            --secondary-color: #4a5568;
            --accent-color: #3182ce;
            --bg-color: #f7fafc;
            --text-color: #2d3748;
            --border-color: #e2e8f0;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            line-height: 1.6;
            padding: 20px;
            max-width: 900px;
            margin: 0 auto;
        }

        .container {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 30px;
            margin-bottom: 20px;
        }

        header {
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 20px;
        }

        h1 {
            color: var(--primary-color);
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        h2 {
            color: var(--secondary-color);
            font-size: 1.8rem;
            margin: 25px 0 15px;
            border-left: 4px solid var(--accent-color);
            padding-left: 10px;
        }

        h3 {
            color: var(--secondary-color);
            font-size: 1.4rem;
            margin: 20px 0 10px;
        }

        p {
            margin-bottom: 15px;
        }

        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid var(--accent-color);
            margin: 0 auto 20px;
            display: block;
        }

        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }

        .badge {
            background-color: var(--accent-color);
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
            font-weight: 500;
        }

        .links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin: 20px 0;
        }

        .link {
            display: inline-flex;
            align-items: center;
            gap: 5px;
            color: var(--accent-color);
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
        }

        .link:hover {
            text-decoration: underline;
            transform: translateY(-2px);
        }

        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin: 25px 0;
        }

        .stat {
            background-color: var(--bg-color);
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            border-left: 3px solid var(--accent-color);
        }

        .stat-value {
            font-size: 1.8rem;
            font-weight: bold;
            color: var(--accent-color);
        }

        .stat-label {
            font-size: 0.9rem;
            color: var(--secondary-color);
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
            gap: 20px;
            margin: 25px 0;
        }

        .project {
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 15px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        .project-title {
            font-size: 1.2rem;
            margin-bottom: 10px;
            color: var(--primary-color);
        }

        .project-description {
            font-size: 0.9rem;
            color: var(--secondary-color);
            margin-bottom: 15px;
        }

        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 5px;
        }

        .tech-tag {
            background-color: var(--bg-color);
            color: var(--secondary-color);
            padding: 3px 8px;
            border-radius: 4px;
            font-size: 0.8rem;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid var(--border-color);
            color: var(--secondary-color);
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .links {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <!-- Substitua pela URL da sua imagem de perfil -->
            <img src="https://via.placeholder.com/150" alt="Foto de Perfil" class="profile-img">
            <h1>Seu Nome</h1>
            <p>Desenvolvedor Full Stack | Apaixonado por tecnologia e inovação</p>
            
            <div class="badges">
                <span class="badge">JavaScript</span>
                <span class="badge">Python</span>
                <span class="badge">React</span>
                <span class="badge">Node.js</span>
                <span class="badge">SQL</span>
                <span class="badge">Git</span>
            </div>
            
            <div class="links">
                <a href="mailto:seuemail@exemplo.com" class="link">✉️ Email</a>
                <a href="https://linkedin.com/in/seu-perfil" class="link">💼 LinkedIn</a>
                <a href="https://twitter.com/seu-perfil" class="link">🐦 Twitter</a>
                <a href="https://portfolio.seusite.com" class="link">🌐 Portfolio</a>
            </div>
        </header>

        <section>
            <h2>Sobre Mim</h2>
            <p>Olá! Sou um desenvolvedor apaixonado por criar soluções inovadoras e eficientes. Com experiência em desenvolvimento web full stack, busco sempre aprender novas tecnologias e enfrentar desafios complexos.</p>
            <p>Atualmente, estou focado em [área de interesse atual] e trabalhando em projetos que envolvem [tecnologias ou conceitos específicos].</p>
            
            <div class="stats">
                <div class="stat">
                    <div class="stat-value">3+</div>
                    <div class="stat-label">Anos de Experiência</div>
                </div>
                <div class="stat">
                    <div class="stat-value">50+</div>
                    <div class="stat-label">Projetos Concluídos</div>
                </div>
                <div class="stat">
                    <div class="stat-value">10+</div>
                    <div class="stat-label">Tecnologias</div>
                </div>
                <div class="stat">
                    <div class="stat-value">5</div>
                    <div class="stat-label">Certificações</div>
                </div>
            </div>
        </section>

        <section>
            <h2>Tecnologias e Ferramentas</h2>
            <h3>Frontend</h3>
            <div class="badges">
                <span class="badge">HTML5</span>
                <span class="badge">CSS3</span>
                <span class="badge">JavaScript</span>
                <span class="badge">React</span>
                <span class="badge">Vue.js</span>
                <span class="badge">Bootstrap</span>
            </div>
            
            <h3>Backend</h3>
            <div class="badges">
                <span class="badge">Node.js</span>
                <span class="badge">Python</span>
                <span class="badge">Express</span>
                <span class="badge">Django</span>
                <span class="badge">MySQL</span>
                <span class="badge">MongoDB</span>
            </div>
            
            <h3>Ferramentas</h3>
            <div class="badges">
                <span class="badge">Git</span>
                <span class="badge">Docker</span>
                <span class="badge">VS Code</span>
                <span class="badge">Figma</span>
                <span class="badge">Postman</span>
            </div>
        </section>

        <section>
            <h2>Projetos em Destaque</h2>
            <div class="projects">
                <div class="project">
                    <h3 class="project-title">Sistema de Gestão</h3>
                    <p class="project-description">Uma aplicação web completa para gerenciamento de tarefas e projetos com dashboard interativo.</p>
                    <div class="project-tech">
                        <span class="tech-tag">React</span>
                        <span class="tech-tag">Node.js</span>
                        <span class="tech-tag">MongoDB</span>
                    </div>
                </div>
                
                <div class="project">
                    <h3 class="project-title">E-commerce</h3>
                    <p class="project-description">Plataforma de e-commerce com carrinho de compras, pagamento integrado e painel administrativo.</p>
                    <div class="project-tech">
                        <span class="tech-tag">Vue.js</span>
                        <span class="tech-tag">Express</span>
                        <span class="tech-tag">MySQL</span>
                    </div>
                </div>
                
                <div class="project">
                    <h3 class="project-title">App de Finanças Pessoais</h3>
                    <p class="project-description">Aplicativo móvel para controle de gastos e orçamento pessoal com gráficos e relatórios.</p>
                    <div class="project-tech">
                        <span class="tech-tag">React Native</span>
                        <span class="tech-tag">Firebase</span>
                        <span class="tech-tag">Chart.js</span>
                    </div>
                </div>
            </div>
        </section>

        <section>
            <h2>Contato</h2>
            <p>Estou sempre aberto a novas oportunidades e colaborações. Sinta-se à vontade para entrar em contato comigo!</p>
            
            <div class="links">
                <a href="mailto:seuemail@exemplo.com" class="link">📧 Enviar Email</a>
                <a href="https://linkedin.com/in/seu-perfil" class="link">👔 Conectar no LinkedIn</a>
                <a href="https://github.com/seu-usuario" class="link">💻 Ver GitHub</a>
            </div>
        </section>

        <footer>
            <p>© 2023 Seu Nome. Todos os direitos reservados.</p>
            <p>📧 seuemail@exemplo.com | 📍 Sua Localização</p>
        </footer>
    </div>
</body>
</html>
