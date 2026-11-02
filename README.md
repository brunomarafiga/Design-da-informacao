# 📚 Redesign do SiBi UFPR — Protótipo de Alta Fidelidade

> Projeto desenvolvido para a disciplina de **Design da Informação** da Universidade Federal do Paraná (UFPR).

## 🔗 Demo

Acesse o protótipo publicado via GitHub Pages:  
👉 **[brunomarafiga.github.io/Design-da-informa-o](https://brunomarafiga.github.io/Design-da-informa-o/)**

---

## 📖 Sobre o Projeto

Este projeto consiste na **recriação (redesign)** de duas páginas do site do **Sistema de Bibliotecas da UFPR (SiBi)**, desenvolvido como trabalho prático da disciplina de **Design da Informação**.

O objetivo principal foi aplicar conceitos de design da informação, usabilidade e acessibilidade para propor uma nova interface que melhore a experiência do usuário em relação ao site original.

### Páginas recriadas

| Página | Descrição |
|--------|-----------|
| **Página Inicial** | Redesign completo da homepage do SiBi UFPR, com atalhos rápidos, notícias recentes, banner do aplicativo, recursos de pesquisa e navegação aprimorada. |
| **Página de Notícias** | Recriação da página de notícias com sistema de busca, filtros por categoria e ano, e carregamento dinâmico de posts a partir de dados JSON. |

---

## ✨ Funcionalidades

- 🌗 **Modo escuro/claro** — alternância de tema com persistência via `localStorage`
- 📱 **Design responsivo** — layout adaptável para dispositivos móveis e desktop
- 🍔 **Menu mobile (drawer)** — navegação lateral com submenus expansíveis
- 🔍 **Busca e filtros** — pesquisa por texto, filtragem por categoria e por ano na página de notícias
- 📰 **Carregamento dinâmico** — notícias carregadas a partir de arquivo JSON (`posts.json`)
- 🧭 **Mega menu** — navegação com dropdown organizado por localidade das bibliotecas
- ♿ **Acessibilidade** — atributos `aria-label`, semântica HTML e contraste adequado

---

## 🗂 Estrutura do Projeto

```
Design-da-informa-o/
├── index.html              # Página inicial (redesign)
├── sibihifi.css             # Estilos da página inicial
├── sibihifi.js              # Scripts da página inicial (tema, menu, submenus)
├── Noticias/
│   ├── noticias.html        # Página de notícias (redesign)
│   ├── style.css            # Estilos da página de notícias
│   ├── script.js            # Scripts de busca, filtros e renderização
│   └── posts.json           # Dados das notícias em formato JSON
├── imagens/
│   ├── página inicial antigo.jpeg       # Screenshot da página original
│   ├── pagina inicial.jpeg              # Screenshot do redesign (modo claro)
│   ├── pagina inicial novo escuro.jpeg  # Screenshot do redesign (modo escuro)
│   ├── Noticias original.jpeg           # Screenshot da página de notícias original
│   ├── Noticia novo.jpeg                # Screenshot do redesign de notícias (modo claro)
│   └── noticia novo modo escuro.jpeg    # Screenshot do redesign de notícias (modo escuro)
├── Teste de acessibilidade/
│   ├── bibliotecas.ufpr.br-11.21.2025.pdf      # Relatório de acessibilidade do site original
│   └── brunomarafiga.github.io-11.21.2025.pdf  # Relatório de acessibilidade do redesign
└── .github/workflows/
    └── jekyll-gh-pages.yml  # Deploy automático via GitHub Pages
```

---

## 🖼 Comparativo Visual

### Página Inicial

| Original | Redesign (Claro) | Redesign (Escuro) |
|----------|-------------------|--------------------|
| ![Original](imagens/página%20inicial%20antigo.jpeg) | ![Novo Claro](imagens/pagina%20inicial.jpeg) | ![Novo Escuro](imagens/pagina%20inicial%20novo%20escuro.jpeg) |

### Página de Notícias

| Original | Redesign (Claro) | Redesign (Escuro) |
|----------|-------------------|--------------------|
| ![Original](imagens/Noticias%20original.jpeg) | ![Novo Claro](imagens/Noticia%20novo.jpeg) | ![Novo Escuro](imagens/noticia%20novo%20modo%20escuro.jpeg) |

---

## 🛠 Tecnologias Utilizadas

- **HTML5** — estrutura semântica das páginas
- **CSS3** — estilização com variáveis CSS, media queries e modo escuro
- **JavaScript (Vanilla)** — interatividade, tema, filtros e renderização dinâmica
- **Font Awesome 6** — ícones
- **Google Fonts (Inter)** — tipografia
- **GitHub Pages** — hospedagem e deploy automático

---

## 🚀 Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/brunomarafiga/Design-da-informa-o.git
   ```
2. Abra o arquivo `index.html` no navegador, ou utilize uma extensão como **Live Server** no VS Code.

---

## 📋 Disciplina

| | |
|---|---|
| **Disciplina** | Design da Informação |
| **Instituição** | Universidade Federal do Paraná (UFPR) |
| **Aluno** | Bruno de Paula Marafiga |

---

## 📄 Licença

Projeto acadêmico sem fins comerciais. As marcas, logotipos e conteúdos do SiBi/UFPR são de propriedade da Universidade Federal do Paraná.

## Contexto do projeto

- **Categoria:** Design de interfaces
- **Temas e tecnologias:** HTML, CSS, JavaScript, acessibilidade e redesign do SiBi UFPR
- **Visibilidade:** Público
- **Repositório:** <https://github.com/brunomarafiga/Design-da-informacao>

Este README apresenta o objetivo, a organização e as instruções de uso do projeto. Consulte os arquivos e diretórios do repositório para detalhes de implementação e materiais complementares.
