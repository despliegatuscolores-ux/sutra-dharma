# SŪTRA · DHARMA
### El Sendero Vivo · Sabiduría Budista Encarnada

> *Aforismos canónicos del Dharma convertidos en micro-prácticas cotidianas de atención plena, desidentificación y compasión radical.*

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-blue.svg)](index.html)
[![Offline First](https://img.shields.io/badge/Architecture-Offline--First-orange.svg)](#arquitectura-técnica)
[![Deploy with GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-violet.svg)](#despliegue-en-github-pages)
[![Collection: Sūtra Series](https://img.shields.io/badge/Collection-Sūtra%20Series-purple.svg)](#colección-sūtra)

---

## ☸️ Visión del Proyecto

El Dharma no fue concebido como un sistema de creencias metafísicas, sino como una **psicología empírica del despertar**: una invitación directa a investigar la naturaleza de la mente (*Ehipassiko*: "ven y comprueba por ti mismo"). 

**sutra-dharma** es el segundo volumen del ecosistema contemplativo *SŪTRA*. Su propósito es rescatar los textos canónicos en Pāli y sánscrito (*Dhammapada, Satipaṭṭhāna Sutta, Anattalakkhaṇa Sutta, Prajñāpāramitā Hṛdaya, Mettā Sutta*) y traducirlos a **micro-prácticas conductuales inmediatas**, eliminando cualquier barrera dogmática para hacer tangible la liberación del sufrimiento cotidiano (*Dukkha-nirodha*).

Desarrollada bajo la premisa de **cero dependencias externas**, la aplicación opera de forma íntegramente local, privada y sin intermediarios de red.

---

## ✨ Módulos Principales

### 1. El Sutta Vivo (Encarnación Cotidiana)
* **Texto raíz en Pāli / Sánscrito:** Transliteración fonética rigurosa.
* **Exégesis psicológica:** Traducción diáfana orientada al funcionamiento de los procesos cognitivos modernos.
* **Micro-práctica conductual:** Una consigna práctica precisa para ejecutar en el trabajo, en las pausas o en momentos de reactividad.
* **Cultivo de Sīla (Conducta Lúcida):** Registro de presencia diaria que preserva la racha de práctica en el almacenamiento local.

### 2. Laboratorio Satipaṭṭhāna (Las 4 Bases de la Atención)
Herramienta interactiva para recorrer sistemáticamente los cuatro fundamentos contemplativos del *Mahāsatipaṭṭhāna Sutta*:
1. **Kāya (Cuerpo y Respiración):** Reconexión háptica con el peso, la postura y la marea del aliento presente.
2. **Vedanā (Sensaciones Primarias):** Discriminación no reactiva del tono hedónico (placentero, desagradable o neutro) antes de que mute en apego o aversión.
3. **Citta (Estados Mentales):** Reconocimiento de la mente agitada, dispersa o serena sin emitir juicios de valor.
4. **Dhammā (Fenómenos y No-Apego):** Verificación de la impermanencia radical (*Anicca*) y desidentificación total del objeto mental.

### 3. Sala de Mettā Bhāvanā (Amor Benevolente)
Guía por etapas concéntricas para cultivar la benevolencia incondicional, disolviendo barreras de hostilidad y resistencia:
* **Fase 1:** Hacia uno mismo (*asentamiento en la dignidad interior*).
* **Fase 2:** Hacia un benefactor o maestro (*reconocimiento de gratitud*).
* **Fase 3:** Hacia un ser neutro (*reconocimiento de humanidad compartida*).
* **Fase 4:** Hacia una persona difícil (*alquimia activa del resentimiento*).
* **Fase 5:** Irradiación universal (*apertura compasiva sin fronteras*).

### 4. Respirador Ānāpānasati (Atención al Aliento)
* Guía geométrica circular fluida con cadencias tradicionales:
  * **Samatha (4-4-6-2):** Estabilización y concentración unidireccional.
  * **Vipassanā (Libre):** Observación pasiva del flujo natural del aire en la punta de la nariz.
  * **Paz Profunda (4-7-8):** Activación vagal y desactivación de la alerta simpática.
* **Campana Zen procedural:** Síntesis sonora acústica de campana de templo mediante la **Web Audio API** nativa (múltiples tonos senoidales armónicos con decaimiento exponencial natural, sin cargar archivos `.mp3` ni enlaces externos).

### 5. Diario del Cuenco Vacío (*Suññatā*)
* Espacio de vaciamiento y desprendimiento psicológico para depositar cargas, apegos y fricciones.
* Categorización analítica según las tres marcas de la existencia (*Tilakkhaṇa*):
  * **Anicca:** Impermanencia y cambio continuo.
  * **Dukkha:** Tensión provocada por la resistencia a lo que es.
  * **Anattā:** Ausencia de un yo rígido o sustancial.
  * **Upekkhā:** Ecuanimidad inquebrantable.
* Exportación sin fricción en formatos **JSON** (estructurado) y **TXT** (lectura en prosa).

### 6. Compendio del Dharma
* Biblioteca navegable organizada por colecciones canónicas (*Dhammapada, Satipaṭṭhāna, Sabiduría Prajñā, Mettā y Conducta*).
* Buscador instantáneo en tiempo real por conceptos en Pāli y español.

---

## 🏛️ Arquitectura Técnica

Diseñado para perdurar décadas sin mantenimiento de dependencias ni roturas de versión:

| Capa | Solución Técnica | Ventajas |
|---|---|---|
| **Estructura** | HTML5 Semántico Puro | Accesibilidad integral, sin capas de abstracción. |
| **Estilos** | CSS3 Nativo con Custom Properties | Modos de contraste armónicos, paleta inspirada en monasterios zen (arena, pizarra, óxido suave y tinta). |
| **Lógica** | JavaScript ES6+ Vanilla | Sin React, Vue o compiladores intermedios. Carga en < 100 ms. |
| **Sonido** | Web Audio API | Generador de armónicos senoidales procedurales de alta fidelidad sin peticiones HTTP. |
| **Persistencia** | Web Storage API (`localStorage`) | Datos 100% aislados en el dispositivo del usuario. Sin tracking ni bases de datos remotas. |

---

## 🚀 Instalación y Despliegue

### Uso Local
```bash
# 1. Clonar el repositorio
git clone [https://github.com/](https://github.com/)<tu-usuario>/sutra-dharma.git

# 2. Entrar al directorio
cd sutra-dharma

# 3. Abrir index.html en tu navegador preferido
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
