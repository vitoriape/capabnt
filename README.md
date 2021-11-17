<h3 align="center"> 
ABNT LaTex Cover
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vitoriape/coverABNT-pdfLaTex">
  
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/vitoriape/coverABNT-pdfLaTex">
  
  <a href="https://github.com/vitoriape/capabnt/blob/main/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-green.svg">
  </a>
  
  <a href="https://github.com/vitoriape/coverABNT-pdfLaTex/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vitoriape/coverABNT-pdfLaTex">
  </a>
</p>

---

<p align="center">
 ◽ <a href="#-about">About</a> |
 <a href="#-tools">Tools</a> | 
 <a href="#-features">Features</a> | 
 <a href="#-setup">Setup</a> ◽
</p>

### 📌 About

> [Versão em Português (pt-br)](https://github.com/vitoriape/capabnt/blob/main/LEIAME.md). <img src="https://camo.githubusercontent.com/dcc375ada213d3ac04a9781518098cd4d071601bc2ccfc120025cc32b6d38fab/68747470733a2f2f63646e2e737461746963616c792e636f6d2f67682f686a6e696c73736f6e2f636f756e7472792d666c6167732f6d61737465722f7376672f62722e737667" alt="brazil flag" width="20" height="20">

This project is an LaTex template for creates titlepages/covers in ABNT standards. The tex file will provide a compiled PDF. 
This is a Tex project developed using TeX Live 2021. <i>Make sure you have at least this version installed.</i>

### 🛠 Tools

Development of this template utilizes the tools listed below:

- [Git](https://git-scm.com/)
- [LaTex](https://www.latex-project.org/)

### 📊 Features

- [x] Cover
- [x] Titlepage
- [ ] Abstract and following report elements

<table class="tg">
<thead>

  <tr>
    <th class="tg-c3ow">Cover</th>
    <th class="tg-c3ow">Titlepage</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow"><img src="https://github.com/vitoriape/coverABNT-pdfLaTex/blob/main/pages/coverpage-abnt.png" alt="coverpage" width="350" height="400"><br></td>
    <td class="tg-c3ow"><img src="https://github.com/vitoriape/coverABNT-pdfLaTex/blob/main/pages/titlepage-abnt.png" alt="titlepage" width="350" height="400"><br></td>
  </tr>
</tbody>
</table>

### 💻 Setup

```bash
# Clone this repository
$ git clone <https://github.com/vitoriape/capabnt/>

# Access the project folder via cmd
$ cd capabnt

# Import the file abnt-cover.tex on a LaTeX Editors/IDEs like MiKTeX or Overleaf
```

- Document Class

```tex
\documentclass[a4paper,10pt,titlepage]{article}
```

- Packages

```tex
\usepackage[brazilian]{babel}
\usepackage[utf8]{inputenc}
\usepackage{setspace}
\usepackage{ragged2e}
\usepackage{ragged2e}
\usepackage{times}
\usepackage{geometry}
\geometry{
 a4paper,
 total={170mm,257mm},
 left=20mm,
 top=20mm,
 }
```

---
