<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imersão Prosperidade Sem Limites - 28 e 29 de Janeiro 2026</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #000;
            color: #fff;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* HERO SECTION */
        .hero {
            background: linear-gradient(135deg, #000 0%, #1a1a1a 100%);
            padding: 80px 20px;
            text-align: center;
            border-bottom: 3px solid #ff0000;
        }

        .hero h1 {
            font-size: 3.5rem;
            font-weight: 900;
            text-transform: uppercase;
            letter-spacing: 2px;
            margin-bottom: 20px;
            color: #fff;
        }

        .hero .subtitle {
            font-size: 1.8rem;
            color: #ff0000;
            font-weight: 700;
            margin-bottom: 30px;
            line-height: 1.3;
        }

        .hero .date {
            font-size: 1.3rem;
            color: #ccc;
            margin-bottom: 30px;
            font-weight: 600;
        }

        .hero .description {
            font-size: 1.2rem;
            max-width: 900px;
            margin: 0 auto 40px;
            color: #ddd;
            line-height: 1.8;
        }

        .hero .warning {
            font-size: 1.1rem;
            color: #ff0000;
            font-weight: 600;
            margin-bottom: 40px;
        }

        .cta-button {
            display: inline-block;
            background: #ff0000;
            color: #fff;
            padding: 20px 50px;
            font-size: 1.3rem;
            font-weight: 900;
            text-transform: uppercase;
            text-decoration: none;
            border-radius: 5px;
            transition: all 0.3s;
            border: 2px solid #ff0000;
        }

        .cta-button:hover {
            background: #fff;
            color: #ff0000;
            transform: scale(1.05);
        }

        /* SECTIONS */
        .section {
            padding: 80px 20px;
            border-bottom: 1px solid #333;
        }

        .section-dark {
            background: #0a0a0a;
        }

        .section-gray {
            background: #1a1a1a;
        }

        h2 {
            font-size: 2.5rem;
            font-weight: 900;
            text-transform: uppercase;
            margin-bottom: 40px;
            text-align: center;
            color: #ff0000;
            letter-spacing: 1px;
        }

        h3 {
            font-size: 1.8rem;
            font-weight: 700;
            margin-bottom: 20px;
            color: #fff;
        }

        p {
            font-size: 1.1rem;
            margin-bottom: 20px;
            color: #ddd;
        }

        /* WHY SECTION */
        .why-box {
            background: #1a1a1a;
            padding: 40px;
            border-left: 5px solid #ff0000;
            margin-bottom: 30px;
        }

        /* FOR WHO SECTION */
        .for-who-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            margin-top: 40px;
        }

        .for-who-box {
            background: #1a1a1a;
            padding: 40px;
            border-radius: 5px;
        }

        .for-who-box.yes {
            border-left: 5px solid #00ff00;
        }

        .for-who-box.no {
            border-left: 5px solid #ff0000;
        }

        .for-who-box h3 {
            color: #ff0000;
            margin-bottom: 30px;
        }

        .for-who-box.yes h3 {
            color: #00ff00;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            padding: 15px 0;
            border-bottom: 1px solid #333;
            font-size: 1.1rem;
            color: #ddd;
        }

        ul li:before {
            content: "✓ ";
            color: #ff0000;
            font-weight: bold;
            margin-right: 10px;
        }

        .for-who-box.no ul li:before {
            content: "✗ ";
        }

        /* MECHANISM SECTION */
        .mechanism-box {
            background: #1a1a1a;
            padding: 40px;
            margin-bottom: 30px;
            border-left: 5px solid #ff0000;
        }

        .mechanism-steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .step {
            background: #0a0a0a;
            padding: 30px;
            border-radius: 5px;
            text-align: center;
            border: 2px solid #333;
            transition: all 0.3s;
        }

        .step:hover {
            border-color: #ff0000;
            transform: translateY(-5px);
        }

        .step-number {
            font-size: 3rem;
            color: #ff0000;
            font-weight: 900;
            margin-bottom: 20px;
        }

        /* PROGRAM SECTION */
        .day-program {
            background: #1a1a1a;
            padding: 40px;
            margin-bottom: 30px;
            border-radius: 5px;
        }

        .day-program h3 {
            color: #ff0000;
            font-size: 2rem;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .day-program .subtitle-day {
            font-size: 1.3rem;
            color: #ccc;
            margin-bottom: 30px;
            font-style: italic;
        }

        /* TRAINERS SECTION */
        .trainers-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            margin-top: 40px;
        }

        .trainer-card {
            background: #1a1a1a;
            padding: 40px;
            border-radius: 5px;
            border-left: 5px solid #ff0000;
        }

        .trainer-name {
            font-size: 2rem;
            color: #ff0000;
            font-weight: 900;
            margin-bottom: 15px;
        }

        .trainer-title {
            font-size: 1.2rem;
            color: #ccc;
            margin-bottom: 25px;
            font-style: italic;
        }

        .trainer-description {
            font-size: 1.05rem;
            line-height: 1.8;
            color: #ddd;
            margin-bottom: 15px;
        }

        .trainer-highlights {
            margin-top: 25px;
            padding-top: 25px;
            border-top: 1px solid #333;
        }

        /* BENEFITS SECTION */
        .benefits-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .benefit-item {
            background: #1a1a1a;
            padding: 30px;
            border-radius: 5px;
            border-left: 5px solid #ff0000;
        }

        .benefit-item h4 {
            color: #ff0000;
            font-size: 1.3rem;
            margin-bottom: 15px;
        }

        /* TICKETS SECTION */
        .tickets-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 40px;
            margin-top: 40px;
        }

        .ticket-card {
            background: #1a1a1a;
            padding: 40px;
            border-radius: 10px;
            border: 3px solid #333;
            text-align: center;
            transition: all 0.3s;
        }

        .ticket-card:hover {
            transform: translateY(-10px);
            border-color: #ff0000;
        }

        .ticket-card.featured {
            border-color: #ff0000;
            background: linear-gradient(135deg, #1a1a1a 0%, #2a0a0a 100%);
        }

        .ticket-name {
            font-size: 2rem;
            font-weight: 900;
            color: #ff0000;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .ticket-price {
            font-size: 3rem;
            font-weight: 900;
            color: #fff;
            margin-bottom: 30px;
        }

        .ticket-features {
            text-align: left;
            margin-bottom: 30px;
        }

        .ticket-features li {
            padding: 12px 0;
            font-size: 1.05rem;
        }

        /* COMPARISON TABLE */
        .comparison-table {
            background: #1a1a1a;
            padding: 40px;
            margin-top: 40px;
            border-radius: 5px;
            overflow-x: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            padding: 20px;
            text-align: left;
            border-bottom: 1px solid #333;
        }

        th {
            background: #ff0000;
            color: #fff;
            font-weight: 900;
            text-transform: uppercase;
        }

        td {
            color: #ddd;
        }

        .check {
            color: #00ff00;
            font-size: 1.5rem;
            text-align: center;
        }

        .cross {
            color: #ff0000;
            font-size: 1.5rem;
            text-align: center;
        }

        /* TESTIMONIALS */
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .testimonial-card {
            background: #1a1a1a;
            padding: 35px;
            border-radius: 5px;
            border-left: 5px solid #ff0000;
        }

        .testimonial-text {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #ddd;
            margin-bottom: 20px;
            font-style: italic;
        }

        .testimonial-author {
            font-weight: 700;
            color: #ff0000;
            font-size: 1.1rem;
        }

        .testimonial-info {
            color: #999;
            font-size: 0.95rem;
        }

        /* FINAL PRESSURE */
        .pressure-section {
            background: linear-gradient(135deg, #1a0000 0%, #000 100%);
            padding: 80px 20px;
            text-align: center;
        }

        .pressure-section h2 {
            font-size: 3rem;
            margin-bottom: 40px;
        }

        .pressure-text {
            font-size: 1.5rem;
            max-width: 800px;
            margin: 0 auto 30px;
            line-height: 1.8;
        }

        .pressure-highlight {
            font-size: 1.8rem;
            color: #ff0000;
            font-weight: 900;
            margin: 40px 0;
        }

        /* RESPONSIVE */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }

            .hero .subtitle {
                font-size: 1.3rem;
            }

            .for-who-grid,
            .trainers-grid {
                grid-template-columns: 1fr;
            }

            h2 {
                font-size: 2rem;
            }

            .tickets-grid {
                grid-template-columns: 1fr;
            }
        }

        /* FAQ SECTION */
        .faq-container {
            max-width: 900px;
            margin: 40px auto 0;
        }

        .faq-item {
            background: #1a1a1a;
            padding: 25px;
            margin-bottom: 20px;
            border-radius: 5px;
            border-left: 5px solid #ff0000;
        }

        .faq-question {
            font-size: 1.2rem;
            font-weight: 700;
            color: #ff0000;
            margin-bottom: 15px;
        }

        .faq-answer {
            font-size: 1.05rem;
            color: #ddd;
            line-height: 1.7;
        }

        /* URGENCY BANNER */
        .urgency-banner {
            background: #ff0000;
            color: #fff;
            text-align: center;
            padding: 15px;
            font-size: 1.1rem;
            font-weight: 700;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
    </style>
</head>
<body>

    <!-- URGENCY BANNER -->
    <div class="urgency-banner">
        ⚠️ VAGAS LIMITADAS - LOTE 1 ENCERRA EM BREVE ⚠️
    </div>

    <!-- HERO SECTION -->
    <section class="hero">
        <div class="container">
            <h1>Imersão Prosperidade Sem Limites</h1>
            <p class="subtitle">O evento mais desconfortável (e lucrativo) da sua vida financeira</p>
            <p class="date">São Paulo – 28 e 29 de janeiro de 2026</p>
            <p class="description">
                Dois dias presenciais para desmontar sua identidade financeira atual, eliminar sabotagens invisíveis 
                e sair com um plano brutal de execução para os próximos 90 dias.
            </p>
            <p class="warning">
                Se você continuar operando como vem operando, seus próximos 12 meses serão apenas uma repetição cara do último ano.
            </p>
            <a href="#ingressos" class="cta-button">Quero garantir meu ingresso agora</a>
        </div>
    </section>

    <!-- WHY THIS EXISTS -->
    <section class="section section-dark">
        <div class="container">
            <h2>Por que essa imersão existe</h2>
            <div class="why-box">
                <p style="font-size: 1.3rem; font-weight: 700; margin-bottom: 30px;">
                    Você não está quebrado de conteúdo.<br>
                    Você está quebrado de identidade financeira.
                </p>
                <p>
                    Você já ouviu "ganhe mais", "gaste menos", "invista melhor".<br>
                    O problema é que, se a sua mente ainda está programada para escassez, culpa, medo e auto-sabotagem, 
                    qualquer estratégia vira remendo.
                </p>
                <p>
                    Esse evento não é sobre aprender "mais uma técnica".<br>
                    É sobre reprogramar a forma como você se relaciona com o dinheiro, com o trabalho e com o próprio valor.
                </p>
            </div>
        </div>
    </section>

    <!-- FOR WHO / NOT FOR WHO -->
    <section class="section section-gray">
        <div class="container">
            <h2>Para quem é / Para quem não é</h2>
            <div class="for-who-grid">
                <div class="for-who-box yes">
                    <h3>Esta imersão é para quem:</h3>
                    <ul>
                        <li>Trabalha muito e colhe pouco — e já sabe que o problema não é o esforço.</li>
                        <li>Consegue pagar as contas, mas vive em estado de sobrevivência, nunca de construção.</li>
                        <li>Já tentou cursos, mentorias, planilhas, mas continua batendo no mesmo teto financeiro.</li>
                        <li>Vê o dinheiro entrar e sair sem nunca sentir segurança real.</li>
                        <li>Sente culpa ou vergonha por ganhar, cobrar ou prosperar.</li>
                        <li>Quer parar de viver de picos de empolgação e entrar em ritmo de execução real.</li>
                        <li>Está pronto para romper com padrões herdados, crenças compradas e desculpas caras.</li>
                        <li>Quer alinhar mente, rotina, renda e propósito com consistência.</li>
                    </ul>
                </div>

                <div class="for-who-box no">
                    <h3>Não é para quem:</h3>
                    <ul>
                        <li>Vem buscar "motivaçãozinha de palco" e selfie com frase de efeito.</li>
                        <li>Não suporta verdades dolorosas sobre suas escolhas e hábitos.</li>
                        <li>Quer terceirizar responsabilidade e culpar governo, família ou "falta de sorte".</li>
                        <li>Vai deixar o caderno mofando depois do evento.</li>
                        <li>Ainda acha que prosperar é questão de sorte, berço ou milagre instantâneo.</li>
                    </ul>
                </div>
            </div>
            <div style="text-align: center; margin-top: 50px;">
                <a href="#ingressos" class="cta-button">Quero garantir meu ingresso agora</a>
            </div>
        </div>
    </section>

    <!-- MECHANISM -->
    <section class="section section-dark">
        <div class="container">
            <h2>O mecanismo por trás da sua estagnação</h2>
            <div class="mechanism-box">
                <h3 style="color: #ff0000; font-size: 2rem;">Sistema F.R.A.C.A.S.S.O.™</h3>
                <p style="font-size: 1.2rem; margin-top: 20px;">
                    Existe um sistema instalado em você — silencioso, recorrente e confortável — que mantém sua vida financeira previsível… para baixo.
                </p>
                <p style="margin-top: 20px;">
                    Chamamos isso de <strong>Sistema F.R.A.C.A.S.S.O.™</strong>
                </p>
                <p style="margin-top: 30px; font-weight: 700;">Ele se alimenta de:</p>
                <ul style="margin-top: 20px;">
                    <li><strong>Frases como:</strong> "dinheiro é sujo", "sou pobre, mas honesto", "não nasci em berço de ouro", "dinheiro não é tão importante, amar sim".</li>
                    <li><strong>Emoções como:</strong> medo, culpa, raiva, vergonha, sensação de incapacidade.</li>
                    <li><strong>Padrões familiares:</strong> brigas por dinheiro, necessidade na infância, frases repetidas pelos pais.</li>
                    <li><strong>Hábitos automáticos:</strong> trabalhar demais, gastar sem consciência, nunca investir, nunca planejar.</li>
                </ul>
                <p style="margin-top: 30px; font-size: 1.2rem; font-weight: 700; color: #ff0000;">
                    Na imersão, você vai:
                </p>
                <ol style="margin-top: 20px; padding-left: 20px; color: #ddd;">
                    <li style="margin-bottom: 10px;">Tornar esse sistema visível.</li>
                    <li style="margin-bottom: 10px;">Quebrar as crenças que o alimentam.</li>
                    <li>Substituir por um novo sistema de prosperidade intencional.</li>
                </ol>
            </div>
        </div>
    </section>

    <!-- 4 STAGES -->
    <section class="section section-gray">
        <div class="container">
            <h2>As 4 etapas da imersão</h2>
            <p style="text-align: center; font-size: 1.2rem; margin-bottom: 40px; color: #ccc;">
                A Arquitetura Interna da Mudança
            </p>

            <div class="mechanism-steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3 style="color: #ff0000; font-size: 1.5rem;">Fissura de Identidade™</h3>
                    <p style="margin-top: 20px; font-size: 1rem;">
                        Você não ajusta só comportamentos. Você quebra a versão de si mesmo que "sempre foi assim".
                    </p>
                    <ul style="margin-top: 20px; text-align: left;">
                        <li style="font-size: 0.95rem;">Exercícios para mapear seu histórico emocional com o dinheiro.</li>
                        <li style="font-size: 0.95rem;">Identificação das crenças limitantes que regem suas decisões hoje.</li>
                        <li style="font-size: 0.95rem;">Exposição clara de quem você está sendo por causa do dinheiro — ou da falta dele.</li>
                    </ul>
                </div>

                <div class="step">
                    <div class="step-number">2</div>
                    <h3 style="color: #ff0000; font-size: 1.5rem;">Rasgo de Realidade™</h3>
                    <p style="margin-top: 20px; font-size: 1rem;">
                        Você confronta, sem anestesia, seus números e suas narrativas.
                    </p>
                    <ul style="margin-top: 20px; text-align: left;">
                        <li style="font-size: 0.95rem;">Diagnóstico da sua vida financeira atual (ganhos, gastos, patrimônio, dívidas).</li>
                        <li style="font-size: 0.95rem;">Mapa da Vida Sistêmica (MVS) para enxergar como o dinheiro contamina todas as áreas.</li>
                        <li style="font-size: 0.95rem;">Confronto entre a vida que você diz que quer e a vida que está de fato construindo.</li>
                    </ul>
                </div>

                <div class="step">
                    <div class="step-number">3</div>
                    <h3 style="color: #ff0000; font-size: 1.5rem;">Arquitetura de Futuro™</h3>
                    <p style="margin-top: 20px; font-size: 1rem;">
                        Sem fantasia. Sem "vision board" vazio.
                    </p>
                    <ul style="margin-top: 20px; text-align: left;">
                        <li style="font-size: 0.95rem;">Definição clara de metas financeiras e de estilo de vida.</li>
                        <li style="font-size: 0.95rem;">Desenho da sua Liberdade Financeira: quanto, quando, como.</li>
                        <li style="font-size: 0.95rem;">Personalidade do Dinheiro: entender se você é gastador, evitador, monge ou poupador e reprogramar isso.</li>
                    </ul>
                </div>

                <div class="step">
                    <div class="step-number">4</div>
                    <h3 style="color: #ff0000; font-size: 1.5rem;">Compromisso Inegociável™</h3>
                    <p style="margin-top: 20px; font-size: 1rem;">
                        Sem esse bloco, tudo vira caderno bonito.
                    </p>
                    <ul style="margin-top: 20px; text-align: left;">
                        <li style="font-size: 0.95rem;">Plano de 90 dias com metas, datas, números e consequências.</li>
                        <li style="font-size: 0.95rem;">Ferramentas de NeuroProgramação Financeira para instalar novos hábitos.</li>
                        <li style="font-size: 0.95rem;">Um pacto real com você mesmo: o que é inegociável a partir do dia seguinte.</li>
                    </ul>
                </div>
            </div>

            <div style="text-align: center; margin-top: 50px;">
                <a href="#ingressos" class="cta-button">Quero garantir meu ingresso agora</a>
            </div>
        </div>
    </section>

    <!-- PROGRAM -->
    <section class="section section-dark">
        <div class="container">
            <h2>Programação dos dois dias</h2>

            <div class="day-program">
                <h3>DIA 1 – O DIA EM QUE VOCÊ VAI SE DESMASCARAR</h3>
                <p class="subtitle-day">Você termina o dia com decisões tomadas — ou exposto demais para continuar fingindo.</p>

                <ul style="margin-top: 30px;">
                    <li><strong>Abertura:</strong> Por que sua vida financeira está onde está.</li>
                    <li><strong>Diagnóstico Financeiro:</strong> O que você ganha, como gasta, quanto vale, quanto deve.</li>
                    <li><strong>Relação Emocional com o Dinheiro:</strong> Qual emoção a falta de dinheiro aciona em você (medo, raiva, incapacidade, culpa, vergonha, abandono?).</li>
                    <li><strong>Infância & Dinheiro:</strong> Acontecimentos marcantes, frases dos pais, traumas e marcas de escassez.</li>
                    <li><strong>28 Crenças Limitantes:</strong> Identificação, exposição e início da reprogramação.</li>
                    <li><strong>Círculo de Excelência:</strong> Criação de estados emocionais fortalecedores para decisões financeiras.</li>
                </ul>

                <p style="margin-top: 30px; font-size: 1.2rem; font-weight: 700; color: #ff0000;">
                    Você sai do primeiro dia sabendo:
                </p>
                <ul style="margin-top: 15px;">
                    <li>O que, exatamente, está te sabotando.</li>
                    <li>Como você mesmo vem queimando dinheiro.</li>
                    <li>Quanto está custando manter o padrão atual nos próximos 5 anos.</li>
                </ul>
            </div>

            <div class="day-program">
                <h3>DIA 2 – O DIA EM QUE SUA NOVA VIDA VAI SER ESCRITA</h3>
                <p class="subtitle-day">Plano com datas, números e dor. Execução inegociável.</p>

                <ul style="margin-top: 30px;">
                    <li><strong>Redesenho da sua identidade financeira:</strong> Quem você escolhe ser a partir de agora.</li>
                    <li><strong>Reprogramação de Crenças:</strong> "Eu sou imã do dinheiro. Eu tenho a mente milionária" — como afirmação ancorada em comportamento real.</li>
                    <li><strong>NeuroProgramação Financeira:</strong> Hábitos diários que governam resultados financeiros.</li>
                    <li><strong>Mapa de 90 Dias:</strong> Metas, ações, indicadores, rotina de execução.</li>
                    <li><strong>Estrutura de Multiplicação do Dinheiro:</strong> Ativos x passivos, liberdade financeira e fluxo.</li>
                    <li><strong>Compromisso Público:</strong> Você assume, em voz alta, o padrão que está encerrando e o novo padrão que escolhe.</li>
                </ul>
            </div>

            <div style="text-align: center; margin-top: 50px;">
                <a href="#ingressos" class="cta-button">Quero garantir meu ingresso agora</a>
            </div>
        </div>
    </section>

    <!-- TRAINERS -->
    <section class="section section-gray">
        <div class="container">
            <h2>Quem vai te conduzir</h2>
            <p style="text-align: center; font-size: 1.2rem; margin-bottom: 40px; color: #ccc;">
                Sobre os treinadores
            </p>

            <div class="trainers-grid">
                <div class="trainer-card">
                    <div class="trainer-name">Thiago Labastie</div>
                    <div class="trainer-title">Criador do Método PSL – Prosperidade Sem Limites</div>

                    <p class="trainer-description">
                        Treinador em inteligência emocional financeira, com atuação em Coaching, PNL, Psicologia Positiva, 
                        Neurociências, Reprogramação de Crenças e Física Quântica aplicada ao comportamento.
                    </p>

                    <p class="trainer-description">
                        Guia pessoas e empresas a romperem com padrões de escassez, saírem da corrida dos ratos e 
                        construírem liberdade financeira com consciência e responsabilidade.
                    </p>

                    <div class="trainer-highlights">
                        <p style="font-weight: 700; color: #ff0000; margin-bottom: 15px;">Especialidades:</p>
                        <ul>
                            <li>Especialista em reprogramação crença-emocional ligada ao dinheiro.</li>
                            <li>Facilitador de processos profundos de renascimento financeiro e emocional.</li>
                            <li>Conduz dinâmicas práticas, intensas e, muitas vezes, desconfortáveis — porém transformadoras.</li>
                        </ul>
                    </div>
                </div>

                <div class="trainer-card">
                    <div class="trainer-name">Vanessa Labastie</div>
                    <div class="trainer-title">Treinadora Emocional & Especialista em NeuroHearth</div>

                    <p class="trainer-description">
                        Especialista em NeuroHearth, Breathwork (neurociência da respiração), Psicologia Positiva 
                        e práticas de cura emocional.
                    </p>

                    <p class="trainer-description">
                        Responsável por criar o ambiente seguro (e firme) para que você consiga acessar dores profundas 
                        sem travar, para então transformá-las em energia de ação.
                    </p>

                    <div class="trainer-highlights">
                        <p style="font-weight: 700; color: #ff0000; margin-bottom: 15px;">Especialidades:</p>
                        <ul>
                            <li>Facilitadora de processos de cura emocional.</li>
                            <li>Experiência com grupos, imersões e atendimentos voltados à relação com dinheiro, merecimento e autoimagem.</li>
                            <li>Referência em criar estados emocionais fortalecedores que sustentam decisões financeiras difíceis.</li>
                        </ul>
                    </div>
                </div>
            </div>

            <div class="why-box" style="margin-top: 50px;">
                <h3 style="color: #ff0000;">Por que isso importa para você?</h3>
                <p style="margin-top: 20px;">
                    Porque não é mais um evento de "motivação" ou "finanças básicas".<br>
                    É um trabalho de fundo emocional, neurológico e comportamental, feito por quem estuda e pratica isso há anos, 
                    com metodologia, processo e responsabilidade.
                </p>
            </div>
        </div>
    </section>

    <!-- BENEFITS -->
    <section class="section section-dark">
        <div class="container">
            <h2>O que você leva (de forma objetiva)</h2>

            <div class="benefits-grid">
                <div class="benefit-item">
                    <h4>Clareza Cirúrgica</h4>
                    <p>Sobre o que está travando sua vida financeira.</p>
                </div>

                <div class="benefit-item">
                    <h4>Consciência Emocional</h4>
                    <p>Do seu padrão com dinheiro (medo, culpa, raiva, escassez).</p>
                </div>

                <div class="benefit-item">
                    <h4>Plano de 90 Dias</h4>
                    <p>Com prazos, metas e ações específicas.</p>
                </div>

                <div class="benefit-item">
                    <h4>Ferramentas de Reprogramação</h4>
                    <p>Para reprogramar crenças limitantes sobre riqueza, pessoas ricas e sobre você mesmo.</p>
                </div>

                <div class="benefit-item">
                    <h4>Novo Padrão Mental</h4>
                    <p>De prosperidade, ancorado em hábitos diários.</p>
                </div>

                <div class="benefit-item">
                    <h4>Conexões Poderosas</h4>
                    <p>Com pessoas decididas a romper com a escassez.</p>
                </div>

                <div class="benefit-item">
                    <h4>Compromisso Inegociável</h4>
                    <p>Com a sua próxima fase.</p>
                </div>
            </div>

            <div class="why-box" style="margin-top: 50px; text-align: center;">
                <p style="font-size: 1.3rem; font-weight: 700; color: #ff0000;">
                    Se você tratar esse evento como mais um, nada muda.<br>
                    Se tratar como divisor, sua vida nunca mais volta ao ponto anterior.
                </p>
            </div>
        </div>
    </section>

    <!-- TESTIMONIALS -->
    <section class="section section-gray">
        <div class="container">
            <h2>O que dizem quem já passou pela transformação</h2>
            <p style="text-align: center; font-size: 1.1rem; margin-bottom: 40px; color: #ccc;">
                Resultado e segurança comprovados
            </p>

            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <p class="testimonial-text">
                        "Eu trabalhava sem parar, mas nunca via dinheiro sobrar. Na imersão, entendi que eu repetia o padrão 
                        da minha família de 'sobreviver'. Três meses depois, reorganizei minhas finanças, aumentei minha renda 
                        em 40% e comecei a investir pela primeira vez."
                    </p>
                    <p class="testimonial-author">[Nome do Cliente]</p>
                    <p class="testimonial-info">[Profissão], [Cidade]</p>
                </div>

                <div class="testimonial-card">
                    <p class="testimonial-text">
                        "Achei que fosse 'mais um evento de motivação'. Saí de lá com um soco de realidade e um plano de 90 dias. 
                        Em menos de 4 meses, quitei dívidas antigas, renegociei contratos e criei uma nova fonte de renda."
                    </p>
                    <p class="testimonial-author">[Nome do Cliente]</p>
                    <p class="testimonial-info">[Profissão], [Cidade]</p>
                </div>

                <div class="testimonial-card">
                    <p class="testimonial-text">
                        "Minha maior trava era cobrar o justo pelo meu trabalho. Carregava a crença de que 'sou pobre, mas honesto' 
                        e 'dinheiro é sujo'. No evento, virei essa chave. Hoje, cobro pelo meu valor, trabalho menos e ganho mais."
                    </p>
                    <p class="testimonial-author">[Nome do Cliente]</p>
                    <p class="testimonial-info">[Profissão], [Cidade]</p>
                </div>

                <div class="testimonial-card">
                    <p class="testimonial-text">
                        "O evento mais desconfortável que já vivi – e o mais necessário. Confrontei padrões que carregava há décadas. 
                        Nunca mais olhei para o dinheiro do mesmo jeito."
                    </p>
                    <p class="testimonial-author">[Nome do Cliente]</p>
                    <p class="testimonial-info">[Profissão], [Cidade]</p>
                </div>

                <div class="testimonial-card">
                    <p class="testimonial-text">
                        "Foi um divisor de águas na minha vida financeira e emocional. Saí com clareza, plano e, principalmente, 
                        com coragem para executar o que sempre soube que precisava fazer."
                    </p>
                    <p class="testimonial-author">[Nome do Cliente]</p>
                    <p class="testimonial-info">[Profissão], [Cidade]</p>
                </div>

                <div class="testimonial-card">
                    <p class="testimonial-text">
                        "Descobri que meu problema não era falta de dinheiro, mas falta de identidade financeira. 
                        Hoje, sei quem sou em relação ao dinheiro — e isso mudou tudo."
                    </p>
                    <p class="testimonial-author">[Nome do Cliente]</p>
                    <p class="testimonial-info">[Profissão], [Cidade]</p>
                </div>
            </div>
        </div>
    </section>

    <!-- TICKETS -->
    <section class="section section-dark" id="ingressos">
        <div class="container">
            <h2>Tipos de Ingresso</h2>

            <div class="tickets-grid">
                <!-- DIAMOND -->
                <div class="ticket-card featured">
                    <div class="ticket-name">DIAMOND</div>
                    <div class="ticket-price">R$ 1.997</div>
                    <div class="ticket-features">
                        <ul>
                            <li>✓ Primeiras fileiras</li>
                            <li>✓ Café da manhã + Almoço com equipe</li>
                            <li>✓ Mini mentoria com Thiago e Vanessa</li>
                            <li>✓ Gravação completa da imersão</li>
                            <li>✓ Kit premium exclusivo</li>
                            <li>✓ Material impresso completo</li>
                            <li>✓ Área VIP</li>
                        </ul>
                    </div>
                    <a href="#checkout" class="cta-button" style="width: 100%; display: block; text-align: center;">
                        Quero o Ingresso Diamond
                    </a>
                </div>

                <!-- VIP GOLD -->
                <div class="ticket-card">
                    <div class="ticket-name">VIP GOLD</div>
                    <div class="ticket-price">R$ 997</div>
                    <div class="ticket-features">
                        <ul>
                            <li>✓ Área reservada com melhor visão do palco</li>
                            <li>✓ Café da manhã nos dois dias</li>
                            <li>✓ Kit Gold</li>
                            <li>✓ Material impresso completo</li>
                            <li>✓ Área VIP</li>
                        </ul>
                    </div>
                    <a href="#checkout" class="cta-button" style="width: 100%; display: block; text-align: center;">
                        Quero o Ingresso VIP Gold
                    </a>
                </div>

                <!-- PRATA -->
                <div class="ticket-card">
                    <div class="ticket-name">ÁREA PRATA</div>
                    <div class="ticket-price" style="font-size: 1.5rem;">POR CONVITE</div>
                    <div class="ticket-features">
                        <ul>
                            <li>✓ Acesso completo aos dois dias de imersão</li>
                            <li>✓ Área separada com visão do conteúdo</li>
                            <li>✓ Conteúdo completo da metodologia PSL</li>
                            <li>✓ Exercícios de reprogramação</li>
                            <li>✓ Plano de 90 dias</li>
                        </ul>
                    </div>
                    <a href="#checkout" class="cta-button" style="width: 100%; display: block; text-align: center;">
                        Tenho convite e quero confirmar
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- COMPARISON TABLE -->
    <section class="section section-gray">
        <div class="container">
            <h2>Comparativo Rápido</h2>

            <div class="comparison-table">
                <table>
                    <thead>
                        <tr>
                            <th>Benefícios</th>
                            <th style="text-align: center;">Prata</th>
                            <th style="text-align: center;">Gold</th>
                            <th style="text-align: center;">Diamond</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>2 dias de imersão presencial</td>
                            <td class="check">✓</td>
                            <td class="check">✓</td>
                            <td class="check">✓</td>
                        </tr>
                        <tr>
                            <td>Conteúdo completo da metodologia PSL</td>
                            <td class="check">✓</td>
                            <td class="check">✓</td>
                            <td class="check">✓</td>
                        </tr>
                        <tr>
                            <td>Exercícios de reprogramação e plano de 90 dias</td>
                            <td class="check">✓</td>
                            <td class="check">✓</td>
                            <td class="check">✓</td>
                        </tr>
                        <tr>
                            <td>Área VIP</td>
                            <td class="cross">✗</td>
                            <td class="check">✓</td>
                            <td class="check">✓</td>
                        </tr>
                        <tr>
                            <td>Material impresso físico</td>
                            <td class="cross">✗</td>
                            <td class="check">✓</td>
                            <td class="check">✓</td>
                        </tr>
                        <tr>
                            <td>Café da manhã nos dois dias</td>
                            <td class="cross">✗</td>
                            <td class="check">✓</td>
                            <td class="check">✓</td>
                        </tr>
                        <tr>
                            <td>Primeiras fileiras</td>
                            <td class="cross">✗</td>
                            <td class="cross">✗</td>
                            <td class="check">✓</td>
                        </tr>
                        <tr>
                            <td>Almoço exclusivo com a equipe</td>
                            <td class="cross">✗</td>
                            <td class="cross">✗</td>
                            <td class="check">✓</td>
                        </tr>
                        <tr>
                            <td>Mini mentoria com Thiago e Vanessa</td>
                            <td class="cross">✗</td>
                            <td class="cross">✗</td>
                            <td class="check">✓</td>
                        </tr>
                        <tr>
                            <td>Gravação completa do evento</td>
                            <td class="cross">✗</td>
                            <td class="cross">✗</td>
                            <td class="check">✓</td>
                        </tr>
                        <tr>
                            <td>Kit premium</td>
                            <td class="cross">✗</td>
                            <td class="cross">✗</td>
                            <td class="check">✓</td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <div style="text-align: center; margin-top: 50px;">
                <a href="#ingressos" class="cta-button">Quero garantir meu ingresso agora</a>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="section section-dark">
        <div class="container">
            <h2>Perguntas Frequentes</h2>

            <div class="faq-container">
                <div class="faq-item">
                    <div class="faq-question">E se eu não tiver experiência com finanças?</div>
                    <div class="faq-answer">
                        Perfeito. Essa imersão não é sobre técnicas financeiras avançadas. É sobre reprogramar sua relação 
                        emocional e mental com o dinheiro. Você não precisa ser expert em finanças — precisa estar disposto 
                        a encarar a verdade sobre seus padrões.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">Esse evento é para quem está endividado ou para quem já ganha bem?</div>
                    <div class="faq-answer">
                        Para ambos. Se você está endividado, vai entender o que te levou até aqui e como sair. 
                        Se já ganha bem mas não acumula, vai descobrir onde está queimando dinheiro e sabotando sua liberdade financeira. 
                        O problema raramente é quanto você ganha — é como você se relaciona com o que ganha.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">Vai ter venda de outros programas lá dentro?</div>
                    <div class="faq-answer">
                        Sim, haverá apresentação de programas de continuidade para quem quiser aprofundar o trabalho. 
                        Mas não é obrigatório. Você sai da imersão com tudo que precisa para executar nos próximos 90 dias. 
                        Se quiser acelerar com mentoria, a opção estará disponível.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">Posso ir com meu cônjuge?</div>
                    <div class="faq-answer">
                        Sim, e é altamente recomendado. Quando o casal passa pela imersão junto, o alinhamento financeiro 
                        e emocional acelera muito. Cada um precisa de seu próprio ingresso.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">Qual a política de cancelamento?</div>
                    <div class="faq-answer">
                        Você tem até o final do primeiro dia para solicitar reembolso de 70% do valor pago, caso sinta que 
                        o evento não é para você. Após esse período, não há reembolso.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">Como funciona o parcelamento?</div>
                    <div class="faq-answer">
                        Aceitamos cartão de crédito em até 12x e PIX à vista com desconto. 
                        As condições específicas aparecem no checkout.
                    </div>
                </div>

                <div class="faq-item">
                    <div class="faq-question">Quantas vagas estão disponíveis?</div>
                    <div class="faq-answer">
                        Vagas limitadas por categoria: 30 Diamond, 60 Gold, 40 Prata (por convite). 
                        Quando esgotar, não abrimos novas vagas.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FINAL PRESSURE -->
    <section class="pressure-section">
        <div class="container">
            <h2>VOCÊ TEM DOIS CAMINHOS AGORA:</h2>

            <p class="pressure-text">
                Ou você adia, mais uma vez, a decisão que pode mudar tudo…
            </p>

            <p class="pressure-text">
                Ou quebra o padrão que te custou anos.
            </p>

            <p class="pressure-highlight">
                Não é sobre "poder pagar" o ingresso.<br>
                É sobre quanto custa continuar repetindo o mesmo ano, de novo.
            </p>

            <p class="pressure-text" style="font-size: 2rem; font-weight: 900; margin-top: 50px;">
                Dois dias.<br>
                Uma decisão.<br>
                Um novo ciclo.
            </p>

            <div style="margin-top: 50px;">
                <a href="#ingressos" class="cta-button" style="font-size: 1.5rem; padding: 25px 60px;">
                    QUERO GARANTIR MEU INGRESSO AGORA
                </a>
            </div>

            <p style="margin-top: 50px; font-size: 1.1rem; color: #ccc;">
                São Paulo – 28 e 29 de janeiro de 2026<br>
                Imersão Prosperidade Sem Limites
            </p>
        </div>
    </section>

</body>
</html>
