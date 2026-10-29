# ✍️ Historia, evolución y usos de Markdown en la práctica

## 1. Panorama general
**Markdown** es un *lenguaje de marcado ligero* diseñado para que el texto en bruto sea legible y, al mismo tiempo, fácilmente convertible a otros formatos. Su propuesta es clara: ***escribir sin fricción***, manteniendo el control del contenido sin atarse a editores visuales.

> 🎯 **Objetivo central:** producir documentos limpios, duraderos y portables que funcionen bien en control de versiones y fluyan hacia HTML, PDF y más.

---

## 2. Historia y evolución

### 2.1. Origen
- **2004:** Propuesto por **John Gruber** con aportaciones de *Aaron Swartz*.  
- Motivación: recuperar la **legibilidad del texto plano** típica del correo electrónico, pero con una sintaxis mínima y consistente.  
- Filosofía: lo escrito debe ser útil y comprensible incluso sin “renderizado”.

### 2.2. Evolución y “sabores”
A lo largo del tiempo surgieron variantes que añadieron funciones:

- **GFM (GitHub Flavored Markdown):** tablas, listas de tareas, delimitadores de código por lenguaje, y detalles prácticos para desarrolladores.
- **Pandoc Markdown:** extensiones para notas al pie, tablas avanzadas, referencias cruzadas y conversión a múltiples formatos.
- **CommonMark:** intento de especificación más estricta para evitar ambigüedades.



> 💡 **Idea clave:** Markdown no es un único estándar monolítico; coexisten implementaciones que priorizan diferentes necesidades.

---

## 3. Características esenciales

| Rasgo                    | Beneficio práctico                            | Ejemplo conciso             |
|-------------------------|-----------------------------------------------|-----------------------------|
| **Simplicidad**         | Menor curva de aprendizaje                     | `**negrita**`               |
| ***Legibilidad***       | El texto plano “se entiende solo”              | Listas y títulos            |
| **Portabilidad**        | Edición en cualquier entorno                   | Archivos `.md`              |
| **Extensibilidad**      | Funciones extra según el “sabor”               | Tablas, tareas, notas       |
| **Versionable**         | Dif y revisiones claras en Git                 | Cambios línea a línea       |

> Nota: lo que sigue usa rasgos comunes y, cuando procede, elementos habituales en GFM/Pandoc para enriquecer el ejercicio.

---

## 4. Sintaxis viva: del mínimo al enriquecido

### 4.1. Títulos y separación
```markdown
# Título 1
## Título 2
### Título 3
---
