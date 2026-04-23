<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f6/INSS.svg/500px-INSS.svg.png" width="100" alt="Logo INSS"/>

# Meu INSS — Recriação Educacional

**Recriação do portal Meu INSS desenvolvida com HTML5 e CSS3 puro para fins de aprendizado.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)
![Licença](https://img.shields.io/badge/Uso-Educacional-green?style=for-the-badge)

</div>

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias](#-tecnologias)
- [Estrutura de Arquivos](#-estrutura-de-arquivos)
- [Como Executar](#-como-executar)
- [Responsividade](#-responsividade)
- [Correções Aplicadas](#-correções-aplicadas)
- [Autor](#-autor)

---

## 📌 Sobre o Projeto

Este projeto é uma **recriação educacional** do portal [Meu INSS](https://meu.inss.gov.br), desenvolvida com o objetivo de praticar e consolidar conhecimentos em **HTML5 semântico** e **CSS3**, incluindo técnicas de layout com `float`, `CSS Grid` e design responsivo com `@media queries`.

> ⚠️ **Aviso:** Este projeto não possui vínculo oficial com o INSS ou o Governo Federal. É estritamente educacional e não processa dados reais.

---

## ✅ Funcionalidades

- [x] Barra institucional GOV.BR
- [x] Cabeçalho com logo e botão de acesso
- [x] Grid de serviços principais (Agendamento, Portal, Consulta)
- [x] Seção de tipos de benefícios
- [x] Layout totalmente responsivo
- [ ] Seção de atendimento *(removida nesta versão)*
- [ ] Seção de notícias *(removida nesta versão)*
- [ ] Funcionalidade real de login

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura semântica da página |
| **CSS3** | Estilização, layout e responsividade |
| **CSS Float** | Layout do cabeçalho e barra de navegação |
| **CSS Grid** | Grid de cards e seção de atendimento |
| **Media Queries** | Adaptação para tablet e mobile |

---

## 📁 Estrutura de Arquivos

```
meu-inss-educacional/
│
├── NETOTRABALHO.HTML       # Estrutura principal da página
├── FOLHA-DE-ESTILO.CSS     # Estilos visuais e responsividade
└── README.md               # Documentação do projeto
```

---

## ▶️ Como Executar

**Pré-requisitos:** Nenhum — apenas um navegador moderno.

```bash
# 1. Clone ou baixe os arquivos do projeto
# 2. Certifique-se que os dois arquivos estão na mesma pasta
# 3. Abra o arquivo HTML no navegador

NETOTRABALHO.HTML   ← abrir este arquivo
FOLHA-DE-ESTILO.CSS ← deve estar na mesma pasta
```

> 💡 O logo do INSS é carregado via URL externa (Wikimedia Commons). Requer conexão com a internet.

---

## 📱 Responsividade

O layout se adapta a três breakpoints:

```
> 900px   →  Desktop   — duas colunas, grid completo
< 900px   →  Tablet    — colunas empilhadas, conteúdo centralizado  
< 680px   →  Mobile    — nav centralizado, fontes e logo reduzidos
```

---

## 🐛 Correções Aplicadas

| # | Problema | Arquivo | Solução |
|---|---|---|---|
| 1 | Tag `</main>` ausente — `<footer>` estava dentro do `<main>` | `NETOTRABALHO.HTML` | Tag `</main>` adicionada antes do `<footer>` |
| 2 | Links do `<nav>` apontando para seções inexistentes (`#atendimento`, `#noticias`) | `NETOTRABALHO.HTML` | Links redirecionados para `#servicos` e `#beneficios` |

---

## 👤 Autor

Desenvolvido para fins educacionais.

---

<div align="center">

*Este projeto foi criado exclusivamente para fins de estudo e aprendizado.*  
*Não possui qualquer vínculo com o INSS ou o Governo Federal Brasileiro.*

</div>
