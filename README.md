# 🌎 Costa Rica vs Latinoamérica — Comparativa STEAM Regional

![Estado](https://img.shields.io/badge/Estado-En%20progreso-yellow)
![Proyecto](https://img.shields.io/badge/Portafolio-Proyecto%204%20de%204-purple)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)

> **Proyecto 4 de 4** de la serie
> [Radiografía de Empleabilidad STEAM en Costa Rica](https://github.com/RDRamosU/data-portfolio)

---

## 🔍 Pregunta central

**¿Cómo se posiciona Costa Rica frente a Latinoamérica
en formación y empleabilidad STEAM?**

---

## 📌 Preguntas de análisis

1. ¿Qué porcentaje de graduados terciarios son STEM en CR
   vs el promedio de Latinoamérica?
2. ¿Cómo se compara la brecha de género STEM de CR
   con el resto de la región?
3. ¿Qué posición ocupa CR en asistencia y completación
   terciaria dentro de Latinoamérica?
4. ¿Cómo se compara el empleo tech de CR (Zona Franca,
   exportaciones TIC) con indicadores regionales?
5. ¿Qué ventajas competitivas tiene CR en el ecosistema
   STEAM de la región?

---

## 🎯 Hallazgo anticipado

Costa Rica ocupa una posición favorable en el ecosistema
STEAM latinoamericano, con ventajas concretas en:

- **Participación femenina en STEAM:** 47% en CR vs 40% máximo
  regional y 15% de mujeres en STEM en LAC en general
- **Asistencia terciaria:** CR entre los 4 países líderes
  de la región junto a Chile, Bolivia y Argentina
- **Exportaciones TIC:** USD 5.539M en 2022 — 43.4% de
  las exportaciones de servicios totales
- **Empleo tech formal:** crecimiento del 37.3% en un año
  (2020→2021), muy por encima del promedio regional

---

## 📂 Fuentes de datos

| Fuente | Institución | Datos clave | Periodo |
|--------|------------|-------------|---------|
| UNESCO UIS Data Browser | UNESCO | % graduados STEM por país | 2018–2022 |
| EdStats / World Bank | Banco Mundial | Matrícula terciaria LAC | 2015–2022 |
| CIMA Brief 30 y 31 | BID | Asistencia y completación terciaria LAC | 2006–2023 |
| Higher Education Global Data | UNESCO IESALC | Brecha género STEM por región | 2019–2022 |
| Proyectos 1, 2 y 3 | OPES-CONARE · MICITT · PROCOMER | Datos CR ya analizados | 2014–2025 |

> ⚠️ **Política de datos:** Todos los datasets son de acceso público,
> no contienen PII y provienen de organizaciones internacionales oficiales.

---

## 🗂️ Estructura del proyecto

```
cr-steam-comparativa-regional/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   ├── raw/                          # Datos originales sin modificar
│   └── processed/                    # Datos limpios para análisis
├── notebooks/
│   ├── 01_definicion_problema.ipynb
│   ├── 02_exploracion_datos.ipynb
│   ├── 03_limpieza_preparacion.ipynb
│   └── 04_visualizaciones_hallazgos.ipynb
└── assets/
    └── graficas/                     # Visualizaciones exportadas
```

---

## 📓 Notebooks

| Notebook | Descripción | Estado |
|----------|-------------|--------|
| [01 — Definición del problema](notebooks/01_definicion_problema.ipynb) | Contexto, preguntas y posición anticipada de CR | 🟢 Completado |
| [02 — Exploración de datos](notebooks/02_exploracion_datos.ipynb) | Carga y exploración de datos UNESCO, BM y BID | 🟢 Completado |
| [03 — Limpieza y preparación](notebooks/03_limpieza_preparacion.ipynb) | Dataset comparativo LAC consolidado | 🟢 Completado |
| [04 — Visualizaciones y hallazgos](notebooks/04_visualizaciones_hallazgos.ipynb) | Gráficas comparativas · ranking · conclusiones | 🟢 Completado |

---

## 📊 Variables clave del análisis

| Variable | Fuente | Cobertura |
|----------|--------|-----------|
| % graduados STEM del total terciario | UNESCO UIS | CR + 10 países LAC |
| % mujeres en graduados STEM | UNESCO UIS | CR + región LAC |
| Tasa neta asistencia terciaria | BID/CIMA | CR + 17 países LAC |
| Exportaciones TIC (USD millones) | BCCR | CR 2020–2022 |
| Empleo tech sector servicios | PROCOMER | CR 2020–2024 |
| Desempleo STEM | CONARE (P1 y P2) | CR 2019 y 2022 |

---

## 🔗 Continuidad con proyectos anteriores

Este proyecto integra los hallazgos de los tres proyectos anteriores
para construir una narrativa comparativa completa:

| Proyecto | Hallazgo clave | Uso en P4 |
|----------|---------------|-----------|
| P1 — Graduados STEAM | 7.273 graduados STEAM/año · 47% mujeres | Base comparativa vs LAC |
| P2 — Mercado laboral | Ratio 15x empleos vs graduados · 4.2% desempleo STEM | Posición competitiva CR |
| P3 — Habilidades | 4 brechas sin cobertura universitaria | Contexto de mejora necesaria |

---

## 🔧 Cómo ejecutar este proyecto

```bash
git clone https://github.com/RDRamosU/cr-steam-comparativa-regional.git
cd cr-steam-comparativa-regional
pip install -r requirements.txt
jupyter notebook
```

> También puede ejecutarse en **Google Colab** sin instalación local.

---

## 🛠️ Tecnologías

`Python 3.11+` `pandas` `NumPy` `Matplotlib` `Seaborn` `Jupyter`

---

## 📎 Parte de la serie

| # | Proyecto | Estado |
|---|----------|--------|
| 1 | [Graduados STEAM en CR 2014–2022](https://github.com/RDRamosU/cr-graduados-steam-analisis) | [🟢 Completado](https://www.linkedin.com/pulse/graduados-steam-de-las-universidades-estatales-costa-rica-zaj4e) |
| 2 | [Mercado laboral tech en CR](https://github.com/RDRamosU/mercado-laboral-steam-cr) | [🟢 Completado](https://www.linkedin.com/posts/ruben-ramos_github-rdramosumercado-laboral-steam-cr-share-7474864458662715392-I-1o/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAChGLMoBf7GYJaNtqlgpzhtt9Jr9qJkG8zc) |
| 3 | [Habilidades demandadas tech CR](https://github.com/RDRamosU/cr-habilidades-demanda-tech) | [🟢 Completado](https://www.linkedin.com/posts/ruben-ramos_anaerlisisdedatos-steam-costarica-share-7475270119057805328-ASBm/) |
| **4** | **CR vs Latinoamérica en STEAM** ← estás aquí | [🟢 Completado](https://www.linkedin.com/posts/ruben-ramos_anaerlisisdedatos-steam-costarica-share-7476014984431554560-7Uzr/) |

---
## 📰 Artículo publicado

Análisis completo publicado en LinkedIn:  
[Comparativa regional: Costa Rica vs Latinoamérica en formación y empleabilidad STEAM]( https://www.linkedin.com/posts/ruben-ramos_anaerlisisdedatos-steam-costarica-share-7476014984431554560-7Uzr/?utm_source=share&utm_medium=member_desktop&rcm=ACoAAChGLMoBf7GYJaNtqlgpzhtt9Jr9qJkG8zc) 

---

## 👤 Autor

**Ruben Dario Ramos Ulate**
🌐 [rubendario.dev](https://rubendario.dev) · 💼 [LinkedIn](https://www.linkedin.com/in/ruben-ramos) · 🐙 [GitHub](https://github.com/RDRamosU)
