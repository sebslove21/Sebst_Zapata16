
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Sebastian%20Zapata%20H.&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Backend%20Developer%20%7C%20Database%20Developer%20%7C%20SENA&descAlignY=55&descSize=18"/>

</div>

---

## Sobre mí

Estudiante de **Análisis y Desarrollo de Software (ADSO)** en el **SENA**, enfocado en el **desarrollo backend** y el **diseño y administración de bases de datos**. Me especializo en construir arquitecturas robustas, diseñar esquemas relacionales eficientes y resolver problemas lógicos complejos. Actualmente en búsqueda de **co-patrocinio, práctica profesional o rol junior**.

- Desarrollando actualmente **Reto_Room-911** (Spring Boot + PostgreSQL)
- Diseñando sistemas de gestión relacional optimizados como **SolPark**
- Profundizando en **arquitectura de software**, **Requisitos No Funcionales (NFRs)** y **buenas prácticas REST**
- Disponible para trabajo remoto, híbrido o presencial

---

## Stack tecnológico

### Lenguajes
<div align="center">
  <img src="https://skillicons.dev/icons?i=java,python,js,html,css&theme=dark" />
</div>

### Frameworks y librerías
<div align="center">
  <img src="https://skillicons.dev/icons?i=spring,flask,bootstrap&theme=dark" />
</div>

### Bases de datos (Mi Especialidad)
<div align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mariadb&theme=dark" />
</div>

### Herramientas y entornos
<div align="center">
  <img src="https://skillicons.dev/icons?i=git,github,postman,vscode,windows&theme=dark" />
</div>

---

## Proyectos destacados

### Reto_Room-911 — API Backend
> Solución backend robusta y escalable construida con estándares empresariales.

- Persistencia avanzada utilizando un servidor nativo PostgreSQL perfectamente estructurado.
- Arquitectura limpia y modular manejada a través de Spring Boot.
- Manejo riguroso de dependencias y aislamiento de lógica de negocio.
- `Java` · `Spring Boot` · `PostgreSQL` · `REST API`

### SolPark — Sistema de Gestión de Parqueaderos
> Diseño e implementación completa de base de datos relacional orientada al rendimiento.

- Creación y optimización de esquemas SQL complejos y mapeo de relaciones.
- Control estricto de integridad de datos, tipos y restricciones de usuario.
- Administración y solución de problemas de conectividad local en entornos de desarrollo.
- `SQL` · `MySQL` · `MariaDB` · `Database Design`

---

## Estadísticas de GitHub

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=sebslove21&show_icons=true&theme=youtube-dark&hide_border=true&include_all_commits=true&count_private=true&locale=es"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sebslove21&layout=compact&theme=youtube-dark&hide_border=true&locale=es&langs_count=8"/>
</div>

<div align="center">
  <a href="https://git.io/streak-stats">
    <img src="https://github-readme-streak-stats.herokuapp.com?user=sebslove21&theme=youtube-dark&hide_border=true&locale=es" alt="GitHub Streak" />
  </a>
</div>

---

## Gráfico de contribuciones

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sebslove21/sebslove21/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sebslove21/sebslove21/output/github-contribution-grid-snake.svg"/>
    <img alt="snake animation" src="https://raw.githubusercontent.com/sebslove21/sebslove21/output/github-contribution-grid-snake.svg"/>
  </picture>
</div>

---

## Escuchando en Spotify

<p align="center">
  <a href="https://spotify-github-profile.kittinanx.com/api/view?uid=31wqkzuhblsg2nx462ydy54pmyh4&redirect=true">
    <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=31wqkzuhblsg2nx462ydy54pmyh4&cover_image=true&theme=default&show_offline=true&background_color=121212&interchange=true&profanity=true"/>
  </a>
</p>

---

## Formación e Idiomas

- **Tecnólogo en Análisis y Desarrollo de Software (ADSO)** — SENA *(En curso)*
- **Español:** Nativo
- **Inglés Técnico:** Orientado a documentación, código y lectura técnica.

---

## Contacto

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sebslove21)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Sebstzapata16@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sebslove21)

</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=sebslove21&color=blue&style=flat-square&label=Visitas+al+perfil"/>
</div>

---

<details>
<summary><b>Configuración — Gráfico animado de contribuciones</b></summary>

Crea el archivo `.github/workflows/snake.yml` dentro de este mismo repositorio:

```yaml
name: generate snake animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
