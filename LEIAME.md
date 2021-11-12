<h3 align="center"> 
Capa ABNT LaTex
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

---

<p align="center">
 ◽ <a href="#-sobre">Sobre</a> |
 <a href="#-ferramentas">Ferramentas</a> | 
 <a href="#-recursos">Recursos</a> | 
 <a href="#-instalação">Instalação</a> |
 <a href="#-autor">Autor</a> ◽
</p>

### 📌 Sobre

Este projeto é um modelo em LaTex para criação de folhas de rosto/capas nas normas da ABNT. O arquivo tex gera um PDF compilado.
Este é um projeto em Tex desenvolvido com Tex Live 2021. <i>Certifique-se de ter esta versão instalada.</i>

### 🛠 Ferramentas

O desenvolvimento desse modelo utiliza as seguintes ferramentas:

- [Git](https://git-scm.com/)
- [LaTex](https://www.latex-project.org/)

### 📊 Recursos

- [x] Capa
- [x] Folha de Rosto
- [ ] Resumo e demais elementos de um relatório

<table class="tg">
<thead>

  <tr>
    <th class="tg-c3ow">Capa</th>
    <th class="tg-c3ow">Folha de Rosto</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow"><img src="https://github.com/vitoriape/coverABNT-pdfLaTex/blob/main/pages/coverpage-abnt.png" alt="coverpage" width="350" height="400"><br></td>
    <td class="tg-c3ow"><img src="https://github.com/vitoriape/coverABNT-pdfLaTex/blob/main/pages/titlepage-abnt.png" alt="titlepage" width="350" height="400"><br></td>
  </tr>
</tbody>
</table>

### 💻 Instalação

```bash
# Clone esse repositório
$ git clone <https://github.com/vitoriape/capabnt/>

# Acesse a pasta do projeto pelo terminal
$ cd capabnt

# Importe o arquivo abnt-cover.tex em uma IDE editor de LaTeX, como MiKTeX ou Overleaf
```

- Classe do Documento

```tex
\documentclass[a4paper,10pt,titlepage]{article}
```

- Pacotes

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

### 💡 Autor

<a href="https://www.linkedin.com/in/vitoria-pecanha/">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/55922652?v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Vitória Peçanha</b></sub></a> <a href="https://www.linkedin.com/in/vitoria-pecanha/" title="LinkedIn"></a>


Feito por Vitória Peçanha 📚 Entre em contato!


[![Linkedin Badge](https://img.shields.io/badge/-Vitória-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/vitoria-pecanha/)](https://www.linkedin.com/in/vitoria-pecanha/) [![Gmail Badge](https://img.shields.io/badge/-vitoriapecanha.log@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:vitoriapecanha.log@gmail.com)](mailto:vitoriapecanha.log@gmail.com)
