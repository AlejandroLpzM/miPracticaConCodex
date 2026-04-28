# Actividad de GitHub Classroom: Plantilla de Propuesta de Práctica Temática (Enfoque en Documentación)

## 1) Título de la actividad
**Diseño de Propuesta para Mini Práctica Temática en Sistemas**

> Ejemplos de título para el proyecto que propondrá cada estudiante:
> - “Mini Toolkit en ARM64”
> - “Asistente de Estudio en Terminal”
> - “Reporteador de Información del Sistema”
> - “Organizador de Archivos”
> - “Juego de Aprendizaje en Línea de Comandos”

---

## 2) Descripción general
En esta actividad **vas a diseñar la propuesta de un proyecto pequeño** con temática de arquitectura de computadoras o programación de sistemas.

La propuesta debe plantearse para implementar con **un lenguaje principal** (elige solo uno):
- **ARM64 Assembly**
- **C**
- **Python**
- **Bash**

> **Nota importante:** Si eliges **ARM64 Assembly**, tu alcance debe ser **muy pequeño** (programas cortos y objetivos concretos), porque el enfoque de la actividad es la **planeación y documentación**, no desarrollar una solución extensa.

### Prioridad académica de la actividad
1. Definir y justificar una idea realista.
2. Documentar claramente caso de uso, alcance y límites.
3. Proponer estructura de repositorio y plan de pruebas.
4. Escribir solo el código mínimo necesario (opcional en esta etapa).

La propuesta debe ser viable para estudiantes que usan herramientas con límites de uso (por ejemplo, versiones gratuitas de asistentes de IA), por lo que **se deben evitar proyectos grandes o complejos**.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Opcionales:
- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio
Usa como referencia la siguiente estructura mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

---

## 5) Instrucciones detalladas para completar la propuesta

### A. `README.md`
Incluye:
1. **Nombre tentativo del proyecto**.
2. **Lenguaje principal elegido** (ARM64 Assembly, C, Python o Bash).
3. **Resumen breve** (5–8 líneas).
4. **Objetivo general** (1 párrafo).
5. **Alcance** (qué sí hará).
6. **Fuera de alcance** (qué no hará).
7. **Cómo ejecutar (tentativo)**, aunque sea preliminar.

---

### B. `docs/propuesta.md`
Desarrolla la propuesta con esta plantilla:

```markdown
# Propuesta de proyecto

## 1. Nombre del proyecto

## 2. Lenguaje principal
- [ ] ARM64 Assembly
- [ ] C
- [ ] Python
- [ ] Bash

## 3. Problema que se quiere resolver
(Explica una necesidad concreta en contexto de terminal/sistemas.)

## 4. Objetivo general

## 5. Objetivos específicos
- Objetivo específico 1
- Objetivo específico 2
- Objetivo específico 3

## 6. Alcance (MVP)
(Define la versión mínima funcional en términos simples y medibles.)

## 7. Restricciones técnicas
- Sin frameworks grandes
- Sin APIs de pago
- Sin bases de datos
- Sin nube
- Sin contenedores
- Dependencias mínimas

## 8. Justificación técnica del lenguaje elegido
(¿Por qué ese lenguaje es adecuado para el tamaño y tipo de práctica?)

## 9. Riesgos y mitigaciones
- Riesgo 1 → Mitigación
- Riesgo 2 → Mitigación

## 10. Cronograma breve (1–2 semanas)
- Día/Periodo 1:
- Día/Periodo 2:
- Día/Periodo 3:
```

---

### C. `docs/caso_de_uso.md`
Incluye al menos:

```markdown
# Caso de uso principal

## 1. Actor principal
(Usuario final en terminal)

## 2. Contexto
(En qué situación se usa la herramienta)

## 3. Precondiciones
- Precondición 1
- Precondición 2

## 4. Flujo principal
1. Paso 1
2. Paso 2
3. Paso 3

## 5. Flujos alternos
- Alterno A:
- Alterno B:

## 6. Resultado esperado
(Qué obtiene el usuario al finalizar)

## 7. Criterios de aceptación
- Criterio 1 (medible)
- Criterio 2 (medible)
- Criterio 3 (medible)
```

---

### D. `docs/estructura_repositorio.md`
Documenta y justifica la organización:

```markdown
# Estructura del repositorio

## 1. Árbol de carpetas propuesto
(Pega aquí el árbol de directorios)

## 2. Propósito de cada carpeta/archivo
- README.md:
- docs/:
- src/:
- scripts/:
- tests/:

## 3. Convenciones de nombres
(Archivos, scripts y pruebas)

## 4. Estrategia de crecimiento
(Si el proyecto creciera, ¿qué se agregaría sin romper el orden?)
```

---

### E. `docs/plan_de_pruebas.md`
Incluye pruebas simples y realistas:

```markdown
# Plan de pruebas

## 1. Objetivo de pruebas

## 2. Alcance de pruebas
(Qué componentes se probarán)

## 3. Casos de prueba
| ID | Descripción | Entrada | Resultado esperado |
|----|-------------|---------|--------------------|
| CP-01 | ... | ... | ... |
| CP-02 | ... | ... | ... |
| CP-03 | ... | ... | ... |

## 4. Criterios de éxito
- Criterio 1
- Criterio 2

## 5. Limitaciones
(Qué no se probará en esta etapa y por qué)
```

---

## 6) Reglas de alcance (obligatorias)
Para mantener la práctica pequeña y viable:

- Máximo sugerido: **1 funcionalidad principal + 1 o 2 complementarias**.
- Debe correr en entorno local, desde terminal.
- No usar frameworks pesados.
- No integrar servicios externos de pago.
- Evitar dependencias difíciles de instalar.
- Si usas Assembly ARM64, prioriza una sola rutina o flujo corto bien documentado.

---

## 7) Criterios de evaluación sugeridos (rúbrica)

| Criterio | Porcentaje |
|---|---:|
| Claridad de la propuesta y problema | 20% |
| Coherencia del alcance (proyecto pequeño y viable) | 20% |
| Calidad de documentación técnica | 25% |
| Calidad del caso de uso y criterios de aceptación | 15% |
| Calidad del plan de pruebas | 10% |
| Organización del repositorio | 10% |

---

## 8) Entrega
- Publica todos los archivos en este mismo repositorio de GitHub Classroom.
- Asegúrate de que la propuesta sea **autocontenida**: cualquier docente o compañero debe entender qué harás, cómo lo organizarás y cómo validarás resultados, incluso si todavía hay poco código.

---

## 9) Recomendación final del instructor
Antes de programar mucho, invierte tiempo en escribir una propuesta sólida. En sistemas, una buena planeación reduce errores, mejora la depuración y hace más claro el objetivo técnico del proyecto.
