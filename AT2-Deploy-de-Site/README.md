# 🎮 GAMES_PPS - Portal de Jogos

## 📝 Descrição do Projeto
Este projeto consiste num portal web interativo voltado para o universo dos videojogos, desenvolvido para centralizar conteúdos como recomendações de títulos populares, secção de novidades, ofertas especiais e organização por categorias[cite: 1, 2, 3, 4, 5]. O objetivo principal é proporcionar uma interface limpa, intuitiva e responsiva para os utilizadores navegarem por diferentes secções de entretenimento digital.

O projeto foi estruturado através de várias páginas em HTML5 estruturadas de forma modular (`index.html`, `jogos.html`, `novidades.html`, `ofertas.html` e `categorias.html`) acompanhadas por uma folha de estilos dedicada (`css/games.css`)[cite: 1, 2, 3, 4, 5].

## 🚀 Tecnologias Utilizadas
- **Linguagens:** HTML5 e CSS3
- **Ferramentas:** VSCode e Git/GitHub Pages
- **Suporte de IA:** Gemini

## 📂 Estrutura de Páginas e Processo de Desenvolvimento
A arquitetura do site foi dividida em componentes modulares para facilitar a navegação e a manutenção:
- **`index.html` (Página Inicial):** Serve como ponto de entrada principal do portal, apresentando um banner de boas-vindas (*hero section*) e atalhos rápidos para as principais áreas da plataforma[cite: 2].
- **`jogos.html` (Secção de Jogos):** Exibe uma montra de títulos populares de destaque no mercado (como *Grand Theft Auto V*, *Minecraft*, *God of War Ragnarök*, entre outros), detalhando breves descrições e ícones representativos[cite: 3].
- **`ofertas.html` (Promoções):** Apresenta uma tabela de preços promocionais com indicação de descontos e valores antigos/atuais para grandes títulos[cite: 5].
- **`novidades.html` (Notícias):** Mantém o utilizador atualizado com publicações sobre atualizações, lançamentos e campeonatos do ecossistema gamer[cite: 4].
- **`categorias.html` (Géneros):** Organiza os estilos de jogo por categorias (Ação, Corrida, RPG, Tiro, Esportes e Estratégia)[cite: 1].

## 👀 Visualização do Projeto
Você pode conferir o resultado final do portal funcionando diretamente através do link do deploy abaixo:

- **Site Oficial:** [https://paulo984-ss.github.io/sites/](https://paulo984-ss.github.io/sites/)

Abaixo estão alguns trechos do código-fonte estruturados nas páginas do projeto:

### Exemplo da Página Inicial (`index.html`)
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🎮 GAMES_PPS - Início</title>
    <link rel="stylesheet" href="css/games.css">
</head>
<body>
    <div class="container">
        <header>
            <h1 class="logo">🎮 GAMES_PPS</h1>
            <p class="subtitle">O seu universo gamer</p>
        </header>

        <nav>
            <ul>
                <li><a class="active" href="index.html
