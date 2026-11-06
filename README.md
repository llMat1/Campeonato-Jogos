# 🎮 Campeonato de Jogos Digitais - IFCE Maranguape

> Página web desenvolvida como parte da atividade acadêmica da disciplina de **Web Development I** (Flexbox) no Instituto Federal do Ceará (IFCE) - Campus Maranguape.

---

## 👥 Autores

* **Matheus Figueredo**
* **Andresson Viana**

---

## 📋 Sobre o Projeto

O **Campeonato de Jogos Digitais** é uma página web temática de divulgação voltada para o público estudantil. O objetivo principal do projeto é aplicar os conceitos modernos de **CSS Flexbox** para estruturação, alinhamento e responsividade de layouts, englobando seções informativas, listagem de modalidades, tabela de programação e formulários de contato.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando exclusivamente tecnologias nativas, sem o uso de frameworks ou bibliotecas externas:

* **HTML5** (Tags semânticas)
* **CSS3** (Flexbox, Box Model, Posicionamento Relativo, Absoluto e Fixo)
* **Git e GitHub** (Controle de versão e hospedagem via GitHub Pages)

---

## 📐 Estrutura do Flexbox e Requisitos Aplicados

Conforme os requisitos da atividade, a página foi dividida em cinco partes principais, aplicando as seguintes propriedades:

1. **Cabeçalho e Menu (`display: flex`):**
   * Organização horizontal dos links com `flex-direction: row`.
   * Distribuição uniforme com `justify-content: space-evenly`.
   * Alinhamento vertical com `align-items: center` e efeito de interatividade `:hover`.
2. **Seção de Apresentação:**
   * Texto e imagem posicionados lado a lado utilizando Flexbox (`flex-direction: row` e `gap: 20px`).
3. **Cards de Destaque (Modalidades):**
   * Contêiner flexível com `flex-wrap: wrap` para garantir a quebra automática de linha em telas menores.
   * Centralização horizontal com `justify-content: center` e espaçamento com `gap`.
   * Uso combinatório de `position: relative` no card e `position: absolute` para fixar a etiqueta de **"DESTAQUE"** no canto superior direito.
4. **Programação:**
   * Faixa de informações organizada com blocos flexíveis e alinhados via `space-between`.
   * Tabela estilizada com bordas personalizadas e espaçamento interno.
5. **Rodapé e Botão "Voltar ao topo":**
   * Elementos do rodapé centralizados em coluna (`flex-direction: column`).
   * Botão flutuante fixado na tela utilizando `position: fixed`.

---

## 📁 Estrutura de Arquivos

```text
Campeonato-Jogos/
├── index.html       # Arquivo principal com a estrutura semântica
├── style.css        # Folha de estilos contendo as regras de Flexbox e design
└── img/             # Pasta de recursos visuais
    ├── Tela.jpeg
    ├── FreeFire.jpeg
    ├── CSGO.jpeg
    ├── Football.jpeg
    ├── LOL.jpeg
    ├── STF.jpeg
    └── brawlstars.jpeg
