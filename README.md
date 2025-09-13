🧠 Jogo da Memória - Emojis

Um jogo da memória simples e interativo desenvolvido com HTML, CSS e JavaScript puro, com o objetivo de treinar a lógica de programação, manipulação do DOM e efeitos visuais com transformações em 3D.

📸 Pré-visualização

<img width="1433" height="900" alt="image" src="https://github.com/user-attachments/assets/b3535820-1863-4b1d-a94e-a883be045b94" />

🚀 Funcionalidades

Geração dinâmica do tabuleiro com cartas de emojis.

Efeito de flip (virada) ao clicar nas cartas.

Sistema de comparação de pares com feedback visual.

Mensagem de fim de jogo ao acertar todos os pares.

Botão de reset para reiniciar a partida.

🧩 Estrutura do Projeto
/
├── index.html          # Estrutura principal da página
├── assets/
│   ├── css/
│   │   ├── reset.css   # Reset de estilos
│   │   └── styles.css  # Estilização do jogo
│   └── scripts/
│       └── engine.js   # Lógica principal do jogo
└── README.md            # Documentação do projeto

🛠️ Tecnologias Utilizadas

HTML5

Estrutura semântica da página.

Criação de elementos dinâmicos via JavaScript no conteiner .game.

CSS3

Estilização completa do layout, com destaque para:

flexbox para organização responsiva dos elementos.

linear-gradient para o plano de fundo com transições suaves de cores

styles

.

transform: rotateY e backface-visibility: hidden para criar o efeito de virada 3D das cartas

styles

.

Transições suaves com transition para melhorar a experiência do usuário.

JavaScript (Vanilla JS)

Criação e embaralhamento do array de emojis

engine

.

Inserção dinâmica dos elementos .item no DOM.

Controle da lógica do jogo:

Abertura das cartas (.boxOpen).

Comparação de pares selecionados (checkMatch()).

Marcação de pares corretos (.boxMatch).

Reinício do jogo com window.location.reload().

Uso de setTimeout para criar um pequeno delay entre abrir as cartas e verificar se formam um par.

⚙️ Como Executar

Clone este repositório:

git clone https://github.com/seu-usuario/jogo-da-memoria-emojis.git


Acesse a pasta do projeto:

cd jogo-da-memoria-emojis


Abra o arquivo index.html em seu navegador.

Não é necessário instalar dependências — o jogo funciona apenas com arquivos estáticos.

💡 Técnicas e Conceitos Abordados

Manipulação do DOM
Criação e inserção de elementos HTML de forma programática usando document.createElement e appendChild.

Eventos de clique
Uso de onclick em cada carta para controlar a interação do usuário e a lógica do jogo.

Estruturas de dados

Array de emojis com elementos duplicados.

Uso de Array.sort com Math.random() para embaralhar os elementos.

Controle de estado do jogo

Armazenamento das cartas abertas no array openCards.

Reset automático do array após a comparação de duas cartas.

Transições e animações CSS

Uso de transform-style: preserve-3d e perspective para efeito tridimensional.

Alteração de classes (.boxOpen e .boxMatch) para aplicar as animações.

Validação de vitória

Contagem de elementos com a classe .boxMatch para verificar quando o jogador encontrou todos os pares e exibir um alert.

📌 Melhorias Futuras (Sugestões)

Adicionar contador de movimentos ou tempo.

Criar um sistema de pontuação e ranking.

Implementar níveis de dificuldade (diferentes quantidades de cartas).

Adicionar sons de acerto e erro.

Tornar o layout responsivo para telas menores.

🧑‍💻 Autor

Desenvolvido por Fernando Antonio Azevedo como projeto prático de lógica de programação.




