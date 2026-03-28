<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1A0533,50:6B21A8,100:C084FC&height=220&section=header&text=Calculadora%20con%20Proceso%20Detallado&fontSize=38&fontColor=F3E8FF&fontAlignY=38&desc=Herramienta%20Educativa%20de%20Cálculo%20Paso%20a%20Paso%20%E2%80%94%20PIXELBITS%20Studio&descAlignY=62&descSize=16&descColor=DDD6FE&animation=fadeIn" />

<br/>

[![Windows](https://img.shields.io/badge/Windows-Ejecutable-A855F7?style=for-the-badge&logo=windows&logoColor=F3E8FF&labelColor=1A0533)](../../releases)
[![Version](https://img.shields.io/badge/Versión-2.0.0-C084FC?style=for-the-badge&labelColor=1A0533)](#)
[![python-docx](https://img.shields.io/badge/Exporta-Word%20.docx-7C3AED?style=for-the-badge&labelColor=1A0533)](../../releases)
[![License](https://img.shields.io/badge/License-MIT-A855F7?style=for-the-badge&labelColor=1A0533)](LICENSE)
[![Studio](https://img.shields.io/badge/PIXELBITS-Studio-6B21A8?style=for-the-badge&labelColor=1A0533)](https://github.com/Pacheco55)

<br/>

```
✦  Opera · Muestra el proceso · Exporta a Word — ejecutable, sin instalar Python
```

</div>

---

## ¿Qué es esta herramienta?

**Calculadora con Proceso Detallado** es una aplicación de escritorio que no solo calcula — también **explica cada operación paso a paso en tiempo real**, mostrando el proceso matemático completo en un panel de salida coloreado. Está pensada como herramienta educativa para estudiantes, docentes y cualquier persona que quiera entender el *cómo* detrás del resultado, no solo el número final.

El ejecutable es **autocontenido**: no requiere Python instalado en el equipo, no requiere conexión a internet y arranca con doble clic.

> _"No es una calculadora que da respuestas. Es una calculadora que enseña el camino."_

---

## Descarga y ejecución

Descarga el archivo desde [**Releases**](../../releases) y ábrelo con doble clic:

```
CalculadoraDetallada.exe     ← doble clic para iniciar
```

> No necesita Python. No necesita instalación. No necesita conexión a internet.

---

## Interfaz — mapa visual

```
┌──────────────────────────────────────────────────────────┐
│  ✦ Calculadora con Proceso Detallado  ·  PIXELBITS v2    │  ← Header
├──────────────────────────────────────────────────────────┤
│  Operación:  [ 12 × 7 = 84                             ] │  ← Pantalla
├──────────────┬───────────────────────┬───────────────────┤
│ 💾 Word      │   C    CE   ÷    ×    │ 🎲 Rand. Botones  │
│ 🎨 Rand App  │   7     8   9    −    │ 🧹 Limpiar        │
│ 🖍️ Rand Proc │   4     5   6    +    │ 👁  Ver ventana   │
│              │   1     2   3    =    │                   │
│              │   0     .             │                   │
├──────────────┴───────────────────────┴───────────────────┤
│  Proceso Detallado:                                      │
│  ════════════════════════════════════════════            │
│  RESOLVIENDO: 12 × 7                                     │  ← Panel
│  • Multiplicando: 12                                     │    coloreado
│  • Multiplicador: 7                                      │
│  • Operación: 12 × 7 = 84                               │
│  • Tabla de multiplicación:                              │
│    Paso  1: 12 × 1 = 12                                  │
│    Paso  2: 12 × 2 = 24  …                               │
├──────────────────────────────────────────────────────────┤
│  PIXELBITS Studio  ·  Julio Cesar  ·  email  ·  v2.0     │  ← Footer
└──────────────────────────────────────────────────────────┘
```

---

## Modo de uso completo

### 1. Introducir una operación

Tienes dos formas de ingresar números y operadores:

| Método | Cómo hacerlo |
|---|---|
| **Teclado numérico en pantalla** | Haz clic en los botones del panel central |
| **Teclado físico** | Escribe directamente con las teclas de tu equipo |

La pantalla superior muestra la expresión en tiempo real con símbolos legibles (`×` y `÷` en lugar de `*` y `/`).

---

### 2. Atajos de teclado

| Tecla | Acción |
|---|---|
| `0 – 9` | Ingresar dígito |
| `.` | Punto decimal |
| `+  -  *  /` | Operadores aritméticos |
| `=` o `Enter` | Calcular y mostrar proceso |
| `C` | Limpiar todo (operación + proceso) |
| `E` | Limpiar solo la operación actual |
| `Backspace` | Borrar el último carácter ingresado |

---

### 3. Leer el panel de proceso detallado

Al presionar `=`, el panel inferior muestra el desglose completo de la operación. Los colores distinguen el rol de cada elemento:

| Color | Significado |
|---|---|
| 🟣 Morado | Títulos de sección y separadores |
| 🟡 Amarillo | Etiquetas explicativas de cada paso |
| 🔵 Azul | Números y valores |
| 🔴 Rojo | Operadores (+, −, ×, ÷) |
| 🟢 Verde brillante | Resultado final |
| 🩵 Cian | Subtotales intermedios |

**Ejemplo de salida para `12 × 7`:**

```
══════════════════════════════════════════════════════
RESOLVIENDO: 12 × 7
  Herramienta: Calculadora con Proceso Detallado v2.0.0
  Autor:       Pacheco Rojas Julio Cesar  ·  PIXELBITS Studio
══════════════════════════════════════════════════════
Proceso de multiplicación:
• Multiplicando: 12
• Multiplicador: 7
• Operación: 12 × 7 = 84
• Tabla de multiplicación:
  Paso  1: 12 × 1 = 12
  Paso  2: 12 × 2 = 24
  Paso  3: 12 × 3 = 36
  Paso  4: 12 × 4 = 48
  Paso  5: 12 × 5 = 60
  Paso  6: 12 × 6 = 72
  Paso  7: 12 × 7 = 84
══════════════════════════════════════════════════════
```

---

### 4. Operaciones soportadas

| Operación | Símbolo en pantalla | Proceso mostrado |
|---|:---:|---|
| Suma | `+` | Identificación de sumandos y resultado |
| Resta | `−` | Minuendo, sustraendo y resultado |
| Multiplicación | `×` | Tabla paso a paso cuando el multiplicador es ≤ 12 |
| División | `÷` | Dividendo, divisor, cociente y resto si no es exacta |
| Expresiones compuestas | `( )  + − × ÷` | Desglose PEMDAS completo |

---

### 5. Expresiones compuestas (PEMDAS)

La calculadora resuelve expresiones con múltiples operaciones respetando el orden matemático estándar:

```
Entrada:  3 + 4 * 2 - 1

Proceso mostrado:
  Expresión compuesta — orden PEMDAS:
    1. Paréntesis
    2. × y ÷  (izq → der)
    3. + y −  (izq → der)

  4 * 2 = 8
  3 + 8 = 11
  11 - 1 = 10

  Resultado final: 10
```

Puedes usar paréntesis para forzar el orden: `(3 + 4) * 2`

---

### 6. Botones de acción adicionales

#### `💾 Exportar a Word`

Guarda el contenido completo del panel de proceso en un archivo `.docx` con portada, fecha y hora de exportación, el proceso detallado en fuente monoespaciada y pie de página con créditos de **PIXELBITS Studio**.

#### `🎨 Randomizar App`

Cambia el esquema de color de toda la ventana principal a una combinación aleatoria. Útil para personalizar el entorno en sesiones largas.

#### `🖍️ Randomizar Proceso`

Cambia el color del texto del panel de proceso a un tono aleatorio contrastante.

#### `🎲 Randomizar Botones`

Aplica un color aleatorio a todos los botones del teclado numérico.

#### `🧹 Limpiar Proceso`

Borra únicamente el panel de proceso detallado, manteniendo la operación actual en la pantalla de entrada.

#### `👁 Ver en Ventana`

Abre una ventana secundaria con el historial completo del proceso — útil para tener los pasos visibles mientras se realizan nuevas operaciones.

---

## Lógica de proceso por tipo de operación

### Suma y Resta
Muestra el nombre de los operandos (sumandos / minuendo y sustraendo), la operación simbólica completa y el resultado.

### Multiplicación
Muestra el proceso completo y, cuando ambos operandos son enteros con multiplicador ≤ 12, genera automáticamente la **tabla de multiplicación paso a paso** desde el paso 1 hasta el paso N.

### División
Muestra dividendo, divisor y resultado decimal. Si la división no es exacta, muestra también el **cociente entero** y el **resto**, útil para aprender división con residuo.

### Expresiones compuestas
Aplica el algoritmo **PEMDAS** iterativamente: primero resuelve paréntesis de adentro hacia afuera, luego multiplicaciones y divisiones de izquierda a derecha, y finalmente sumas y restas de izquierda a derecha. Cada subexpresión resuelta aparece como un paso independiente.

---

## Licencia

Distribuido bajo la **Licencia MIT**. Consulta el archivo [`LICENSE`](LICENSE) para más detalles.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:C084FC,50:6B21A8,100:1A0533&height=120&section=footer" />

**Hecho con 💜 por [Pacheco Rojas Julio Cesar](https://github.com/Pacheco55)**

[PIXELBITS Studio](https://github.com/Pacheco55) &nbsp;·&nbsp; [studiospixelbits@gmail.com](mailto:studiospixelbits@gmail.com)

[![GitHub](https://img.shields.io/badge/GitHub-Pacheco55-A855F7?style=flat-square&logo=github&labelColor=1A0533)](https://github.com/Pacheco55)
[![Email](https://img.shields.io/badge/Email-studiospixelbits%40gmail.com-7C3AED?style=flat-square&logo=gmail&logoColor=white&labelColor=1A0533)](mailto:studiospixelbits@gmail.com)

<sub>Calculadora con Proceso Detallado v2.0.0 &nbsp;·&nbsp; PIXELBITS Studio © 2026</sub>

</div>
