# ALD/FT — Casos Prácticos: Modelos Aplicados de Riesgo

Proyecto académico de aplicación práctica en materia de **Prevención de Lavado de Dinero y Financiamiento del Terrorismo (ALD/FT)**, desarrollado sobre tres escenarios distintos del sistema financiero guatemalteco.

## 🎯 Objetivo

Modelar y cuantificar el riesgo ALD/FT en tres tipos de entidades obligadas bajo la normativa guatemalteca, aplicando enfoque basado en riesgo (EBR), matrices de clasificación, sistemas de alertas y cálculo de índices de exposición, siguiendo criterios de la Superintendencia de Bancos (SIB) y estándares internacionales GAFI/GAFILAT.

## 📜 Marco normativo referenciado

- **Decreto 67-2001** — Ley Contra el Lavado de Dinero u Otros Activos
- **Acuerdo Gubernativo 118-2002** — Reglamento de la Ley ALD (umbrales de reporte, DDC)
- **Resolución JM-108-2010** — Reglamento técnico SIB de medidas mínimas ALD/FT
- **Decreto 58-2005 + AG 86-2006** — Ley para Prevenir y Reprimir el Financiamiento del Terrorismo
- **Decreto 94-2000 + JM-129-2001** — Ley de Libre Negociación de Divisas (aplicable a remesadoras)
- **Recomendaciones GAFI** (1, 10, 12, 13, 14, 16, 19, 20) — Enfoque basado en riesgo, DDC, PEPs, corresponsalía, regla de viaje, países de alto riesgo, reporte de operaciones sospechosas
- **Informes de Evaluación Mutua GAFILAT** (Guatemala, 4ª Ronda) y catálogo de tipologías GAFILAT

## 📂 Estructura del archivo

El proyecto está desarrollado en un único libro de Excel (`.xlsm`) con 19 hojas, organizadas en 3 casos + un dashboard consolidado.

### Caso 1 — Banco Comercial: Matriz de Riesgo ALD/FT
Clasificación de una cartera de 50 clientes de un banco comercial ficticio ("El Amanecer S.A.") en un semáforo de riesgo (Bajo/Medio/Alto/Crítico), determinando el nivel de debida diligencia del cliente (DDC) aplicable a cada segmento según variables como perfil geográfico, canal de atención y condición de PEP.

**Hojas:** Marco Normativo · Parámetros · Umbrales y KYC · Matriz de Clientes · Resumen Ejecutivo

### Caso 2 — Cooperativa de Ahorro y Crédito: Monitoreo de Transacciones Inusuales
Sistema de monitoreo sobre 300 transacciones de una cooperativa ("Futuro Seguro, R.L.", enero–junio 2026), generando alertas automáticas por tipo (monto alto en efectivo, inconsistencia de perfil, posible fraccionamiento, retiros inmediatos) y evaluando la necesidad de Reporte de Operación Sospechosa (ROS).

**Hojas:** Marco Normativo · Parámetros · Socios · Transacciones · ROS · Resumen Ejecutivo

### Caso 3 — Casa de Cambio / Remesadora: Índice de Exposición FT por Corredor
Cálculo de un índice de exposición al riesgo de financiamiento del terrorismo (0-100) por corredor de remesas (México, EE.UU., España, Otros) para una remesadora ficticia ("GuateEnvíos, S.A.", 118 transacciones analizadas), identificando tipologías de smurfing/estructuración transfronteriza y definiendo medidas de mitigación.

**Hojas:** Marco Normativo · Datos Históricos · Parámetros · Transacciones · Índice Exposición FT · Medidas de Mitigación · Resumen Ejecutivo

### Dashboard
Vista consolidada de los indicadores clave de los tres casos.

## 🛠️ Herramientas utilizadas

- **Microsoft Excel** (con macros VBA) — modelado, matrices de riesgo, cálculo de índices y umbrales
- Fórmulas dinámicas para clasificación automática de riesgo y generación de alertas

## ▶️ Cómo usar el archivo

1. Descarga `LDFT_Casos_Prácticos_-_MAR_I.xlsm`
2. Al abrirlo, **habilita el contenido/macros** cuando Excel lo solicite (el archivo utiliza VBA para algunos cálculos y validaciones)
3. Navega por las pestañas en el orden: Marco Normativo → Parámetros → datos del caso → Resumen Ejecutivo
4. El **Dashboard** ofrece una vista rápida de los tres casos sin necesidad de revisar cada hoja individualmente

## ⚠️ Nota

Todos los datos (clientes, socios, transacciones, montos) son **simulados** con fines exclusivamente académicos. No representan información real de ninguna institución financiera.

---
*Proyecto desarrollado como parte de la formación académica en gestión de riesgo del área ALD/FT, con base en normativa guatemalteca vigente.*
