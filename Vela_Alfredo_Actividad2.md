# Configuración básica de un servidor DNS en Debian 12

## 0. Índice
- [1. Introducción](#1-introducción)
- [2. Creación de la máquina](#2-creación-de-la-máquina)
  - [2.1 Importar la OVA](#21-importar-la-ova)
  - [2.2 Configuración de la máquina](#22-configuración-de-la-máquina)
  - [2.3 Configuración Inicial](#23-configuración-inicial)
- [3. Comparativa técnica](#3-comparativa-técnica)
- [4. Ventajas y desventajas](#4-ventajas-y-desventajas)
- [5. Aplicaciones prácticas](#5-aplicaciones-prácticas)
- [6. Resultados y conclusiones](#6-resultados-y-conclusiones)
- [7. Recursos externos](#7-recursos-externos)
- [8. Imagen ilustrativa](#8-imagen-ilustrativa)

---

## 1. Introducción

Vamos a crear en **VirtualBox** una máquina de *Debian 12* sobre la cual configuraremos un servidor DNS.

👉 Seguiremos 3 pasos simples:
- ***Creación de la máquina.***
- ***Instalación de la apt Bind9 (DNS).***
- ***Configuración básica.***

---

## 2. Creación de la máquina

### 2.1 Importar la OVA

Descargamos u obtenemos una ***OVA*** de Debian 12 para importarla desde **VB**.
Abrimos **VB** y desde *Archivo* seleccionamos *Importar servicio virtualizado.*

Configuración de la importación:
- Busca la **OVA** en tus archivos.
- Selecciona *Generar una nueva **MAC**.
- Importar.

---

### 2.2 Configuración de la máquina 

Entramos en *Settings* de la máquina y personalizamos las opciones.

Pasos:
1. Nombramos la máquina.
2. Ajustamos la RAM, CPUs a los valores deseados.
3. Desmarcamos el audio al ser innecesario.
4. Configuramos la red.
5. Iniciamos la máquina para comprobar que funciona.

---

### 2.3 Configuración Inicial



Tipos:
1. **Monomodo** 🚀: largas distancias, alta capacidad.
2. **Multimodo** 🌐: distancias cortas, menor coste.

Beneficios:
- Ancho de banda extremadamente alto.
- Inmunidad total a interferencias electromagnéticas.
- Seguridad en la transmisión 🔒.

---

## 3. Comparativa técnica

| Medio          | Ancho de banda | Distancia máxima | Inmunidad al ruido | Coste relativo |
|----------------|----------------|------------------|--------------------|----------------|
| Par trenzado   | Medio          | 100 m            | Baja               | Bajo           |
| Cable coaxial  | Medio-Alto     | 500 m            | Media              | Medio          |
| Fibra óptica   | Muy alto       | > 40 km          | Muy alta           | Alto           |

---

## 4. Ventajas y desventajas

### 4.1 Ventajas generales ✅
- Control del medio físico.
- Mayor seguridad frente a escuchas.
- Estabilidad en entornos industriales.

### 4.2 Desventajas generales ❌
- Coste de instalación (especialmente en fibra).
- Fragilidad mecánica en algunos casos.
- Necesidad de infraestructura física.

---

## 5. Aplicaciones prácticas

Lista ordenada con emojis de números:

1️⃣ **Par trenzado**: redes LAN, telefonía.  
2️⃣ **Coaxial**: televisión por cable, sistemas de CCTV.  
3️⃣ **Fibra óptica**: backbone de Internet, interconexión de centros de datos, redes troncales de operadores.

Lista no ordenada con emojis:

- 🌍 Conexiones internacionales (fibra submarina).  
- 🏢 Redes empresariales.  
- 🏠 Hogares con FTTH (Fiber To The Home).  

---

## 6. Resultados y conclusiones

> **Resultado clave:** la fibra óptica se posiciona como el medio guiado más eficiente para el futuro de las telecomunicaciones.  

En resumen:
- El **par trenzado** sigue siendo la opción más económica y práctica en entornos locales.  
- El **coaxial** mantiene su relevancia en televisión y ciertos sistemas de seguridad.  
- La **fibra óptica** es la apuesta estratégica para redes de alta velocidad y gran capacidad.  

---

## 7. Recursos externos

- [Artículo sobre medios de transmisión en Wikipedia](https://es.wikipedia.org/wiki/Medio_de_transmisi%C3%B3n)  
- [Guía de fibra óptica de Cisco](https://www.cisco.com/c/es_mx/support/docs/optical/synchronous-digital-hierarchy-sdh/29000-db-29000.html)  
- [Vídeo sobre fibra óptica](https://www.youtube.com/watch?v=LaKZ5DDRPS8)
---

## 8. Imagen ilustrativa

![Fibra óptica](http://www.yio.com.ar/fibras-opticas/imagenes/fibra-optica-multimodo-monomodo.gif)
---
