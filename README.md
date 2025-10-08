# JS Game
Um jogo simples de adivinhação de número secreto, desenvolvido para praticar lógica de programação e manipulação do DOM.
## 📁 Estrutura do projeto
```
└── git&github
    ├── img
    │   ├── JS Game_files
    │   │   ├── app.js
    │   │   └── style.css
    │   ├── bg.png
    │   ├── code.png
    │   ├── ia.png
    │   ├── JS Game.html
    │   └── Ruido.png
    ├── app.js
    ├── index.html
    └── style.css
```
## 🚀 Tecnologias
- HTML5
- CSS3
- JavaScript (Vanilla)
## ✨ Funcionalidades
- Gera um número aleatório para ser adivinhado pelo usuário
- Valida tentativas e informa se o palpite é maior ou menor
- Mostra feedback das tentativas
## 🧠 Como funciona (resumo)
- Ao iniciar, o sistema escolhe um **número secreto** (normalmente com `Math.random()`).
- O usuário faz **tentativas** informando números.
- O app retorna **dicas**: *maior* ou *menor* que o número secreto.
- Quando o número é descoberto, exibe **mensagem de sucesso** e opção de **reiniciar**.
## ▶️ Como executar

### Local (abrindo o arquivo)
1. Baixe/clonar este repositório.
2. Abra `git&github/index.html` no navegador.

### (Opcional) Servidor local
Para evitar problemas de CORS, você pode rodar um servidor simples:
```bash
# Python 3
python -m http.server 5500
# depois acesse: http://localhost:5500/git&github/index.html
```

## 🧪 Testes (se aplicável)
Se houver testes automatizados, execute conforme o gerenciador de scripts do projeto (por exemplo):
```bash
npm test
```

## 📦 Build (se aplicável)
Se existir etapa de build, utilize:
```bash
npm run build
```

## 🗂️ Assets estáticos
Se o projeto tiver imagens, áudios ou fontes, eles ficam organizados nas pastas correspondentes.

## 🛠️ Melhorias sugeridas
- Exibir número de tentativas e tempo decorrido.
- Modo *hard* com limites dinâmicos e pontuação.
- Acessibilidade (leitura de tela, foco, contraste).
- Internacionalização (pt-BR / en-US).
- Deploy no GitHub Pages, Vercel ou Netlify.

## 📄 Licença
Este projeto é distribuído sob a licença MIT. Sinta-se à vontade para usar e melhorar.

---


