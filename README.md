<h3 align="center"> 
ABNT LaTex Cover
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vitoriape/coverABNT-pdfLaTex">
  
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/vitoriape/coverABNT-pdfLaTex">
  
  <a href="https://github.com/vitoriape/coverABNT-pdfLaTex/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/vitoriape/coverABNT-pdfLaTex">
  </a>
</p>

---

<p align="center">
 ◽ <a href="#-about">About</a> |
 <a href="#-tools">Tools</a> | 
 <a href="#-features">Features</a> | 
 <a href="#-setup">Setup</a> |
 <a href="#-author">Author</a> ◽
</p>

### 📌 About

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

### 💡 Author

<a href="https://blog.rocketseat.com.br/author/thiago/">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/55922652?v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Vitória Peçanha</b></sub></a> <a href="https://www.linkedin.com/in/vitoria-pecanha/" title="LinkedIn"></a>


Made by Vitória Peçanha 📚 Contact me!


[![Linkedin Badge](https://img.shields.io/badge/-Vitória-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/vitoria-pecanha/)](https://www.linkedin.com/in/vitoria-pecanha/) [![Gmail Badge](https://img.shields.io/badge/-vitoriapecanha.log@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:vitoriapecanha.log@gmail.com)](mailto:vitoriapecanha.log@gmail.com)
