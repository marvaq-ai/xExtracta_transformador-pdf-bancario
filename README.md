<div align="center">

# 🧾 xExtracta

**Convertí extractos bancarios en PDF a planillas de Excel —con imputación contable sugerida— de forma automática y 100% local.**

![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?logo=windows&logoColor=white)
![Bancos](https://img.shields.io/badge/Bancos-13-1565C0)
![Imputación contable](https://img.shields.io/badge/Imputaci%C3%B3n%20contable-autom%C3%A1tica-6A1B9A)
![Procesamiento local](https://img.shields.io/badge/Procesamiento-100%25%20local-2E7D32)
![Licencia](https://img.shields.io/badge/Licencia-Propietaria-red)

Un producto de **Marvaq** · [hello@marvaq.com](mailto:hello@marvaq.com)

### [⬇️ Descargar xExtracta](https://xextracta.marvaq.com/)

</div>

---

## 📑 Tabla de contenidos

- [Descripción general](#-descripción-general)
- [Características](#-características)
- [Imputación contable automática](#-imputación-contable-automática)
- [Bancos soportados](#-bancos-soportados)
- [Descarga e instalación](#-descarga-e-instalación)
- [Cómo se usa](#-cómo-se-usa)
- [Prueba y suscripción](#-prueba-y-suscripción)
- [Seguridad y privacidad](#-seguridad-y-privacidad)
- [Licencia](#-licencia)
- [Contacto](#-contacto)

---

## 🎯 Descripción general

**xExtracta** es una aplicación de escritorio para **Windows** que automatiza la conversión de **extractos bancarios en PDF a planillas de Excel**. Todo el procesamiento ocurre **de forma local, en tu propia computadora**: seleccionás una carpeta con los PDF y obtenés un archivo Excel por banco, listo para trabajar.

Pero va un paso más allá de la simple extracción: **cada movimiento sale con una cuenta contable sugerida**, para que arranques desde un borrador ya clasificado en vez de una planilla en blanco.

Está pensada para **contadores independientes y estudios contables** que necesitan procesar grandes volúmenes de movimientos bancarios sin cargarlos —ni clasificarlos— a mano.

> **Principio clave:** el contenido de tus extractos bancarios **nunca sale de tu equipo**. La aplicación no sube, almacena ni transmite los datos de tus movimientos.

---

## ✨ Características

- 📄 **Conversión PDF → Excel**: un archivo `.xlsx` por banco, con fechas e importes en formato reconocible por Excel.
- 🧮 **Imputación contable sugerida**: cada movimiento viene con su cuenta contable propuesta en una columna aparte. [Ver detalle ↓](#-imputación-contable-automática)
- 🔒 **Procesamiento 100% local**: los datos bancarios se trabajan solo en tu equipo.
- 🔑 **Licencia por equipo**: una licencia activa por computadora, con **tolerancia offline** para seguir trabajando sin conexión por unos días.
- 🎁 **Prueba gratuita** autogestionada desde la propia app.
- 💳 **Suscripción mensual** simple a través de MercadoPago.
- ♻️ **Recuperación de licencia** por correo electrónico.
- 🔐 **Soporte de PDF protegidos con contraseña** y de **extractos con varias cuentas**.
- 🔔 **Aviso de actualizaciones** cuando hay una nueva versión disponible.

---

## 🧮 Imputación contable automática

xExtracta no solo extrae los movimientos: los **pre-imputa**. Cada fila del Excel incluye una columna **`Imputación`** con la cuenta contable sugerida, para que el trabajo más tedioso después de la extracción —clasificar movimiento por movimiento— ya venga adelantado.

### 🎯 Honesto por diseño

Una imputación **confiada pero equivocada es peor que un casillero vacío**: te obliga a descubrir y deshacer el error más tarde, cuando ya confiaste en él. Por eso xExtracta sugiere una cuenta **solo cuando el movimiento es inequívoco**. Cuando no lo es, marca el casillero como *"a clasificar"* o lo deja señalado para revisión, en lugar de inventar una cuenta para rellenar.

El resultado: vos mantenés el control. La imputación es un **punto de partida revisable, no un reemplazo de tu criterio profesional** —y nunca te mete una clasificación inventada que tengas que ir a cazar después.

### 🇦🇷 Entiende el vocabulario bancario argentino

Reconoce y clasifica los movimientos típicos de los extractos locales, con sus distintas formas de nombrarlos según el banco:

- **Impuesto Ley 25.413** sobre débitos y créditos
- **Percepciones y retenciones de IIBB**, regímenes **SIRCREB** y **ARBA**
- **Retenciones y percepciones de IVA y Ganancias**
- **Comisiones y gastos bancarios**, e **IVA sobre comisiones** (crédito fiscal del cliente)
- **Acreditaciones de tarjetas** (Visa, Cabal, Maestro, Fiserv/First Data, Posnet) → **Deudores por ventas**
- **Transferencias** a terceros y **entre cuentas propias** (las distingue: las propias no impactan resultado)
- **Débitos automáticos**, **impuesto de sellos**, **sueldos y honorarios**, **intereses**, **plazos fijos** y más
- **Billeteras virtuales**: rendimientos del saldo remunerado, dinero reservado en objetivos de ahorro y pagos con QR en comercios

### 🏦 Afinado banco por banco

Cada banco nombra las mismas cosas distinto (`S/CRED`, `S/CR`, `DB/CR BANCARIOS`, `e/ cuentas propias`, `IMP DEB TASA GRAL`…). La imputación está **calibrada y validada banco por banco, sobre miles de movimientos reales**, para que un mismo concepto caiga siempre en la misma cuenta sin importar cómo lo escriba cada entidad.

> 💡 El resultado es un Excel donde la **mayoría de los movimientos ya viene clasificado**, y lo que queda sin clasificar está **claramente señalado** para que lo resuelvas en segundos.

---

## 🏦 Bancos soportados

`BBVA` · `BTF` · `Galicia` · `Galicia +` · `Nación` · `Santander` · `Macro` · `Patagonia` · `PBA` · `Credicoop` · `Hipotecario` · `ICBC` · `Mercado Pago`

**Novedades de la versión 2.1.2:**

| | |
|---|---|
| 🔷 **Patagonia: los dos formatos** | Ahora también lee la exportación *"Movimientos de Cuenta"* del homebanking, además del resumen mensual. Antes ese archivo no devolvía ningún movimiento. |
| 🔷 **Débito y crédito verificados contra el saldo** | La columna ya no depende de una lista de palabras: se lee la posición real en el PDF y se **verifica contra el saldo que imprime el banco**. Si la aritmética la desmiente, se corrige sola. Un concepto que el banco estrene mañana ya no puede caer del lado equivocado. |
| 🔷 **Una cuenta por planilla** | El *"Estado de cuentas unificado"* trae **todas** las cuentas del titular —y la segunda suele ser en **dólares**—. Antes se sumaban las dos monedas en la misma columna. [Ver cómo elegir la cuenta ↓](#-cómo-se-usa) |
| 🔷 **Menos filas que no eran movimientos** | Las secciones de detalle que el resumen imprime al final (débitos automáticos ya listados, y los **rechazados por falta de fondos**, que nunca ocurrieron) ya no entran como movimientos. |

**Novedades de la versión 2.1.0:**

| | |
|---|---|
| 💜 **Mercado Pago** | Resumen de cuenta en pesos de la billetera (CVU): pagos con QR, transferencias, rendimientos del saldo y dinero reservado. |
| 🔵 **Galicia +** (ex HSBC) | Extracto de cuenta corriente en el formato que Galicia mantiene de HSBC, con su detalle de contraparte y CUIT. |
| 🔴 **ICBC** | Resumen mensual de cuenta corriente. |

> 🏦 **Extractos con varias cuentas — Patagonia y Macro.** El resumen de Patagonia lista todas las cuentas del titular: la operativa en pesos y, casi siempre, una cuenta especial **en dólares**. Sumarlas en una misma planilla daría dos monedas mezcladas y una columna de saldo sin sentido, así que xExtracta exporta **una sola cuenta**: sin `CuentaObjetivo.txt` toma la primera (la de pesos), y con el archivo en la carpeta toma la que le indiques. Si el archivo pide una cuenta que ese PDF no tiene, te lo avisa y nombra las que sí están, en lugar de exportar otra en su lugar.

> 💡 **No hace falta escribir el nombre exacto de la carpeta.** xExtracta reconoce las formas en que la gente los escribe: `Nacion`, `Provincia`, `BIP`, `Frances`, `MP`, `Mercadopago`, `HSBC`, `Galicia más`… y tolera acentos, el "Banco" adelante y errores de tipeo leves. La lista completa de nombres aceptados está en el botón **Bancos** de la aplicación.

> ¿Falta tu banco? Lo incorporamos: enviá 2–3 extractos PDF de muestra a [hello@marvaq.com](mailto:hello@marvaq.com).

---

## ⬇️ Descarga e instalación

1. Descargá el instalador desde **[xextracta.marvaq.com](https://xextracta.marvaq.com/)**.
2. Ejecutá **`xExtracta-Setup.exe`** y seguí los pasos del asistente de instalación.
3. Una vez instalado, abrí **xExtracta** desde el acceso directo en el escritorio o el menú Inicio.
4. **Requisitos:** Windows 10 u 11 (64 bits).

> **Si Windows muestra un aviso al instalarlo:** como la aplicación es nueva, es posible que SmartScreen muestre un cartel de *"editor desconocido"*. Es normal y no significa que el archivo sea peligroso. Hacé clic en **Más información** y luego en **Ejecutar de todas formas**.

---

## 🧭 Cómo se usa

1. Abrí **xExtracta** y activá tu licencia (o pedí la prueba gratuita).
2. Presioná **Seleccionar carpeta y procesar** y elegí la carpeta a convertir.
3. Al finalizar, se genera un **Excel (`.xlsx`) por banco** —con la columna **`Imputación`** incluida— dentro de la carpeta de cada banco.

**Para que el resultado sea correcto, organizá los PDF así:**

- **Una carpeta por banco**, nombrada como el banco (`BBVA`, `Galicia`, `Nación`, …). No hace falta que sea exacto: también toma `Nacion`, `Banco Provincia`, `MP`, `HSBC` y variantes por el estilo.
- **Máximo 12 PDF por carpeta** (uno por mes).
- Numerá los archivos con **cero adelante** para que se ordenen bien: `01, 02, … 11, 12` (un `1, 2, … 11` se desordena).
- **PDF con contraseña** → agregá un archivo `Contraseña.txt` en la carpeta, con solo la contraseña.
- **Extractos con varias cuentas** (Patagonia, Macro) → xExtracta exporta la **primera** cuenta del PDF, que es la operativa en pesos. Para trabajar otra, agregá un archivo `CuentaObjetivo.txt` con el **número de cuenta**, el **CBU** (con o sin espacios) o **parte del nombre** (por ejemplo `DOLARES`). Una cuenta por ejecución.

> 💡 **Antes de un nuevo proceso, limpiá la carpeta:** xExtracta procesa *todos* los PDF que encuentre en cada carpeta. Si no quitás los ya procesados, la próxima vez volverá a procesarlos a todos. La guía rápida en PDF (incluida con tu licencia de prueba) explica todo esto en detalle.

---

## 💳 Prueba y suscripción

- **Prueba gratuita de 4 días**, sin cargo.
- Para continuar, **suscripción mensual de $9.000 ARS** a través de **MercadoPago**.
- Podés **recuperar tu licencia** por correo en cualquier momento desde la app.

---

## 🔐 Seguridad y privacidad

- 🛡️ **El contenido de tus extractos bancarios se procesa únicamente de forma local** y nunca se transmite ni se sube a ningún servidor. La imputación contable también se calcula **en tu propio equipo**.
- 🔑 Las **contraseñas de los PDF** se usan de manera transitoria, solo para abrir el archivo durante el procesamiento: **no se almacenan ni se transmiten**.
- 📡 Para validar y administrar la licencia, la aplicación transmite **únicamente datos de licencia** (la clave, un identificador técnico del equipo y la versión de la app) y, al pedir prueba o suscripción, tu **nombre y correo**. En ningún caso viaja el contenido de los extractos.
- 🧾 El tratamiento de datos se realiza conforme a la **Ley 25.326** de Protección de Datos Personales (Argentina), bajo el control de la **Agencia de Acceso a la Información Pública (AAIP)**. Podés ejercer tus derechos de acceso, rectificación y supresión escribiendo a [hello@marvaq.com](mailto:hello@marvaq.com).

---

## 📄 Licencia

**Software propietario.** © Marvaq. Todos los derechos reservados.
Protegido por la **Ley 11.723** de Propiedad Intelectual (Argentina). Prohibida su reproducción, distribución, ingeniería inversa o reventa sin autorización expresa del titular.

---

## 📬 Contacto

**Marvaq** — [hello@marvaq.com](mailto:hello@marvaq.com)

<div align="center">
<sub>Hecho con ☕ en Argentina · Tierra del Fuego</sub>
</div>
