## 🍔 Menu Mobile & FAQ Accordion Interativo

✨ Projeto front-end com **menu hamburger responsivo** e **FAQ Accordion animado**, feito com **HTML, CSS e JavaScript puro**.

---

## 📸 Preview
![alt text](./images/preview.png)
🔹 Menu mobile com botão hamburger  
🔹 Accordion de perguntas frequentes com ícones dinâmicos (+ / −)

---

## 🚀 Funcionalidades

✔️ Menu mobile responsivo  
✔️ Botão hamburger animado  
✔️ FAQ Accordion interativo  
✔️ Apenas um item do FAQ aberto por vez  
✔️ Ícones alternam automaticamente  
✔️ Código limpo e organizado  
✔️ JavaScript sem bibliotecas externas  

---

## 🛠️ Tecnologias Utilizadas

🔸 **HTML5**  
🔸 **CSS3**  
🔸 **JavaScript (Vanilla JS)**  
🔸 **Font Awesome** (ícones)

---

## 📂 Estrutura do Projeto
├── 📄 index.html

├── 📄 style.css

├── 📄 script.js

└── 📄 README.md

---

## 🍔 Menu Mobile (Hamburger)

📱 Ao clicar no botão hamburger:
- O menu mobile aparece/desaparece
- A classe `active` é adicionada/removida dinamicamente

✨ Ideal para layouts **responsivos e modernos**

---

## ❓ FAQ Accordion

📌 Comportamento:
- Clique no título da pergunta
- O conteúdo abre ou fecha
- O ícone muda de **➕ para ➖**
- Ao abrir um item, os outros se fecham automaticamente

🎯 Experiência limpa e intuitiva para o usuário

---

## 🧠 Lógica JavaScript

## 🧠 JavaScript — Explicação do Código

### 📌 O que este código faz?
Este script utiliza **JavaScript puro (Vanilla JS)** para adicionar interatividade à página, criando:
- Um **FAQ no formato accordion** (abre e fecha perguntas)
- Um **menu mobile responsivo** com botão hamburguer  

Toda a lógica funciona através de **eventos**, **seleção de elementos do DOM** e **manipulação dinâmica de classes CSS**.

---

### 🛠️ Conceitos e Recursos Utilizados

🔹 **`addEventListener`**  
Usado para capturar ações do usuário, como cliques e o carregamento da página.  
O evento `DOMContentLoaded` garante que o código só seja executado após o HTML estar totalmente carregado.

🔹 **`querySelector`**  
Seleciona elementos do HTML usando seletores CSS, permitindo acessar containers, botões e menus de forma simples e eficiente.

🔹 **`closest()`**  
Identifica o elemento pai mais próximo com base em um seletor.  
Isso garante que o clique funcione corretamente mesmo quando ocorre em ícones ou textos internos.

🔹 **`classList.toggle()`**  
Adiciona ou remove classes CSS dinamicamente, permitindo alternar estados visuais como:
- Abrir e fechar o conteúdo do FAQ
- Alternar ícones de **+** e **−**
- Mostrar ou esconder o menu mobile

🔹 **Manipulação dinâmica de classes**  
O JavaScript não altera o layout diretamente.  
Ele apenas controla classes, enquanto o **CSS define a aparência, animações e transições**.

---

### 🔄 Lógica do FAQ Accordion
Ao clicar em uma pergunta:
- O conteúdo correspondente é exibido
- Os demais conteúdos são fechados automaticamente
- Os ícones são atualizados para refletir o estado aberto ou fechado

Esse comportamento garante uma interface organizada e intuitiva.

---

### 📱 Menu Mobile
O menu mobile é ativado ao clicar no botão hamburguer.  
A classe `active` é adicionada ou removida, controlando a exibição do menu de forma simples e eficiente.

---

### ✅ Resumo Final
📎 Este código demonstra o uso prático de JavaScript para:
- Trabalhar com eventos
- Manipular o DOM
- Controlar estados visuais com classes CSS
- Criar interfaces interativas sem bibliotecas externas

🚀 **Solução leve, organizada e ideal para projetos Front-End.**
---

## ▶️ Como Usar

1️⃣ Clone o repositório  
```bash
git clone https://github.com/Nataly868/growth-landing-page

2️⃣ Abra o arquivo
index.html

3️⃣ Pronto! 🎉
Use em qualquer projeto web

