<h3 align="center"> 
<img alt="vmkdir banner" src="./assets/capabnt.banner2.png" width="1000" height="350">
</h3>

<h1 align="center">
   📚 <a href="#"> ABNT LATEX COVER </a>
</h1>

<h3 align="center">
    Template in ABNT standards made with LaTex
</h3>


<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vitoriape/capabnt">
  
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/vitoriape/capabnt">
  
  <a href="https://github.com/vitoriape/capabnt/blob/main/LICENSE">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-green.svg">
  </a>
  
  <a href="https://github.com/vitoriape/capabnt/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vitoriape/coverABNT-pdfLaTex">
  </a>
</p>

<h4 align="center"> 
	 Status: Finished
</h4>

---

Index
=================
<!--ts-->
   * [About](#about)
   * [Tools](#tools)
   * [References](#references)
   * [Features](#features)
   * [Layout](#layout)
   * [Pre-requisites](#pre-requisites)
   * [Setup](#setup)
   * [Using Overleaf](#using-overleaf)
   * [Team](#team)

## About
This project is an LaTex template for creates titlepages/covers in ABNT standards. The tex file will provide a compiled PDF. This is a Tex project developed using `Tex Live 2021`.

>[README em Português (pt-br)](https://github.com/vitoriape/capabnt/blob/main/LEIAME.md). <img src="https://camo.githubusercontent.com/dcc375ada213d3ac04a9781518098cd4d071601bc2ccfc120025cc32b6d38fab/68747470733a2f2f63646e2e737461746963616c792e636f6d2f67682f686a6e696c73736f6e2f636f756e7472792d666c6167732f6d61737465722f7376672f62722e737667" alt="brazil flag" width="20" height="20">

---

## Tools
Development of this template utilizes the tools listed below:

- [Git](https://git-scm.com/)
- [LaTex](https://www.latex-project.org/)
- [Overleaf](https://www.overleaf.com/learn)

## References
For more information about the brazilian technical standards, check out the website of the [Brazilian Association of Technical Standards](https://www.abnt.org.br/).

## Features

- [x] Usepackages
- [x] Classes
- [x] Cover
- [x] Titlepage
- [ ] Template of the following report elements

## Layout

<table class="tg">
<thead>

  <tr>
    <th class="tg-c3ow">Cover</th>
    <th class="tg-c3ow">Titlepage</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow"><img src="./assets/coverpage-abnt.png" alt="coverpage" width="350" height="400"><br></td>
    <td class="tg-c3ow"><img src="./assets/titlepage-abnt.png" alt="titlepage" width="350" height="400"><br></td>
  </tr>
</tbody>
</table>

---

## Pre-requisites

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

## Setup

```bash
# Clone this repository
$ git clone <https://github.com/vitoriape/capabnt/>

# Access the project folder
$ cd capabnt

# Upload the file abnt-cover.tex on a LaTeX Editors/IDEs like MiKTeX or Overleaf
```

## Using Overleaf
A easy way to enjoy LaTex tools is using [Overleaf](https://pt.overleaf.com/), an cloud-based collaborative editor:

<img alt="overleaf editor" src="./assets/overleaf-editor.jpeg">

For use this template on Overleaf just follow the [setup](#instalação) directions, and then [upload](https://www.overleaf.com/learn/how-to/Uploading_a_project) the `tex` file of this project.

---

## Team
### Author

<table>
  <tr>
    <td align="center"><a href="https://github.com/vitoriape"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/55922652?v=4" width="100px;" alt=""/><br /><sub><b>Vitória Peçanha</b></sub></a><br /><a href="https://www.linkedin.com/in/vitoria-pecanha/" title="LinkedIn">🌐</a>   <a href="mailto:vitoriapecanha.log@gmail.com" title="E-mail">📬</a>   <a href="https://translate.habitica.com/user/PenariaToji/" title="Linguists Commonwealth">📜</a></td>   
</table>


### License

This project is under the   
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

