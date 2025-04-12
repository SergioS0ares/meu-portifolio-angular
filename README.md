# 🚀 Meu Portfólio Angular

Este é um projeto prático de portfólio desenvolvido com **Angular**, com o objetivo de aplicar na prática os principais conceitos aprendidos durante os estudos no repositório [Aprendizado-Angular](https://github.com/SergioS0ares/Aprendizado-angular).

> 📡 Acesse online: [Clique aqui para ver o portfólio publicado](https://sergios0ares.github.io/meu-portifolio-angular/browser)

---

## 📂 Estrutura

Este projeto foi construído com os seguintes recursos do Angular:

- Componentização (modularização por seção)
- Estilização com SCSS customizado
- Interfaces e Enum para tipagem segura
- Organização em módulos por domínio (`header`, `projects`, `knowledge`, etc.)
- Testes unitários iniciais com Jasmine/Karma
- Deploy automático com GitHub Pages

---

## 💡 Objetivo

Criar um portfólio interativo e de fácil manutenção que demonstre conhecimento técnico, organização de código e boas práticas com Angular moderno.

---

## 🚀 Como rodar localmente

```bash
git clone https://github.com/SergioS0ares/meu-portifolio-angular.git
cd meu-portifolio-angular/Portifolio/portifolio
npm install
ng serve
```

Abra no navegador: [http://localhost:4200](http://localhost:4200)

---

## 📦 Deploy com GitHub Pages

Este projeto utiliza a biblioteca `angular-cli-ghpages` para publicação contínua. Veja abaixo o passo a passo:

### 1. Instalar o pacote de deploy

```bash
ng add angular-cli-ghpages
```

### 2. Realizar o build de produção e deploy

```bash
ng deploy --base-href=/meu-portifolio-angular/browser/
```

> O valor de `--base-href` deve seguir o formato `/nome-do-repo/browser/` se você estiver hospedando direto em GitHub Pages.

### 3. Acessar o link publicado

Se tudo estiver certo, acesse:

```
https://seu-usuario.github.io/seu-repositorio/browser/
```

No caso deste projeto:

👉 [https://sergios0ares.github.io/meu-portifolio-angular/browser](https://sergios0ares.github.io/meu-portifolio-angular/browser)

---

## 💠 Atualizações futuras

Sempre que atualizar o código e quiser atualizar a versão online:

```bash
ng deploy --base-href=/meu-portifolio-angular/browser/
```

---

## 📜 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais detalhes.

