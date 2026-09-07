# Implementación de CRUD con Rails y RSpec

El sistema debe permitir la gestión completa de productos en una tienda online. Los productos tienen nombre, precio, stock y categoría. El sistema debe validar que los nombres de los productos no sean duplicados y que los precios no sean negativos. En caso de que una validación falle, el sistema debe registrar el error y notificar al usuario. Los productos se gestionan a través de una interfaz de usuario y una API RESTful.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Ruby on Rails |
| **Nivel** | junior-l1 |
| **Tipo** | practical |
| **Tiempo estimado** | 8 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Configuración del entorno y modelo básico

**Objetivo:** Configurar el entorno de desarrollo y crear el modelo básico de Producto.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Configurar el entorno de desarrollo con Rails.
- Crear el modelo de Producto con los atributos necesarios.
- Asegurar que el modelo valida los atributos según las reglas del dominio.

**Entregable:** Modelo de Producto con validaciones básicas y migraciones aplicadas.

<details>
<summary>Pistas de conocimiento</summary>

- Considera las validaciones necesarias para los atributos del producto.
- Piensa en cómo manejar los errores de validación.

</details>

### Fase 2: Implementación de controladores y vistas

**Objetivo:** Crear los controladores y vistas para la gestión de productos.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Crear los controladores para las operaciones CRUD de productos.
- Implementar las vistas para la interfaz de usuario.
- Asegurar que las vistas y controladores interactúen correctamente.

**Entregable:** Controladores y vistas funcionales para la gestión de productos.

<details>
<summary>Pistas de conocimiento</summary>

- Piensa en cómo estructurar los controladores para las operaciones CRUD.
- Considera la interacción entre las vistas y los controladores.

</details>

### Fase 3: Implementación de pruebas con RSpec

**Objetivo:** Escribir pruebas para validar el funcionamiento del CRUD de productos.

**Tiempo estimado:** 3 horas

**Instrucciones:**

- Escribir pruebas unitarias para el modelo de Producto.
- Escribir pruebas de integración para los controladores de productos.
- Asegurar que todas las pruebas pasan correctamente.

**Entregable:** Pruebas unitarias y de integración que validan el funcionamiento del CRUD de productos.

<details>
<summary>Pistas de conocimiento</summary>

- Considera los diferentes escenarios de prueba para el modelo y los controladores.
- Piensa en cómo estructurar las pruebas para cubrir todos los casos de uso.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es un modelo en Rails y para qué sirve?
- **paraQueSirve**: ¿Para qué sirven las validaciones en el modelo de Producto?
- **comoSeUsa**: ¿Cómo se usan las pruebas unitarias y de integración en Rails?
- **erroresComunes**: ¿Cuáles son los errores comunes al implementar un CRUD en Rails?
- **queDecisionesImplica**: ¿Qué decisiones implica la estructuración de los controladores para las operaciones CRUD?

## Criterios de Evaluacion

- Configuración correcta del entorno de desarrollo con Rails.
- Creación del modelo de Producto con validaciones básicas.
- Implementación de controladores y vistas funcionales para la gestión de productos.
- Escritura de pruebas unitarias y de integración que validan el funcionamiento del CRUD de productos.

## Como trabajar con un asistente de IA

- **AGENTS.md** — instrucciones nativas del repo (Cursor, Codex, Copilot, Gemini, Claude Code). Abrí el proyecto y el agente las carga solo.
- **PROMPT_MEJORA.md** — el mismo prompt, para copiar y pegar en un chat (claude.ai, ChatGPT, etc.).

---

*Reto generado automaticamente por Challenge Generator - Pragma*
