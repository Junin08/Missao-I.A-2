# 🚀 Missão IA: Você Decide o Futuro da Inteligência Artificial

Projeto web interativo e educacional desenvolvido durante as aulas de programação web (**FIAP / Alura**), focado nos impactos, desafios e possibilidades do avanço da Inteligência Artificial em nossas vidas.

---

## 📖 Sobre o Projeto

O **Missão IA** é uma aplicação interativa do tipo "escolha sua própria aventura". O jogador é apresentado a uma narrativa envolvente onde suas decisões afetam a trajetória da história e definem um resultado final personalizado.

### 🌟 Principais Recursos:
- **Tela Inicial:** Apresentação da missão com botão de início para introduzir o jogador na história antes das perguntas.
- **Nomes Aleatórios:** Personalização dinâmica dos enunciados e do resultado final utilizando um nome sorteado automaticamente.
- **Estrutura de Fluxograma:** Navegação fluida entre perguntas com base nas escolhas do jogador.
- **Múltiplas Afirmações:** Frases sorteadas aleatoriamente a partir das escolhas feitas para gerar um resumo final único.
- **Reinício Sem Recarregar:** Botão "Jogar Novamente" que restaura o estado do jogo e permite tentar novos caminhos instantaneamente.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica e acessível.
- **CSS3:** Estilização com variáveis customizadas (`:root`), Flexbox, fontes do Google Fonts (`Chakra Petch` e `Inter`) e transições visuais.
- **JavaScript ES6+:** Modularização nativa (`import`/`export`), manipulação do DOM, expressões regulares (`replace`) e lógica condicional.

---

## 📂 Estrutura de Arquivos

```text
MISSÃO-IA/
├── index.html        # Página principal da aplicação
├── style.css         # Estilos globais e controle de visibilidade
└── js/
    ├── aleatorio.js  # Módulo de sortear nomes e itens aleatórios
    ├── perguntas.js  # Módulo contendo os dados do quiz e o fluxograma
    └── script.js     # Módulo principal da lógica e controle do jogo