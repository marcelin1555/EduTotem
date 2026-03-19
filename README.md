<div align="center">


> Totem digital interativo para uso em tela de quiosque escolar.  
> Desenvolvido para o **Centro de Educacional Felinto Elisio (CEFE) de Jardim do Seridó – RN**.
=======
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgi-TzRzeQBqxRq0cbufWKFmmyEzS7DBLZd-NQk_Gk1Ri1kd6BngHB7z9CgcZH5S6hVMmr9NCFxqpuxmfwilH18LVQH5g1i11uoc3MvbYlwtvqqONqRhCcHbmkSlxZHoZUqkH-xrYzOz3I/s320/S%25C3%258DMBOLO+DO+CEFE.+SEM+PLANO+DE+FUNDO.png" width="120" alt="CEFE Logo" />

# 🖥️ EduTotem

### Sistema Digital Interativo para Ambiente Escolar

**CEFE · Centro Educacional Felinto elsio · Jardim do Seridó — RN**
>>>>>>> b6f3cf9 (feat: EduTotem v1.0.0 - sistema completo + README profissional)

---

[![Versão](https://img.shields.io/badge/versão-1.0.0-22D3EE?style=for-the-badge&logo=github)](https://github.com/marcelin1555/EduTotem)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/marcelin1555/EduTotem)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/marcelin1555/EduTotem)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/marcelin1555/EduTotem)
[![Licença](https://img.shields.io/badge/licença-MIT-10B981?style=for-the-badge)](LICENSE)

---

> **EduTotem** é um totem digital interativo desenvolvido para o **CEFE de Jardim do Seridó/RN**, projetado para rodar em terminais touchscreen instalados em ambiente escolar. O sistema centraliza informações para alunos e moderniza a gestão escolar — tudo em um único arquivo HTML, funcionando 100% offline.

<br/>

![Preview EduTotem](https://raw.githubusercontent.com/marcelin1555/EduTotem/main/assets/preview.png)

</div>

---

## 📋 Índice

- [✨ Funcionalidades](#-funcionalidades)
- [🖥️ Telas do Sistema](#️-telas-do-sistema)
- [🚀 Como Usar](#-como-usar)
- [🔑 Credenciais](#-credenciais)
- [📊 Importação de Alunos](#-importação-de-alunos)
- [🔄 Sincronização](#-sincronização)
- [🧱 Estrutura do Totem Físico](#-estrutura-do-totem-físico)
- [🛠️ Tecnologias](#️-tecnologias)
- [🗺️ Roadmap](#️-roadmap)
- [📄 Licença](#-licença)

---

## ✨ Funcionalidades

<table>
  <tr>
    <td>🔐 <strong>Login Seguro</strong></td>
    <td>Cartão NFC ou matrícula + senha com sessão por JWT</td>
  </tr>
  <tr>
    <td>🍽️ <strong>Sistema de Almoço</strong></td>
    <td>Confirmação em tempo real com contador ao vivo via Socket.IO</td>
  </tr>
  <tr>
    <td>📋 <strong>Cardápio Semanal</strong></td>
    <td>Visualização e edição completa por dia da semana</td>
  </tr>
  <tr>
    <td>📢 <strong>Avisos Escolares</strong></td>
    <td>Comunicados com prioridade alta, média e baixa</td>
  </tr>
  <tr>
    <td>📚 <strong>Horários de Aula</strong></td>
    <td>Grade por turma com badge <strong>AGORA</strong> em tempo real</td>
  </tr>
  <tr>
    <td>🏫 <strong>Mapa de Salas</strong></td>
    <td>Status visual: Livre 🟢 · Ocupada 🔴 · Manutenção 🟡</td>
  </tr>
  <tr>
    <td>👤 <strong>Perfil do Aluno</strong></td>
    <td>Edição de foto, nome social, gênero, e-mail e senha</td>
  </tr>
  <tr>
    <td>⚙️ <strong>Painel Administrativo</strong></td>
    <td>Gestão completa de alunos, turmas, cardápio e salas</td>
  </tr>
  <tr>
    <td>📊 <strong>Importação CSV/Excel</strong></td>
    <td>Cadastro em massa via <code>.xlsx</code>, <code>.xls</code>, <code>.csv</code> ou <code>.ods</code></td>
  </tr>
  <tr>
    <td>👨‍🏫 <strong>Staff Escolar</strong></td>
    <td>Cadastro de professores, coordenadores e funcionários</td>
  </tr>
  <tr>
    <td>🔄 <strong>Sincronização</strong></td>
    <td>Export/Import JSON entre dispositivos e Broadcast em tempo real</td>
  </tr>
  <tr>
    <td>⏱️ <strong>Logout por Inatividade</strong></td>
    <td>Sessão encerrada automaticamente após 60s sem interação</td>
  </tr>
</table>

---

## 🖥️ Telas do Sistema

O EduTotem conta com **17 telas** organizadas em dois portais:

### 👨‍🎓 Portal do Aluno
```
Login → Portal → Almoço → Cardápio → Avisos → Horários → Mapa de Salas → Perfil
```

### ⚙️ Portal Administrativo
```
Admin Login → Painel → Alunos → Importar CSV → Staff → Turmas → Cardápio → Salas → Sincronização
```

---

## 🚀 Como Usar

### ▶️ Opção 1 — Abrir direto no navegador (offline)

```bash
# Clone o repositório
git clone https://github.com/marcelin1555/EduTotem.git
<<<<<<< HEAD
=======
cd EduTotem
>>>>>>> b6f3cf9 (feat: EduTotem v1.0.0 - sistema completo + README profissional)

# Abra o arquivo
start index.html       # Windows
open index.html        # macOS
xdg-open index.html    # Linux
```

### 🌐 Opção 2 — Servir localmente (recomendado para totem)

```bash
# Com Python
python3 -m http.server 8080

# Com Node.js
npx serve .
```

Acesse `http://localhost:8080` no navegador do totem.

### 🖥️ Modo Kiosk (totem real)

```bash
# Windows
chrome.exe --kiosk --disable-infobars --noerrdialogs http://localhost:8080

# Linux
google-chrome --kiosk --disable-infobars http://localhost:8080
```

---

## 🔑 Credenciais

> ⚠️ **Altere as credenciais padrão antes de colocar em produção!**

No **primeiro acesso** ao painel admin, vá em **Alterar Senha Admin** e defina suas próprias credenciais.

| Perfil | Como acessar |
|---|---|
| **Aluno** | Cadastre via painel admin ou importe por CSV/Excel |
| **Admin** | Botão "Painel Administrativo" na tela de login |

---

## 📊 Importação de Alunos

O sistema suporta importação em massa pelos formatos:

| Formato | Extensão |
|---|---|
| Excel Moderno | `.xlsx` |
| Excel Antigo | `.xls` |
| LibreOffice | `.ods` |
| Texto | `.csv` / `.txt` |

### Estrutura do arquivo

```csv
matricula,nome,senha,serie,turma,email,nascimento
2024001,João Silva,senha123,1º Ano,1º Propedêutico,joao@cefe.edu.br,10/05/2009
2024002,Maria Santos,senha456,2º Ano,2º Integral Técnico,maria@cefe.edu.br,22/08/2008
```

> O sistema reconhece automaticamente variações de nomes de coluna (ex: `mat`, `ra`, `nome_completo`, `data_nascimento`, etc.)

---

## 🔄 Sincronização

Para sincronizar dados entre o computador e o totem:

1. No computador: **Admin → Sincronização → Exportar Sistema** → gera um `.json`
2. No totem: **Admin → Sincronização → Importar Backup** → seleciona o `.json`

Para sincronização automática entre abas/janelas do mesmo navegador, o sistema usa **BroadcastChannel API** nativa.

---

## 🧱 Estrutura do Totem Físico

```
┌─────────────────────┐
│   ┌─────────────┐   │  ← Gabinete ABS ou Acrílico
│   │             │   │
│   │  Touchscreen│   │  ← Tela 21"–27" Full HD Capacitiva
│   │   21"–27"   │   │
│   │             │   │
│   │             │   │
│   └─────────────┘   │
│   [  Leitor NFC  ]  │  ← Módulo NFC frontal (ACR122U)
└─────────────────────┘
         ║║║             ← Estrutura interna metálica
    ─────────────        ← Base estável (fixação ao solo)
```

**Especificações recomendadas:**

| Componente | Mínimo | Recomendado |
|---|---|---|
| Tela | 21" FHD Touch | 24" IPS Industrial |
| CPU | Intel Celeron N4020 | Intel Core i3 |
| RAM | 4GB | 8GB |
| Armazenamento | SSD 64GB | SSD 120GB |
| SO | Windows 10 IoT | Windows 10 IoT LTSC |
| Leitor NFC | ACR122U USB | Embutido no gabinete |

**Custo estimado:**

| Versão | Custo |
|---|---|
| Protótipo | R$ 1.160 – R$ 1.930 |
| Produção | R$ 2.900 – R$ 5.500 |

---

## 🛠️ Tecnologias

<div align="center">

| Camada | Tecnologia |
|---|---|
| Interface | HTML5 + CSS3 + JavaScript ES6+ |
| Tipografia | Space Grotesk + Plus Jakarta Sans + JetBrains Mono |
| Ícones | SVG Inline (sem dependências externas) |
| Planilhas | SheetJS (xlsx) |
| Dados | localStorage (offline) |
| Tempo real (futuro) | Socket.IO + Node.js + SQLite |

</div>

### 📁 Estrutura do Projeto

```
EduTotem/
├── index.html          ← Aplicação completa (HTML + CSS + JS)
├── README.md           ← Este arquivo
└── .gitignore
```

> O sistema foi projetado como **single-file** — todo CSS, JavaScript e imagens estão embutidos no `index.html`, sem nenhuma dependência externa obrigatória.

---

## 🗺️ Roadmap

- [x] **v1.0.0** — Sistema completo offline (atual)
  - Login NFC + matrícula/senha
  - Portal do aluno com 6 módulos
  - Painel admin completo
  - Importação CSV/Excel
  - Staff e professores
  - Sincronização manual

- [ ] **v1.1.0** — Backend online
  - Node.js + Express + SQLite
  - API REST completa
  - Socket.IO para tempo real
  - Múltiplos totens sincronizados

- [ ] **v1.2.0** — Inteligência
  - Geração automática de horários
  - Detecção de conflitos de professores
  - Relatórios de almoço (histórico, exportação)
  - Notificações push para alunos

- [ ] **v2.0.0** — Expansão
  - Aplicativo mobile (iOS/Android)
  - Portal web responsivo
  - Reconhecimento facial
  - Integração com sistemas da SEEC-RN

---

## 📸 Screenshots

> *Screenshots serão adicionados em breve.*

---

## 🤝 Contribuindo

Este projeto foi desenvolvido para uso interno do **CEFE Jardim do Seridó**.  
Sugestões e melhorias são bem-vindas via [Issues](https://github.com/marcelin1555/EduTotem/issues).

```bash
# Fork o projeto
# Crie sua branch
git checkout -b feat/minha-funcionalidade

# Commit suas mudanças
git commit -m "feat: descrição da funcionalidade"

# Push para a branch
git push origin feat/minha-funcionalidade

# Abra um Pull Request
```

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

Desenvolvido com 💙 para a comunidade escolar de **Jardim do Seridó – RN**

---

<div align="center">

**[⬆ Voltar ao topo](#️-edutotem)**

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-marcelin1555-181717?style=flat-square&logo=github)](https://github.com/marcelin1555)
[![CEFE](https://img.shields.io/badge/Escola-CEFE_Jardim_do_Seridó-22D3EE?style=flat-square)](https://github.com/marcelin1555/EduTotem)

</div>
