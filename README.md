<!-- Banner / Encabezado -->
<h1 align="center">¡Hola! Soy César Roque 👋</h1>
<p align="center">
  <b>Jr QA Analyst · Est. Ingeniería Informática · Enfoque en QA Manual & Automatización</b><br/>
  San Salvador, El Salvador · Español / English
</p>

<p align="center">
  <a href="mailto:cesarroque2002@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-cesarroque2002%40gmail.com-informational?logo=gmail"></a>
  <a href="https://www.linkedin.com/in/cesar-roqueinginf"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-César%20Roque-blue?logo=linkedin"></a>
  <img alt="Role" src="https://img.shields.io/badge/Role-Jr%20QA%20Analyst-6aa84f">
  <img alt="Focus" src="https://img.shields.io/badge/Focus-QA%20Manual%20%26%20Automation-3c78d8">
</p>

---

## 🧭 Sobre mí
Soy **Jr QA Analyst** y **estudiante de Ingeniería Informática**. Me apasiona asegurar la calidad de software mediante:
- Diseño de casos de prueba, regresión y documentación clara.
- Automatización de pruebas (UI/API) y **mejora continua** del proceso.
- Colaboración con desarrollo y operaciones para **entregas confiables**.

> Experiencia en QA para **sistemas de venta (SAP POS)** y aplicaciones internas; pruebas manuales y automatizadas; reporte/seguimiento de bugs; y mantenimiento de scripts de prueba. :contentReference[oaicite:0]{index=0}

---

## 🧪 QA & Tech Stack
**Lenguajes:** JavaScript, Python  
**QA / Testing:** Playwright, Selenium, Postman, Jest, TestComplete (desktop)  
**Prácticas:** SDLC, estrategias de prueba (funcionales, integración, regresión), gestión de defectos  
**Herramientas:** Git, GitHub Actions, SQL básico, Markdown

> Aptitudes destacadas: *Quality System, Quality Control, SDLC*. Idiomas: **Español (nativo)**, **Inglés (profesional)**. :contentReference[oaicite:1]{index=1}

---

## 💼 Experiencia (resumen)
**Junior QA Analyst — Dollarcity** *(ago 2024 – presente)*  
- Pruebas funcionales y de regresión en **SAP POS** y sitios internos.  
- **Automatización** de pruebas de escritorio con **TestComplete + Python**.  
- Gestión de bugs y fortalecimiento de la cobertura QA.  
- Trabajo conjunto con Dev/IT para optimizar procesos.  :contentReference[oaicite:2]{index=2}

**SAP Intern — QA** *(feb 2024 – ago 2024)*  
- Apoyo a QA en equipos multidisciplinarios, con foco en calidad y aprendizaje continuo.  :contentReference[oaicite:3]{index=3}

**Developer Odoo — Multiserviciossv** *(ene 2023 – ene 2024)*  
- Personalización de módulos, reportes y flujos; soporte en Python/JS; optimización de rendimiento.  :contentReference[oaicite:4]{index=4}

---

## 🏅 Certificaciones (selección)
- **Software Testing**  
- **Principiante en programación G6 — ONE**  
- **Macros y VBA**  
- **Autodescubrimiento y desarrollo personal**  
- **Emprendimiento, Agilidad y Protagonismo Profesional G6 — ONE**  :contentReference[oaicite:5]{index=5}

---

## 📌 Proyectos destacados
> Fija (pin) 4–6 repositorios que te representen. Ejemplos para tu perfil:

- **qa-automation-demo** — Pruebas E2E con Playwright (UI) y colección de Postman (API) + **GitHub Actions**.
- **sap-pos-test-scripts** — Scripts de validación para flujos clave (ventas, devoluciones, cierres) con reporting.
- **pos-restaurante-front** — Interfaz POS en React optimizada para pantallas táctiles; guía de instalación en README.
- **testing-strategy-examples** — Plantillas de casos de prueba (MD/CSV) y ejemplos de regresión.

Cada repo debería incluir:
- **Descripción clara**, **cómo correrlo**, **tecnologías**, **capturas** y **casos de ejemplo**.

---

## 🛠 CI: ejemplo rápido (Node + Playwright)
```yaml
# .github/workflows/tests.yml
name: Run tests
on: [push, pull_request]
jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-node@v4
        with:
          node-version: '20'
      - run: npm ci
      - run: npx playwright install --with-deps
      - run: npm test
