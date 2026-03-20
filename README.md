<div align="center">

<img src="https://raw.githubusercontent.com/marcelin1555/EduTotem/main/assets/logo.png" width="120" alt="CEFE Logo" />

# ðŸ–¥ï¸ EduTotem

### Sistema Digital Interativo para Ambiente Escolar

**CEFE Â· Centro de Ensino Â· Jardim do SeridÃ³ â€” RN**

---

[![VersÃ£o](https://img.shields.io/badge/versÃ£o-1.0.0-22D3EE?style=for-the-badge&logo=github)](https://github.com/marcelin1555/EduTotem)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/marcelin1555/EduTotem)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/marcelin1555/EduTotem)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/marcelin1555/EduTotem)
[![LicenÃ§a](https://img.shields.io/badge/licenÃ§a-MIT-10B981?style=for-the-badge)](LICENSE)

---

> **EduTotem** Ã© um totem digital interativo desenvolvido para o **CEFE de Jardim do SeridÃ³/RN**, projetado para rodar em terminais touchscreen instalados em ambiente escolar. O sistema centraliza informaÃ§Ãµes para alunos e moderniza a gestÃ£o escolar â€” tudo em um Ãºnico arquivo HTML, funcionando 100% offline.

<br/>

![Preview EduTotem](https://raw.githubusercontent.com/marcelin1555/EduTotem/main/assets/preview.png)

</div>

---

## ðŸ“‹ Ãndice

- [âœ¨ Funcionalidades](#-funcionalidades)
- [ðŸ–¥ï¸ Telas do Sistema](#ï¸-telas-do-sistema)
- [ðŸš€ Como Usar](#-como-usar)
- [ðŸ”‘ Credenciais](#-credenciais)
- [ðŸ“Š ImportaÃ§Ã£o de Alunos](#-importaÃ§Ã£o-de-alunos)
- [ðŸ”„ SincronizaÃ§Ã£o](#-sincronizaÃ§Ã£o)
- [ðŸ§± Estrutura do Totem FÃ­sico](#-estrutura-do-totem-fÃ­sico)
- [ðŸ› ï¸ Tecnologias](#ï¸-tecnologias)
- [ðŸ—ºï¸ Roadmap](#ï¸-roadmap)
- [ðŸ“„ LicenÃ§a](#-licenÃ§a)

---

## âœ¨ Funcionalidades

<table>
  <tr>
    <td>ðŸ” <strong>Login Seguro</strong></td>
    <td>CartÃ£o NFC ou matrÃ­cula + senha com sessÃ£o por JWT</td>
  </tr>
  <tr>
    <td>ðŸ½ï¸ <strong>Sistema de AlmoÃ§o</strong></td>
    <td>ConfirmaÃ§Ã£o em tempo real com contador ao vivo via Socket.IO</td>
  </tr>
  <tr>
    <td>ðŸ“‹ <strong>CardÃ¡pio Semanal</strong></td>
    <td>VisualizaÃ§Ã£o e ediÃ§Ã£o completa por dia da semana</td>
  </tr>
  <tr>
    <td>ðŸ“¢ <strong>Avisos Escolares</strong></td>
    <td>Comunicados com prioridade alta, mÃ©dia e baixa</td>
  </tr>
  <tr>
    <td>ðŸ“š <strong>HorÃ¡rios de Aula</strong></td>
    <td>Grade por turma com badge <strong>AGORA</strong> em tempo real</td>
  </tr>
  <tr>
    <td>ðŸ« <strong>Mapa de Salas</strong></td>
    <td>Status visual: Livre ðŸŸ¢ Â· Ocupada ðŸ”´ Â· ManutenÃ§Ã£o ðŸŸ¡</td>
  </tr>
  <tr>
    <td>ðŸ‘¤ <strong>Perfil do Aluno</strong></td>
    <td>EdiÃ§Ã£o de foto, nome social, gÃªnero, e-mail e senha</td>
  </tr>
  <tr>
    <td>âš™ï¸ <strong>Painel Administrativo</strong></td>
    <td>GestÃ£o completa de alunos, turmas, cardÃ¡pio e salas</td>
  </tr>
  <tr>
    <td>ðŸ“Š <strong>ImportaÃ§Ã£o CSV/Excel</strong></td>
    <td>Cadastro em massa via <code>.xlsx</code>, <code>.xls</code>, <code>.csv</code> ou <code>.ods</code></td>
  </tr>
  <tr>
    <td>ðŸ‘¨â€ðŸ« <strong>Staff Escolar</strong></td>
    <td>Cadastro de professores, coordenadores e funcionÃ¡rios</td>
  </tr>
  <tr>
    <td>ðŸ”„ <strong>SincronizaÃ§Ã£o</strong></td>
    <td>Export/Import JSON entre dispositivos e Broadcast em tempo real</td>
  </tr>
  <tr>
    <td>â±ï¸ <strong>Logout por Inatividade</strong></td>
    <td>SessÃ£o encerrada automaticamente apÃ³s 60s sem interaÃ§Ã£o</td>
  </tr>
</table>

---

## ðŸ–¥ï¸ Telas do Sistema

O EduTotem conta com **17 telas** organizadas em dois portais:

### ðŸ‘¨â€ðŸŽ“ Portal do Aluno
```
Login â†’ Portal â†’ AlmoÃ§o â†’ CardÃ¡pio â†’ Avisos â†’ HorÃ¡rios â†’ Mapa de Salas â†’ Perfil
```

### âš™ï¸ Portal Administrativo
```
Admin Login â†’ Painel â†’ Alunos â†’ Importar CSV â†’ Staff â†’ Turmas â†’ CardÃ¡pio â†’ Salas â†’ SincronizaÃ§Ã£o
```

---

## ðŸš€ Como Usar

### â–¶ï¸ OpÃ§Ã£o 1 â€” Abrir direto no navegador (offline)

```bash
# Clone o repositÃ³rio
git clone https://github.com/marcelin1555/EduTotem.git
cd EduTotem

# Abra o arquivo
start index.html       # Windows
open index.html        # macOS
xdg-open index.html    # Linux
```

### ðŸŒ OpÃ§Ã£o 2 â€” Servir localmente (recomendado para totem)

```bash
# Com Python
python3 -m http.server 8080

# Com Node.js
npx serve .
```

Acesse `http://localhost:8080` no navegador do totem.

### ðŸ–¥ï¸ Modo Kiosk (totem real)

```bash
# Windows
chrome.exe --kiosk --disable-infobars --noerrdialogs http://localhost:8080

# Linux
google-chrome --kiosk --disable-infobars http://localhost:8080
```

---

## ðŸ”‘ Credenciais

> âš ï¸ **Altere as credenciais padrÃ£o antes de colocar em produÃ§Ã£o!**

No **primeiro acesso** ao painel admin, vÃ¡ em **Alterar Senha Admin** e defina suas prÃ³prias credenciais.

| Perfil | Como acessar |
|---|---|
| **Aluno** | Cadastre via painel admin ou importe por CSV/Excel |
| **Admin** | BotÃ£o "Painel Administrativo" na tela de login |

---

## ðŸ“Š ImportaÃ§Ã£o de Alunos

O sistema suporta importaÃ§Ã£o em massa pelos formatos:

| Formato | ExtensÃ£o |
|---|---|
| Excel Moderno | `.xlsx` |
| Excel Antigo | `.xls` |
| LibreOffice | `.ods` |
| Texto | `.csv` / `.txt` |

### Estrutura do arquivo

```csv
matricula,nome,senha,serie,turma,email,nascimento
2024001,JoÃ£o Silva,senha123,1Âº Ano,1Âº PropedÃªutico,joao@cefe.edu.br,10/05/2009
2024002,Maria Santos,senha456,2Âº Ano,2Âº Integral TÃ©cnico,maria@cefe.edu.br,22/08/2008
```

> O sistema reconhece automaticamente variaÃ§Ãµes de nomes de coluna (ex: `mat`, `ra`, `nome_completo`, `data_nascimento`, etc.)

---

## ðŸ”„ SincronizaÃ§Ã£o

Para sincronizar dados entre o computador e o totem:

1. No computador: **Admin â†’ SincronizaÃ§Ã£o â†’ Exportar Sistema** â†’ gera um `.json`
2. No totem: **Admin â†’ SincronizaÃ§Ã£o â†’ Importar Backup** â†’ seleciona o `.json`

Para sincronizaÃ§Ã£o automÃ¡tica entre abas/janelas do mesmo navegador, o sistema usa **BroadcastChannel API** nativa.

---

## ðŸ§± Estrutura do Totem FÃ­sico

```
â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
â”‚   â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”   â”‚  â† Gabinete ABS ou AcrÃ­lico
â”‚   â”‚             â”‚   â”‚
â”‚   â”‚  Touchscreenâ”‚   â”‚  â† Tela 21"â€“27" Full HD Capacitiva
â”‚   â”‚   21"â€“27"   â”‚   â”‚
â”‚   â”‚             â”‚   â”‚
â”‚   â”‚             â”‚   â”‚
â”‚   â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜   â”‚
â”‚   [  Leitor NFC  ]  â”‚  â† MÃ³dulo NFC frontal (ACR122U)
â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
         â•‘â•‘â•‘             â† Estrutura interna metÃ¡lica
    â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€        â† Base estÃ¡vel (fixaÃ§Ã£o ao solo)
```

**EspecificaÃ§Ãµes recomendadas:**

| Componente | MÃ­nimo | Recomendado |
|---|---|---|
| Tela | 21" FHD Touch | 24" IPS Industrial |
| CPU | Intel Celeron N4020 | Intel Core i3 |
| RAM | 4GB | 8GB |
| Armazenamento | SSD 64GB | SSD 120GB |
| SO | Windows 10 IoT | Windows 10 IoT LTSC |
| Leitor NFC | ACR122U USB | Embutido no gabinete |

**Custo estimado:**

| VersÃ£o | Custo |
|---|---|
| ProtÃ³tipo | R$ 1.160 â€“ R$ 1.930 |
| ProduÃ§Ã£o | R$ 2.900 â€“ R$ 5.500 |

---

## ðŸ› ï¸ Tecnologias

<div align="center">

| Camada | Tecnologia |
|---|---|
| Interface | HTML5 + CSS3 + JavaScript ES6+ |
| Tipografia | Space Grotesk + Plus Jakarta Sans + JetBrains Mono |
| Ãcones | SVG Inline (sem dependÃªncias externas) |
| Planilhas | SheetJS (xlsx) |
| Dados | localStorage (offline) |
| Tempo real (futuro) | Socket.IO + Node.js + SQLite |

</div>

### ðŸ“ Estrutura do Projeto

```
EduTotem/
â”œâ”€â”€ index.html          â† AplicaÃ§Ã£o completa (HTML + CSS + JS)
â”œâ”€â”€ README.md           â† Este arquivo
â””â”€â”€ .gitignore
```

> O sistema foi projetado como **single-file** â€” todo CSS, JavaScript e imagens estÃ£o embutidos no `index.html`, sem nenhuma dependÃªncia externa obrigatÃ³ria.

---

## ðŸ—ºï¸ Roadmap

- [x] **v1.0.0** â€” Sistema completo offline (atual)
  - Login NFC + matrÃ­cula/senha
  - Portal do aluno com 6 mÃ³dulos
  - Painel admin completo
  - ImportaÃ§Ã£o CSV/Excel
  - Staff e professores
  - SincronizaÃ§Ã£o manual

- [ ] **v1.1.0** â€” Backend online
  - Node.js + Express + SQLite
  - API REST completa
  - Socket.IO para tempo real
  - MÃºltiplos totens sincronizados

- [ ] **v1.2.0** â€” InteligÃªncia
  - GeraÃ§Ã£o automÃ¡tica de horÃ¡rios
  - DetecÃ§Ã£o de conflitos de professores
  - RelatÃ³rios de almoÃ§o (histÃ³rico, exportaÃ§Ã£o)
  - NotificaÃ§Ãµes push para alunos

- [ ] **v2.0.0** â€” ExpansÃ£o
  - Aplicativo mobile (iOS/Android)
  - Portal web responsivo
  - Reconhecimento facial
  - IntegraÃ§Ã£o com sistemas da SEEC-RN

---

## ðŸ“¸ Screenshots

> *Screenshots serÃ£o adicionados em breve.*

---

## ðŸ¤ Contribuindo

Este projeto foi desenvolvido para uso interno do **CEFE Jardim do SeridÃ³**.  
SugestÃµes e melhorias sÃ£o bem-vindas via [Issues](https://github.com/marcelin1555/EduTotem/issues).

```bash
# Fork o projeto
# Crie sua branch
git checkout -b feat/minha-funcionalidade

# Commit suas mudanÃ§as
git commit -m "feat: descriÃ§Ã£o da funcionalidade"

# Push para a branch
git push origin feat/minha-funcionalidade

# Abra um Pull Request
```

---

## ðŸ“„ LicenÃ§a

Este projeto estÃ¡ sob a licenÃ§a **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

Desenvolvido com ðŸ’™ para a comunidade escolar de **Jardim do SeridÃ³ â€“ RN**

---

<div align="center">

**[â¬† Voltar ao topo](#ï¸-edutotem)**

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-marcelin1555-181717?style=flat-square&logo=github)](https://github.com/marcelin1555)
[![CEFE](https://img.shields.io/badge/Escola-CEFE_Jardim_do_SeridÃ³-22D3EE?style=flat-square)](https://github.com/marcelin1555/EduTotem)

</div>
