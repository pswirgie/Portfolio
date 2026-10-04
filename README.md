<p id="top"></p>
<div align="center">

# Portfolio

</div>


A personal portfolio website built with Astro and Tailwind CSS, showcasing my projects, skills and CV.

[**View Live Site**](https://pswirgie.github.io/Portfolio/)

![Built with Astro](https://img.shields.io/badge/Built_with-Astro-BC52EE?style=flat-square&logo=astro&logoColor=fff)
![Deployed on GitHub Pages](https://img.shields.io/badge/Deployed_on-GitHub_Pages-121013?style=flat-square&logo=github&logoColor=white)

- [Portfolio](#portfolio)
  - [Description](#description)
  - [Features added](#features-added)
  - [Tech Stack](#tech-stack)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
  - [Instructions](#instructions)
    - [Installation](#installation)
  - [Project Structure](#project-structure)
  - [Deployment](#deployment)
  - [Roadmap](#roadmap)
  - [Acknowledgments](#acknowledgments)

<!-- new line -->
<br>

## Description

This repository contains the source code of my personal portfolio. It is built on top of [**astro_academia**](https://github.com/maiobarbero/astro_academia), an open-source Astro template by [Matteo Barbero](https://maiobarbero.dev), originally designed for academic websites.

I have significantly customized the template to turn it into a portfolio tailored to a developer profile: new visual identity, reorganized content, a dedicated tech stack section and a downloadable CV.

<!-- new line -->
<br>

## Features added

Compared to the original template, I added and reworked the following:
 
- **Language toggle (EN ⇄ FR):** switch between English and French *(work in progress)*.
- **Custom fonts:** new typography for a distinctive visual identity.
- **Reworked themes:** updated color palette with refined light and dark modes.
- **Tech Stack section:** technologies displayed with dedicated badges.
- **CV page with PDF download:** a button lets visitors download my CV directly.
- **Reorganized sections:** content restructured to highlight my projects and skills.

[back to top](#top)
<!-- new line -->
<br>

## Tech Stack 

[![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=fff)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=fff)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)](#)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](#)
[![Visual Studio Code](https://custom-icon-badges.demolab.com/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visualstudiocode&logoColor=white)](#)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](#)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-121013?style=for-the-badge&logo=github&logoColor=white)](#)

[back to top](#top)
<!-- new line -->
<br>

## Getting Started

### Prerequisites
 
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) and npm (the required version is specified in `.nvmrc`)
- [nvm](https://github.com/nvm-sh/nvm) (recommended, to match the Node version)


[back to top](#top)
<!-- new line -->
<br>

## Instructions

### Installation
 
1. **Clone the repository**
```bash
   git clone https://github.com/pswirgie/Portfolio.git
   cd Portfolio
```
 
2. **Use the correct Node version** (see `.nvmrc` in this project)
```bash
   nvm use
```
 
3. **Install dependencies**
```bash
   npm install
```
 
4. **Start the development server**
```bash
   npm run dev
```

[back to top](#top)
<!-- new line -->
<br>

## Project Structure

```text
├── .github/workflows/   # Workflow for GitHub Pages
├── public/              # Static assets (images, CV PDF, ...)
├── src/                 # Pages, components, styles and site data
├── astro.config.mjs     # Astro configuration
├── tailwind.config.mjs  # Tailwind configuration
├── tsconfig.json        # TypeScript configuration
└── package.json
```

[back to top](#top)
<!-- new line -->
<br>


## Deployment

The site is deployed automatically to **GitHub Pages** through a **GitHub Actions** workflow (see `.github/workflows/`). Every push to the `main` branch triggers a new build and deployment.


[back to top](#top)
<!-- new line -->
<br>


## Roadmap

- [ ] Complete the EN ⇄ FR language toggle
- [ ] Add detailed project pages with screenshots
- [ ] Improve accessibility and SEO

[back to top](#top)
<!-- new line -->
<br>


## Acknowledgments

This project is based on [**astro_academia**](https://github.com/maiobarbero/astro_academia) by [Matteo Barbero](https://maiobarbero.dev). Many thanks for the excellent foundation.

[back to top](#top)

