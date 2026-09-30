# Mosquito Intelligence Aljaraque

## Territorial Biointelligence for Mosquito Surveillance
### Biointeligencia territorial para la vigilancia de mosquitos

**Case study / Caso de estudio: Aljaraque, Huelva, Spain**

---

## English

### Overview

This project explores the use of **territorial biointelligence** for local mosquito surveillance using the municipality of **Aljaraque (Huelva, Spain)** as a case study.

The project uses open scientific data from **Mosquito Alert**, a citizen-science initiative that collects and validates observations of mosquitoes, breeding sites and mosquito bites.

The main objective is to determine whether these data provide sufficient temporal, spatial and biological information to build a useful local vector-intelligence demonstrator.

### Research question

> **Does Mosquito Alert provide sufficient data to build a useful territorial vector-intelligence demonstrator for Aljaraque?**

### Data sources

The initial analysis focuses on four Mosquito Alert data products:

- `reports` — citizen-science mosquito, breeding-site and bite reports.
- `sampling_effort` — estimates of citizen-science sampling effort.
- `model_tables` — modelled mosquito distribution and encounter probabilities.
- `muni_preds` — daily municipal predictions for *Aedes albopictus* in Spain.

Official metadata portal:

https://labs.mosquitoalert.com/metadata_public_portal/README.html

### Analytical approach

The project follows the analytical chain:

**Observed evidence → Sampling effort → Modelled information → Territorial intelligence**

The analysis will assess:

- temporal coverage;
- spatial coverage;
- mosquito observations;
- evidence of *Aedes albopictus* and other relevant taxa;
- citizen-science sampling effort;
- modelled mosquito probabilities;
- missing data and data-quality limitations;
- suitability of the available data for local vector surveillance.

### Current status

**Phase 1 — Data acquisition and audit**

The first stage focuses exclusively on determining the availability, coverage and quality of Mosquito Alert data for Aljaraque.

Environmental, epidemiological, demographic or socioeconomic variables will only be incorporated in later stages if they provide additional explanatory or decision-making value.

---

## Español

### Descripción

Este proyecto explora el uso de la **biointeligencia territorial** aplicada a la vigilancia local de mosquitos, utilizando como caso de estudio el municipio de **Aljaraque (Huelva, España)**.

El proyecto utiliza datos científicos abiertos de **Mosquito Alert**, una iniciativa de ciencia ciudadana que recopila y valida observaciones de mosquitos, lugares de cría y picaduras.

El objetivo principal es determinar si estos datos proporcionan suficiente información temporal, espacial y biológica para construir un demostrador útil de inteligencia vectorial local.

### Pregunta de investigación

> **¿Proporciona Mosquito Alert datos suficientes para construir un demostrador útil de inteligencia vectorial territorial para Aljaraque?**

### Fuentes de datos

El análisis inicial se centra en cuatro productos de datos de Mosquito Alert:

- `reports` — observaciones ciudadanas de mosquitos, criaderos y picaduras.
- `sampling_effort` — estimaciones del esfuerzo de muestreo ciudadano.
- `model_tables` — modelos de distribución y probabilidad de encuentro con mosquitos.
- `muni_preds` — predicciones municipales diarias de *Aedes albopictus* en España.

Portal oficial de metadatos:

https://labs.mosquitoalert.com/metadata_public_portal/README.html

### Enfoque analítico

El proyecto sigue la cadena:

**Evidencia observada → Esfuerzo de muestreo → Información modelizada → Inteligencia territorial**

El análisis evaluará:

- cobertura temporal;
- cobertura espacial;
- observaciones de mosquitos;
- evidencia de *Aedes albopictus* y otros taxones relevantes;
- esfuerzo de muestreo de ciencia ciudadana;
- probabilidades modelizadas;
- datos faltantes y limitaciones de calidad;
- idoneidad de los datos disponibles para la vigilancia vectorial local.

### Estado actual

**Fase 1 — Obtención y auditoría de datos**

La primera fase se centra exclusivamente en determinar la disponibilidad, cobertura y calidad de los datos de Mosquito Alert para Aljaraque.

Las variables ambientales, epidemiológicas, demográficas o socioeconómicas se incorporarán posteriormente únicamente si aportan capacidad explicativa o utilidad para la toma de decisiones.

---

## Project structure / Estructura del proyecto

```text
mosquito-intelligence-aljaraque/
│
├── notebooks/
│   └── 01_mosquito_alert_aljaraque_data_audit.ipynb
│
├── data/
│   └── processed/
│
├── figures/
│
├── README.md
│
└── LICENSE
