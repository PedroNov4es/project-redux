<h1 align="center">Project Redux</h1>

## 📝 Descrição
 
 Este projeto foi feito no curso da Udemy de React onde foi apresentado o Redux como um gerenciador de estados globais. O projeto tem como funcionalidade apresentar as boas práticas e    as vantagens de se utilizar Redux nos projetos. Foi utilizado um programa de Login pra demonstrar o uso dele.
 
---

## 🛠 Tecnologias
- Redux
- React
- Vite
---

## 📂 Estrutura do Projeto
```bash
/public
  vite.svg
/src
  /components/header
    header.module.css
    index.jsx
  /pages
    /Home
      home.module.css
      index.jsx
    /Login
      index.jsx
      login.module.css
    /addres
      address.module.css
      index.jsx
  /redux
    /user
      saga.js
      slice.js
    root-reducer.js
    sagas.js
    store.js
  App.jsx
  index.css
  main.jsx
.gitignore
README.md
index.html
package-lock.json
package.json
vite.config.js
```
---

## 🚀 Como Usar

Primeiro, faça o Login, não é necessário um cadastro , apenas preencha os campos com as informações solicitadas, podem ser ficticias. Após isso o programa irá te direcionar a uma tela chamada "Painel", onde você pode Buscar usuários(que são buscados de JSONPlaceholder) e criar um endereço clicando em "Meus endereços" e sendo direcionado para a página de endereços. Preencha o nome e o número do endereço e após voltar a página inicial o seu endereço atual será exibido juntamente com a opção de deleta-lo.

---
Acesse: https://project-redux-five.vercel.app/
