 {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    color: white;
    background-color: black;
    margin: 0;
    font-family: "Chakra Petch", sans-serif;
    margin-bottom: 100px;
    line-height: 1.6; /* Melhora a legibilidade */
}

header {
    border-bottom: 2px solid rgb(42, 122, 228);
    padding: 20px;
    font-size: 32px;
    color: rgb(42, 122, 228);
    text-align: center; /* Centraliza o título */
    background-color: #111; /* Aumenta o contraste com o conteúdo */
}

.chamada {
    background-color: rgb(184, 156, 213);
    padding: 80px 0;
    display: flex;
    justify-content: center;
    flex-wrap: wrap; /* Responsivo para telas menores */
    text-align: center; /* Centraliza o conteúdo */
}

.chamada-texto {
    margin-right: 5%;
    max-width: 600px; /* Limita a largura para melhorar a leitura */
}

h1 {
    font-size: 40px;
    font-weight: 700; /* Reforça a importância do título */
    text-transform: uppercase; /* Maiúsculas para títulos */
    margin-bottom: 20px; /* Espaço inferior */
}

p {
    font-size: 20px;
    margin-bottom: 20px; /* Espaçamento entre parágrafos */
}

.categoria {
    padding: 50px 20px;
}

.categoria h2 {
    color: rgb(42, 122, 228);
    text-align: center;
    font-size: 28px;
    text-transform: uppercase;
    margin-bottom: 30px;
}

.categoria-videos {
    display: flex;
    overflow-x: auto;
    gap: 10px;
    padding-bottom: 20px;
    scroll-behavior: smooth; /* Adiciona rolagem suave */
}

/* Estilização das Imagens de Vídeos */
.categoria-videos img {
    opacity: 0.5;
    height: 200px;
    transition: opacity 0.3s ease, border 0.3s ease; /* Animação suave */
    cursor: pointer;
}

.categoria-videos img:hover {
    opacity: 1;
    border: 3px solid green;
}

/* Ajustes de responsividade para telas menores */
@media (max-width: 768px) {
    .chamada-texto {
        margin-right: 0;
        max-width: 100%;
    }

    header {
        font-size: 28px;
    }

    h1 {
        font-size: 32px;
    }

    p {
        font-size: 18px;
    }

    .categoria-videos img {
        height: 150px;
    }
}
