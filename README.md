# 🔐 Segurança Digital — Gerador de Senhas

Projeto inspirado na Unidade 2 da trilha **“Segurança digital: utilizando matemática para programar senhas seguras”**, da Start by Alura.

## 👨‍💻 Autor

**Arthur Vinicius Thomé**

## 🎯 Objetivo

Criar uma página web capaz de gerar senhas aleatórias e analisar sua força com base no tamanho e na quantidade de possibilidades de caracteres.

## ⚙️ Recursos

- Geração automática de senhas.
- Controle do número de caracteres.
- Letras maiúsculas.
- Letras minúsculas.
- Números.
- Símbolos.
- Indicador visual de força.
- Estimativa qualitativa do tempo necessário para descobrir a senha.
- Layout responsivo.

## 🧮 Matemática utilizada

O projeto utiliza a ideia de **entropia** para representar a quantidade de informação de uma senha:

`entropia = comprimento × log2(tamanho do conjunto de caracteres)`

Quanto maior o número de caracteres e maior a variedade de símbolos possíveis, maior é o número de combinações que precisam ser testadas.

## ▶️ Como executar

Não é necessário instalar nenhuma biblioteca.

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Personalize a senha usando os controles.

## 📁 Estrutura

```text
seguranca-digital-alura/
├── index.html
├── style.css
├── script.js
└── README.md
```

## 📚 Tecnologias

- HTML5
- CSS3
- JavaScript
