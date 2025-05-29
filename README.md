<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Feira Gastronômica - Do Campo à Cidade</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <div class="wood-sign">
                <img src="https://pplx-res.cloudinary.com/image/private/user_uploads/40437733/d36b3356-915a-4c9e-bb20-ca88a0facd52/FEIRA-GASTRONOMICA.jpg" alt="Feira Gastronômica - Do Campo à Cidade" class="logo">
                <div class="sign-text">
                    FEIRA GASTRONÔMICA - DO CAMPO À CIDADE
                </div>
            </div>
        </header>
        <main>
            <section class="intro">
                <h2>Convite Especial para a Feira Gastronômica</h2>
                <p>
                    Você é nosso convidado especial para uma experiência única de sabores e aromas!
                </p>
                <p>
                    Venha desfrutar de pratos incríveis, preparados por chefs renomados e talentos locais. Teremos opções para todos os gostos: culinária regional, internacional, vegan, doces artesanais e muito mais!
                </p>
            </section>
            <section class="destaques">
                <div class="card">
                    <img src="https://cdn.panelinha.com.br/receita/1582558000000-feijao-tropeiro.jpg" alt="Feijão tropeiro">
                    <span>Feijão tropeiro</span>
                </div>
                <div class="card">
                    <img src="https://static.itdg.com.br/images/auto-auto/2b1b5e6c7d1b8b3b6a3a0a8a2e9e7a7b/pamonha.jpg" alt="Pamonha">
                    <span>Pamonha</span>
                </div>
                <div class="card">
                    <img src="https://www.sabornamesa.com.br/media/k2/items/cache/9d2d5a6a5a2fae3b0c8a7f8b9a1e9a3a_XL.jpg" alt="Queijo">
                    <span>Queijo</span>
                </div>
            </section>
            <section class="evento">
                <img src="https://images.unsplash.com/photo-1519864600265-abb23847ef2c?auto=format&fit=crop&w=600&q=80" alt="Banda ao vivo">
                <div class="evento-info">
                    <h3>Feira Gastronômica 2025</h3>
                    <p>Data: 10 a 12 de junho</p>
                    <p>Horário: Das 11h às 22h</p>
                    <p>Local: Praça Central da Cidade</p>
                </div>
            </section>
            <section class="extras">
                <p>
                    Além da comida deliciosa, aproveite música ao vivo, oficinas culinárias e atividades para toda a família.
                </p>
                <p>
                    Não perca essa festa dos sentidos! Traga amigos e familiares para celebrar a cultura e a gastronomia conosco.<br>
                    Esperamos por você!
                </p>
            </section>
        </main>
    </div>
</body>
</html>
body {
    margin: 0;
    padding: 0;
    background: #9b4e2a;
    font-family: 'Courier New', Courier, monospace;
    color: #fff8f0;
}

.container {
    max-width: 700px;
    margin: 0 auto;
    background: #9b4e2a;
    padding: 30px 20px;
}

header {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 18px;
}

.wood-sign {
    position: relative;
    width: 360px;
    height: 140px;
    margin-bottom: 16px;
}

.logo {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
    border: 3px solid #7c3a1e;
}

.sign-text {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 100%;
    text-align: center;
    transform: translate(-50%, -50%);
    font-size: 1.1rem;
    color: #fffbe7;
    font-weight: bold;
    letter-spacing: 2px;
    text-shadow: 2px 2px 4px #7c3a1e;
    pointer-events: none;
}

.intro h2 {
    font-size: 1.35rem;
    margin-bottom: 6px;
    color: #fffbe7;
}

.intro p {
    margin: 8px 0;
    font-size: 1.02rem;
    color: #fff8f0;
}

.destaques {
    display: flex;
    justify-content: space-between;
    margin: 20px 0 18px 0;
}

.card {
    background: #fffbe7;
    color: #9b4e2a;
    border-radius: 7px;
    width: 30%;
    text-align: center;
    box-shadow: 0 2px 7px rgba(0,0,0,0.08);
    padding: 10px 4px 8px 4px;
}

.card img {
    width: 95%;
    height: 90px;
    object-fit: cover;
    border-radius: 6px;
    margin-bottom: 7px;
}

.card span {
    font-size: 1rem;
    font-weight: bold;
}

.evento {
    display: flex;
    align-items: flex-start;
    margin: 18px 0;
    gap: 18px;
}

.evento img {
    width: 170px;
    height: 110px;
    object-fit: cover;
    border-radius: 8px;
    box-shadow: 0 2px 7px rgba(0,0,0,0.10);
    border: 2px solid #fffbe7;
}

.evento-info {
    flex: 1;
}

.evento-info h3 {
    margin: 0 0 6px 0;
    color: #fffbe7;
    font-size: 1.13rem;
}

.evento-info p {
    margin: 2px 0;
    color: #fff8f0;
    font-size: 1.01rem;
}

.extras {
    margin-top: 18px;
    font-size: 1.05rem;
    color: #fffbe7;
}

@media (max-width: 800px) {
    .container {
        padding: 12px 2vw;
    }
    .destaques {
        flex-direction: column;
        gap: 14px;
    }
    .card {
        width: 100%;
    }
    .evento {
        flex-direction: column;
        align-items: center;
        gap: 10px;
    }
    .evento img {
        width: 95vw;
        max-width: 300px;
        height: 100px;
    }
}
