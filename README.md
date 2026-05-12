# 🦆 Minha Aventura em Brusque!

Jogo educativo para crianças de 5 anos sobre a cultura de Brusque (SC).

## 📁 Estrutura do Projeto

```
minha-aventura-brusque/
├── index.html        ← Jogo completo (HTML + CSS + JS em um arquivo)
└── README.md         ← Este arquivo
```

## 🚀 Como Rodar

Basta abrir o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge).
Não precisa de servidor, instalação ou internet (exceto para carregar as fontes do Google).

## 🎮 Funcionalidades

- Tela inicial com mascote animado
- Coleta de dados opcional (nome, idade, escola)
- 15 perguntas sobre Brusque embaralhadas a cada jogo
- Áudio nas perguntas (leitura automática por voz)
- Feedback visual (verde = correto, vermelho = errado)
- Sistema de estrelas e confetes no final
- Totalmente responsivo (tablet e celular)

## ✏️ Como Editar as Perguntas

No arquivo `index.html`, procure o trecho:
```
const TODAS_PERGUNTAS = [...]
```

Cada pergunta tem o formato:
```js
{
  id: 1,
  texto: "TEXTO DA PERGUNTA",
  emoji: "🌿",
  opcoes: [
    { texto: "OPÇÃO A", emoji: "🐒", correta: false },
    { texto: "OPÇÃO B", emoji: "🦫", correta: true },  // ← correta: true = resposta certa
  ]
}
```



## 👥 Projeto

Parceria UNIFEBE × Prefeitura Municipal de Brusque
Curricularização 2026 — Curso de Sistemas de Informação
