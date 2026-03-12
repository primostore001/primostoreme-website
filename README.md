#https://primogemstore.mee/website
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PRIMOSTORE / HOYOSTORE</title>
<style>
    /* Reset básico */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
        font-family: Arial, sans-serif;
        background-color: #f8f9fa;
        color: #1a1a1a;
        scroll-behavior: smooth;
    }

    /* Header */
    header {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        background: linear-gradient(90deg, #1e1a55, #4b0082);
        color: white;
        padding: 15px 0;
        text-align: center;
        z-index: 1000;
        box-shadow: 0 3px 6px rgba(0,0,0,0.2);
    }

    header h1 {
        margin-bottom: 5px;
        font-size: 28px;
    }

    nav a {
        color: white;
        margin: 0 15px;
        text-decoration: none;
        font-weight: bold;
        transition: color 0.3s;
    }

    nav a:hover {
        color: #ffcc00;
    }

    /* Container */
    .container {
        max-width: 1000px;
        margin: 120px auto 50px;
        padding: 0 20px;
    }

    /* Sections */
    .section {
        margin-bottom: 50px;
        background-color: #fff;
        padding: 25px;
        border-radius: 10px;
        box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .section h2 {
        margin-bottom: 15px;
        color: #4b0082;
        border-bottom: 2px solid #1e1a55;
        padding-bottom: 5px;
    }

    /* Services */
    .service {
        border-top: 1px solid #ddd;
        padding: 15px 0;
    }

    .service:first-child { border-top: none; }

    .service strong {
        color: #1e1a55;
    }

    .price {
        color: #4b0082;
        font-weight: bold;
    }

    .note {
        font-style: italic;
        color: #555;
        margin-top: 10px;
    }

    /* Buttons */
    .btn-contact {
        display: inline-block;
        margin-top: 10px;
        padding: 10px 20px;
        background-color: #4b0082;
        color: white;
        border-radius: 5px;
        text-decoration: none;
        transition: background 0.3s;
    }

    .btn-contact:hover {
        background-color: #1e1a55;
    }

    /* Footer */
    footer {
        text-align: center;
        padding: 20px;
        background-color: #1e1a55;
        color: white;
        margin-top: 50px;
    }

    /* Scroll anchor offset */
    section { scroll-margin-top: 90px; }

</style>
</head>
<body>

<header>
    <h1>PRIMOSTORE / HOYOSTORE</h1>
    <nav>
        <a href="#reroll">Reroll & Preços</a>
        <a href="#trabalhos">Trabalhos Individuais</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<div class="container">

    <!-- Setor: Reroll -->
    <section id="reroll" class="section">
        <h2>Reroll & Preços</h2>
        <p class="note">Aceitamos Sonhos e Nitro como pagamento. Mais detalhes em nossa DM.</p>

        <div class="service">
            <p><strong>Reroll NV 1</strong> - <span class="price">R$10,00</span></p>
            <p>Conta low player: personagens básicos upados, AR 30+, 10k+ primogemas, 0 desejos realizados, armas gratuitas (F2P). Mais informações ao nos contatar.</p>
        </div>

        <div class="service">
            <p><strong>Reroll NV 2</strong> - <span class="price">R$15,00+</span></p>
            <p>Conta low player: personagens básicos + 4 personagens aleatórios, AR 30+, 15k+ primogemas, 10-15 desejos realizados, armas F2P + 1 arma T4 de sua escolha (+ de 3 armas: +R$1,00, risco de armas aleatórias). Mantemos primogemas!</p>
        </div>

        <div class="service">
            <p><strong>Reroll NV 3</strong> - <span class="price">R$20,00</span></p>
            <p>Conta mid player: personagens básicos + T4 aleatórios + 1 T5 aleatório (mochileiro não incluso), AR 35+, 20k+ primogemas, armas T4 aleatórias + 1 T5 opcional (+R$5,00, ou +R$2 sem escolha). Mantemos primogemas!</p>
        </div>

        <div class="service">
            <p><strong>Reroll NV 4</strong> - <span class="price">R$26,00</span></p>
            <p>Conta mid player: personagens básicos + T4 aleatórios + 1 T5 de sua preferência, AR 40+, 25k+ primogemas, 1 arma T5 aleatória + T4 aleatórias e T4 de escolha (+R$1,00). Mantemos primogemas!</p>
        </div>

        <div class="service">
            <p><strong>Reroll NV 5</strong> - <span class="price">R$30,00</span></p>
            <p>Conta high player: personagens básicos + 10 T4 de sua escolha + T4 aleatórios + 2 T5 de sua escolha, AR 50-, 30k+ primogemas, 1 arma T5 de escolha + 1 arma T5 aleatória + armas T4 aleatórias (taxa T4 desejada: R$1,00 + 1 giro perdido a cada 10 desejos). Mais informações ao nos contatar.</p>
        </div>

        <p class="note">Caso queira um pedido específico, entre em contato conosco (a negociar).</p>
    </section>

    <!-- Setor: Trabalhos Individuais -->
    <section id="trabalhos" class="section">
        <h2>Trabalhos Individuais</h2>
        <p class="note">Não aceitamos pagamentos em Nitro ou Impulsos nos serviços individuais.</p>

        <div class="service">
            <p><strong>001: A cada 10 giros</strong> - R$6,00 (1600 gemas)</p>
        </div>

        <div class="service">
            <p><strong>002: Ascensão</strong></p>
            <p>Nv1 ao Nv60: R$2,00 a cada 10 níveis.<br>Nv60 ao 90: R$5,00 a cada 10 níveis.</p>
        </div>

        <div class="service">
            <p><strong>003: Build</strong> - Valor a negociar</p>
        </div>

        <div class="service">
            <p><strong>004: Exploração</strong></p>
            <p>0% ao 50%: R$6,00<br>50% ao 100%: R$12,00<br>0% ao 100%: R$18,00</p>
        </div>

        <div class="service">
            <p><strong>005: Serviços não listados</strong></p>
            <p>Entre em contato para negociar preço e prazo.</p>
        </div>
    </section>

    <!-- Contato -->
    <section id="contato" class="section">
        <h2>Contato</h2>
        <p>TikTok: <a href="https://www.tiktok.com/@pr_store.me" target="_blank">@pr_store.me</a></p>
        <p>Email: <a href="mailto:aprimostore001@gmail.com">aprimostore001@gmail.com</a></p>
        <a class="btn-contact" href="mailto:aprimostore001@gmail.com">Enviar Email</a>
        <a class="btn-contact" href="https://www.tiktok.com/@pr_store.me" target="_blank">Ver TikTok</a>
    </section>

</div>

<footer>
    <p>PRIMOSTORE / HOYOSTORE &copy; 2026</p>
</footer>

</body>
</html>