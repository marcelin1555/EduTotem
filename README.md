# 🖥️ EduTotem — CEFE Jardim do Seridó

> Totem digital interativo para uso em tela de quiosque escolar.  
> Desenvolvido para o **Centro de Educação e Formação do Estado (CEFE) de Jardim do Seridó – RN**.

---

## 📸 Visão Geral

O **EduTotem** é uma aplicação web *single-file* (HTML + CSS + JS), projetada para rodar em telas de totem ou monitores de recepção escolar. Ele centraliza informações úteis para alunos, professores e visitantes da escola.

---

## ✨ Funcionalidades

| Módulo | Descrição |
|---|---|
| 🔐 **Login** | Acesso com matrícula e senha; modo administrador separado |
| 🏠 **Menu Principal** | Hub com acesso a todos os módulos |
| 🏫 **Salas** | Mapa de disponibilidade das salas em tempo real |
| 🍽️ **Cardápio** | Cardápio semanal da escola por dia da semana |
| 📅 **Eventos** | Calendário de eventos e avisos institucionais |
| 📚 **Biblioteca** | Catálogo de livros disponíveis para empréstimo |
| 🚌 **Transporte** | Horários e rotas de transporte escolar |
| ⚙️ **Admin** | Painel de gerenciamento de salas, cardápio e alunos |

---

## 🚀 Como usar

### Opção 1 — Abrir diretamente no navegador

Basta abrir o arquivo `index.html` em qualquer navegador moderno. Nenhuma instalação ou servidor necessário.

```bash
# Clone o repositório
git clone https://github.com/marcelin1555/EduTotem.git

# Abra o arquivo
cd edutotem
open index.html   # macOS
start index.html  # Windows
xdg-open index.html  # Linux
```

### Opção 2 — Servir localmente (recomendado para totem)

```bash
# Com Python 3
python3 -m http.server 8080

# Com Node.js (npx)
npx serve .
```

Acesse `http://localhost:8080` no navegador do totem.

---

## 🔑 Credenciais de Acesso (padrão)

> ⚠️ Altere as senhas antes de colocar em produção.

| Perfil | Usuário | Senha |
|---|---|---|
| Administrador | `admin` | `admin123` |
| Aluno (exemplo) | Matrícula cadastrada | Senha cadastrada |

---

## 🛠️ Tecnologias

- **HTML5 / CSS3 / JavaScript** — puro, sem frameworks
- **Google Fonts** — Sora + JetBrains Mono
- **LocalStorage** — persistência de dados no navegador
- Design responsivo para telas **fullscreen / quiosque**

---

## 📁 Estrutura do Projeto

```
edutotem/
├── index.html      # Aplicação completa (HTML + CSS + JS)
└── README.md       # Este arquivo
```

---

## 🖥️ Configuração para Modo Quiosque

Para usar em um totem real, recomenda-se abrir o Chrome em modo quiosque:

```bash
# Windows
chrome.exe --kiosk --no-first-run http://localhost:8080

# Linux
google-chrome --kiosk --no-first-run http://localhost:8080
```

---

## 📄 Licença

Este projeto foi desenvolvido para uso interno do **CEFE Jardim do Seridó**.  
Distribuição e modificação livres para fins educacionais.

---

*Feito com 💙 para a comunidade escolar de Jardim do Seridó – RN*
