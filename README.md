
# 🧠 Jogo da Memória - Emojis

Um jogo da memória simples e interativo desenvolvido com **HTML, CSS e JavaScript puro**, com o objetivo de treinar a lógica de programação, manipulação do DOM e efeitos visuais com transformações em 3D.

---

## 📸 Pré-visualização

<img width="1433" height="900" alt="image" src="https://github.com/user-attachments/assets/b3535820-1863-4b1d-a94e-a883be045b94" /> 
*(Substitua `preview.png` por um print do jogo)*

---

## 🚀 Funcionalidades

- Geração dinâmica do tabuleiro com cartas de emojis.
- Efeito de **flip (virada)** ao clicar nas cartas.
- Sistema de **comparação de pares** com feedback visual.
- Mensagem de **fim de jogo** ao acertar todos os pares.
- Botão de **reset** para reiniciar a partida.

---

## 🧩 Estrutura do Projeto

```
/
├── index.html          # Estrutura principal da página
├── assets/
│   ├── css/
│   │   ├── reset.css   # Reset de estilos
│   │   └── styles.css  # Estilização do jogo
│   └── scripts/
│       └── engine.js   # Lógica principal do jogo
└── README.md            # Documentação do projeto
```

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**
  - Estrutura semântica da página
  - Criação de elementos dinâmicos via JavaScript no contêiner `.game`

- **CSS3**
  - Estilização completa do layout com:
    - `flexbox` para organização responsiva
    - `linear-gradient` no plano de fundo
    - `transform: rotateY` e `backface-visibility: hidden` para o efeito 3D
  - Transições suaves com `transition`

- **JavaScript (Vanilla JS)**
  - Criação e embaralhamento do array de emojis
  - Inserção dinâmica dos elementos `.item` no DOM
  - Controle da lógica do jogo:
    - Abertura das cartas (`.boxOpen`)
    - Comparação de pares (`checkMatch()`)
    - Marcação de pares corretos (`.boxMatch`)
    - Reinício do jogo com `window.location.reload()`
  - Uso de `setTimeout` para delay entre abrir as cartas e verificar o par

---

## ⚙️ Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/jogo-da-memoria-emojis.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd jogo-da-memoria-emojis
   ```
3. Abra o arquivo `index.html` em seu navegador.

Não é necessário instalar dependências — o jogo funciona apenas com arquivos estáticos.

---

## 💡 Técnicas e Conceitos Abordados

- **Manipulação do DOM** com `document.createElement`, `appendChild` e alteração de classes
- **Eventos de clique** usando `onclick`
- **Estruturas de dados** como arrays para armazenar e embaralhar os emojis
- **Controle de estado do jogo** com o array `openCards`
- **Transições e animações CSS** com `transform`, `perspective` e `transition`
- **Validação de vitória** contando os elementos com a classe `.boxMatch`

---

## 📌 Melhorias Futuras

- Adicionar contador de movimentos ou tempo
- Criar um sistema de pontuação e ranking
- Implementar níveis de dificuldade (diferentes quantidades de cartas)
- Adicionar sons de acerto e erro
- Tornar o layout responsivo para telas menores

---

## 🧑‍💻 Autor

Desenvolvido por Fernando Antonio Azevedo como projeto prático de lógica de programação.




