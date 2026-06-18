# IRS LLC Deadline Calculator

Calculadora gratuita y de código abierto para **estimar fechas clave del IRS** de una LLC de EE. UU. de dueño extranjero. Es una herramienta estática (HTML, CSS y JavaScript en un solo archivo), sin dependencias ni backend: se abre en cualquier navegador.

Estima:

- Fecha de **Form 5472** con **pro forma Form 1120**.
- Fecha límite para solicitar extensión con **Form 7004**.
- Fecha extendida estimada cuando aplica la extensión de seis meses.

## Más recursos

Encuentra más herramientas y contenido sobre contabilidad para LLC en:

https://bookkeepingaldia.com/

## Para quién sirve

- Dueños de una LLC de EE. UU. de dueño extranjero (*foreign-owned, single-member LLC*).
- No residentes que necesitan ubicar sus fechas de presentación ante el IRS.
- Cualquier persona que quiera estimar plazos antes de confirmarlos con un preparador fiscal.

## Variables que toma en cuenta

- **Año fiscal** de la LLC.
- **Mes de cierre fiscal**.
- Si se piensa solicitar **extensión** con Form 7004.

Los detalles del cálculo y sus límites están en [metodologia.md](metodologia.md).

## Uso local

No requiere instalación. Tienes dos opciones:

1. **Abrir el archivo directamente:** haz doble clic en `index.html`.
2. **Servidor local:**

   ```bash
   python -m http.server 8000
   ```

   Luego abre `http://localhost:8000` en tu navegador.

## Descargar o clonar

```bash
git clone https://github.com/Danielher20/irs-llc-deadline-calculator.git
cd irs-llc-deadline-calculator
```

O descarga el repositorio como ZIP desde GitHub con el botón **Code → Download ZIP**.

## Aviso importante

Esta herramienta ofrece una **estimación educativa** y **no sustituye asesoría fiscal, legal ni contable**. Las fechas del IRS pueden cambiar por fines de semana, feriados federales, reglas de año fiscal, clasificación de la entidad o circunstancias particulares del contribuyente. Solo ajusta fines de semana; no valida todos los feriados federales. Confirma siempre con un preparador fiscal antes de presentar.

## Fuentes oficiales

- [IRS: Instructions for Form 5472](https://www.irs.gov/instructions/i5472)
- [IRS: About Form 5472](https://www.irs.gov/forms-pubs/about-form-5472)
- [IRS: About Form 7004](https://www.irs.gov/forms-pubs/about-form-7004)
- [IRS: Instructions for Form 1120](https://www.irs.gov/instructions/i1120)

## Créditos

Desarrollada y mantenida por [Bookkeeping al Día](https://bookkeepingaldia.com/).

## Licencia

Distribuida bajo licencia [MIT](LICENSE).
