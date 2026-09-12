# Species 5.5e

Módulo para **Foundry Virtual Tabletop V13** que añade especies adaptadas a **D&D 5e 2024 / 5.5e**, con sus rasgos, Advancement y automatizaciones.

Actualmente incluye soporte para:

- **Shadar-Kai**

---

## Compatibilidad

- Foundry VTT: **V13**
- D&D 5e System: **5.3.x**
- Orientado a reglas y estructura de personaje de **D&D 2024**

---

## Contenido

### Shadar-Kai

La especie incluye los siguientes rasgos:

- Fey Ancestry
- Keen Senses
- Trance
- Necrotic Resistance
- Blessing of the Raven Queen

También incluye:

- Darkvision 60 ft
- Speed 30 ft
- Advancement configurado
- Elección de competencia para Keen Senses
- Automatización de Blessing of the Raven Queen
- Iconos propios para la especie y todas sus Features

---

## Keen Senses

Al añadir Shadar-Kai a un personaje, Foundry permite elegir competencia en una de estas habilidades:

- Insight
- Perception
- Survival

La elección se gestiona mediante Advancement.

---

## Necrotic Resistance

Añade resistencia al daño necrótico al personaje.

---

## Blessing of the Raven Queen

Permite teletransportarse hasta **30 pies** como **Bonus Action**.

Características:

- Usos iguales al Proficiency Bonus
- Recuperación con Long Rest
- Movimiento automático del token
- Selección de destino sobre el mapa
- Validación automática de distancia máxima

A partir de nivel 3, después de usar el teletransporte, el personaje obtiene temporalmente resistencia a todo el daño hasta el inicio de su siguiente turno.

---

## Automatización

El archivo:

```text
scripts/species.js
