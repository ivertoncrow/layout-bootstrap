# layout-bootstrap
Layouts Responsivos (Construção de Layouts e Templates Responsivos)

# 📱 Página Responsiva com Bootstrap Grid

Atividade prática desenvolvida para a disciplina de **Desenvolvimento Responsivo**  
Unidade 2 · Aula 4 — Layouts com Frameworks e Bibliotecas Front-End

---

## 📋 Sobre o projeto

Página web responsiva construída com **Bootstrap 5**, demonstrando o uso do sistema de grid, breakpoints e classes utilitárias para criar um layout adaptável a diferentes tamanhos de tela.

---

## 🎯 Objetivos

- Compreender o funcionamento do sistema de grid do Bootstrap 5
- Aplicar breakpoints para construir layouts responsivos
- Utilizar classes utilitárias de espaçamento, sombra e alinhamento
- Desenvolver uma interface organizada seguindo boas práticas de design responsivo

---

## 🖥️ Layout

| Dispositivo | Largura | Comportamento                      |
| ----------- | ------- | ---------------------------------- |
| Celular     | < 768px | `col-12` — colunas empilhadas      |
| Tablet      | ≥ 768px | `col-md-6` — 2 colunas por linha   |
| Desktop     | ≥ 992px | `col-lg-4` — 3 colunas lado a lado |

---

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- [Bootstrap 5.3.3](https://getbootstrap.com/) via CDN

---

## 📁 Estrutura do projeto

```
layout-bootstrap/
└── index.html
```

---

## ✅ Checklist da atividade

- [x] Bootstrap 5 vinculado via CDN
- [x] Estrutura com header, 3 colunas e footer
- [x] Classes de grid (`row`, `col-12`, `col-md-6`, `col-lg-4`)
- [x] Breakpoints responsivos implementados
- [x] Utilitários de espaçamento (`p-2`, `py-5`, `px-4`)
- [x] Sombras (`shadow-sm`) e bordas arredondadas (`rounded-4`)
- [x] Utilitários de background (`bg-light`)
- [x] Alinhamento centralizado (`text-center`)
- [x] Badges com classes do Bootstrap (`badge rounded-pill text-bg-*`)
- [x] Footer fixado no rodapé da página
- [x] Responsividade testada em diferentes tamanhos de tela

---

## 🚀 Como executar

1. Clone o repositório:

```bash
git clone https://github.com/ivertoncrow/layout-bootstrap.git
```

2. Abra o arquivo `index.html` no navegador.

> Não é necessário instalar nada — o Bootstrap é carregado via CDN.

---

## 📸 Preview

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8e728bd8-7093-448d-8c1a-01b99113e5e4" />

---

## 📚 Referências

- [Documentação Bootstrap 5](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Grid System](https://getbootstrap.com/docs/5.3/layout/grid/)
- [Bootstrap Utilities](https://getbootstrap.com/docs/5.3/utilities/spacing/)
