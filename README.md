### 📈 Fidelity Fund NAV Scraper

Script en Python que **extrae automáticamente el NAV (valor liquidativo) y la fecha** de un fondo de Fidelity (ISIN `IE00BYX5NX33`) desde fuentes oficiales, los **normaliza al formato europeo** y los **almacena en un Excel histórico** sin duplicar registros.

#### ✨ Funcionalidades

* Obtiene el **NAV y fecha** desde la API oficial de Fidelity.
* Formatea:

  * Fecha → `DD/MM/YYYY`
  * Precio → coma decimal (`12,4299`)
* Inserta el nuevo dato en la **primera fila** del Excel.
* Evita **duplicados por fecha**.
* Ideal para **seguimiento histórico diario**.

#### 🛠️ Tecnologías

* Python
* `requests`
* `pandas`
* `datetime`
* Excel (`.xlsx`)

#### 📂 Resultado

Archivo `Historical_NAVs_IE00BYX5NX33.xlsx` con histórico ordenado y actualizado automáticamente.

Simple, reproducible y listo para automatizar.

